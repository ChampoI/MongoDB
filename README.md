# 🧠 Proyecto de Demostración: MongoDB con Docker

Este repositorio demuestra habilidades prácticas en el diseño y gestión de bases de datos NoSQL utilizando MongoDB. El objetivo principal es aplicar patrones eficientes, explorar características avanzadas del motor de base de datos y facilitar un entorno replicable mediante Docker.

## 🚀 Objetivos del Proyecto

- **Demostrar Competencia Técnica**: Evidenciar experiencia en operaciones CRUD, consultas complejas, modelado flexible y optimización en MongoDB.
- **Explorar Capacidades de MongoDB**: Utilizar funcionalidades como agregaciones, índices, validaciones y expresiones lógicas.
- **Proveer un Entorno Reproducible**: Implementar un entorno de desarrollo auto-contenido mediante `Docker` y `docker-compose`, permitiendo una ejecución sencilla y uniforme en cualquier sistema operativo.

## 🛠️ Tecnologías y Herramientas

| Herramienta        | Descripción |
|--------------------|-------------|
| **MongoDB**        | Base de datos principal, con operaciones y consultas diseñadas para escenarios reales. |
| **Docker**         | Proporciona aislamiento y portabilidad, eliminando problemas de configuración local. |
| **Docker Compose** | Orquestación de servicios para levantar el contenedor de MongoDB de forma rápida y consistente. |

## 📂 Estructura del Repositorio

```
├── src/                   # Scripts de ejemplo y pruebas con MongoDB
│   ├── 01-playground/     # Comandos básicos de prueba
│   ├── 02-docker/         # Comandos útiles de Docker
│   ├── ...                # Otras operaciones MongoDB (insert, update, query, etc.)
├── docker-compose.yml     # Configuración para levantar MongoDB en Docker
├── .gitignore             # Archivos y carpetas ignoradas por Git
└── README.md              # Documentación del proyecto
```

Cada carpeta en `src/` representa un módulo temático relacionado con una operación o concepto importante en MongoDB. Está diseñada para facilitar el aprendizaje progresivo o como base para proyectos reales.

## 🧪 ¿Cómo Ejecutarlo?

### Requisitos Previos

- Tener instalado [Docker](https://docs.docker.com/get-docker/)
- Tener instalado [Docker Compose](https://docs.docker.com/compose/install/)

### Levantar el entorno

```bash
docker-compose up -d
```

Esto ejecutará un contenedor con MongoDB accesible desde `localhost:27017`.

### Detener los servicios

```bash
docker-compose down
```

## 📌 Notas Adicionales

- El proyecto se ejecuta sin necesidad de configuraciones adicionales.
- Ideal para prácticas educativas, tests rápidos o como punto de partida para aplicaciones más complejas.

## 🧑‍💻 Autor

Desarrollado por **Champol C.**  
Este proyecto forma parte de un portafolio técnico enfocado en bases de datos NoSQL, DevOps y buenas prácticas de desarrollo backend.

## 📄 Licencia

Este repositorio se distribuye bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles (si decides agregarlo).

