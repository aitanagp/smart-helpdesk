# 🛠️ Helpdesk Inteligente

Un sistema de gestión de incidencias de nivel empresarial diseñado con una arquitectura modular. Este proyecto centraliza el soporte técnico conectando un portal web para empleados con una aplicación multiplataforma para técnicos IT a través de una API unificada.

## 🚀 Arquitectura y Stack Tecnológico

El proyecto está dividido en microservicios y despliegues independientes, abarcando infraestructura, backend y clientes frontend:

*   **Backend & API:** Python (FastAPI) + SQLAlchemy.
*   **Base de Datos:** PostgreSQL 16 (desplegado en contenedores).
*   **Portal Web (Empleados):** HTML5, CSS3, JavaScript.
*   **App Técnico (Soporte):** Kotlin Multiplatform (Compose Desktop & Android).
*   **Infraestructura:** Docker & Docker Compose.

## 📁 Estructura del Monorepo

*   `/backend` - API RESTful y modelos de datos.
*   `/web` - Interfaz estática para la creación y seguimiento de tickets.
*   `/app-tecnico` - Cliente nativo para la resolución de incidencias.
*   `/docs` - Documentación técnica y diagramas de base de datos.

## ⚙️ Estado del Proyecto
Actualmente en fase de desarrollo (Fase 1: Infraestructura y Backend).