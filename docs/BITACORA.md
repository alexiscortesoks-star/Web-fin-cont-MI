# Bitácora Técnica y de Producto — Web-fin-cont-MI

## 1. Visión del Proyecto
* **Objetivo Etapa 1 (Actual):** Web institucional de presentación para servicios de Contabilidad y Asesoramiento Financiero, con herramientas interactivas en cliente (calculadoras/simuladores) y captación de consultas.
* **Objetivo Etapa 2 (Futuro):** Escalar hacia una aplicación web con portal de clientes autenticado y backend en Python para carga de datos y análisis financiero automatizado.

## 2. Arquitectura y Decisiones Técnicas (ADR)
* **Estructura Monorepo (`frontend/`, `backend/`, `docs/`):** Permite mantener sincronizados la interfaz y el futuro servidor bajo un mismo repositorio Git.
* **Frontend:** React + Vite + Tailwind CSS + Lucide Icons. Preparado con carpeta `/services` para desacoplar la lógica de llamadas a API.
* **Backend (Reservado Etapa 2):** Python + FastAPI + Pandas (prototipado inicial con SQLite, migración futura a PostgreSQL/Supabase).
* **Despliegue Etapa 1:** GitHub -> Vercel (Root Directory: `frontend`).

## 3. Reglas de Negocio y Fórmulas Financieras
*(Documentar aquí cada fórmula acordada con la contadora antes de programarla en JS o Python)*
* **Calculadora 1 (A definir):** ...

## 4. Registro de Avances
### [2026-11-19] — Inicialización del proyecto
* **Hecho:** Creación de carpeta `Web-fin-cont-MI`, inicialización de Git, estructura base (`docs`, `frontend`, `backend`) y bitácora.
* **Próximo paso:** Primer commit, subida a GitHub, conexión con Vercel y armado de la estructura visual de la Landing Page.
* **Pendiente con la socia/contadora:** Definir paleta de colores preferida, nombre comercial/marca, servicios exactos y primera calculadora interactiva.