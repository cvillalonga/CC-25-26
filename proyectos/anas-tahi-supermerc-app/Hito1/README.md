# Hito 1 — Definición del proyecto

## Título del proyecto
Supermerc-App

## Autor
- Anas Tahir

## Resumen
Este proyecto consiste en una aplicación de gestión de supermercado basada en microservicios. 
Permitirá gestionar productos, clientes y pedidos. El objetivo es aprender a desplegar 
y escalar aplicaciones en la nube aplicando integración continua, contenedores y despliegue 
en un PaaS.

## Objetivos
- Construir un backend de microservicios que gestione productos, clientes y pedidos.
- Desplegar la aplicación usando contenedores Docker.
- Automatizar tests y despliegue mediante CI/CD en GitHub Actions.
- Publicar el servicio en un PaaS gratuito.

## Requisitos funcionales
- RF1: Crear, listar, actualizar y eliminar productos.
- RF2: Gestionar clientes.
- RF3: Crear y consultar pedidos.

## Requisitos no funcionales
- RNF1: Escalabilidad horizontal mediante contenedores.
- RNF2: Observabilidad básica (logs).
- RNF3: Tolerancia a fallos (varias réplicas).

## Tecnologías propuestas
- Backend: Python (FastAPI)
- Base de datos: MongoDB
- Contenedores: Docker
- Orquestación: Docker Compose (dev), Kubernetes (demo)
- CI/CD: GitHub Actions
- PaaS target: Render o Heroku

## Arquitectura inicial
- API Gateway (FastAPI) → Microservicios (productos, clientes, pedidos) → MongoDB
- Despliegue inicial con Docker Compose.

## Plan de hitos
- Hito 1: Definición del proyecto
- Hito 2: Integración continua
- Hito 3: Diseño de microservicios
- Hito 4: Composición de servicios
- Hito 5: Despliegue en PaaS

## Instrucciones (dev)
1. Clonar el repositorio
2. `docker compose up --build` (futuro, para ejecutar la app)
