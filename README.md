# HI SAGA 🎉

Backend del sistema web de **HI SAGA**, desarrollado como parte de un proyecto académico.

El sistema busca apoyar la gestión de clientes, cotizaciones, eventos e inventario, proporcionando una base para la administración de los diferentes procesos de la empresa.

## 🚀 Tecnologías

- Java 17
- Spring Boot
- Spring Data JPA
- Spring Security
- PostgreSQL
- Maven
- Git & GitHub

## 📂 Estructura

El proyecto utiliza una arquitectura por capas:

- **Model** → Entidades y datos del sistema.
- **Repository** → Acceso a la base de datos.
- **Service** → Lógica de negocio.
- **Controller** → Endpoints de la API.
- **Config** → Configuraciones del sistema.

## 🔧 Estado actual

Actualmente se encuentra implementado el módulo inicial de **Clientes**, incluyendo:

- Crear clientes
- Consultar clientes
- Consultar cliente por ID
- Eliminar clientes
- Persistencia en PostgreSQL

El proyecto continuará creciendo mediante nuevos módulos y funcionalidades.

## 🛠️ Instalación

1. Clonar el repositorio.
2. Configurar PostgreSQL.
3. Crear una base de datos llamada `hisaga`.
4. Configurar las credenciales de PostgreSQL en `application.properties`.
5. Ejecutar el proyecto con Maven o desde IntelliJ IDEA.

## 👥 Equipo

**HI SAGA Team**

Proyecto académico — 2026
