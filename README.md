# 🚀 Hono Multi-Runtime API

Una API moderna, ultraligera y de alto rendimiento construida con **Hono.js**, diseñada para ejecutarse en cualquier runtime de JavaScript (Node.js, Bun, Cloudflare Workers, Deno) bajo una **Arquitectura Hexagonal**.

[![Hono](https://img.shields.io/badge/Framework-Hono.js-orange?style=flat-square&logo=hono)](https://hono.dev/)
[![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

## 📖 Descripción

Este proyecto es una implementación de referencia para construir servicios backend que priorizan los **Web Standards**. Gracias a la abstracción de Hono, el mismo código fuente puede ser desplegado sin cambios en infraestructuras distribuidas (Edge), contenedores (Docker) o servidores tradicionales (VPS).

El desarrollo sigue los principios de la **Arquitectura Hexagonal (Puertos y Adaptadores)**, asegurando que la lógica de negocio permanezca desacoplada de los detalles técnicos de la infraestructura.

## ✨ Características Principales

*   **Zero Dependencies (Core):** Basado en estándares de la Web (Fetch API).
*   **Multi-Runtime:** Soporte nativo para Node.js, Bun, Deno y Edge Functions.
*   **Hexagonal Architecture:** Lógica de negocio aislada y testeable.
*   **Type Safety:** Tipado estricto con TypeScript.

## 🛠️ Tech Stack

- **Framework:** [Hono.js](https://hono.dev/)
- **Runtime:** Node.js / Bun


## 🏗️ Estructura del Proyecto

```text
app/
├── domain/         # Lógica de negocio pura (Entidades, Casos de Uso)
├── application/    # Puertos (Interfaces) y servicios de aplicación
└── infrastructure/ # Adaptadores (DB, External APIs, Framework)
```

## 🚀 Inicio Rápido

### Requisitos Previos

- Node.js (v20+) o Bun
- Docker (opcional para desarrollo local)

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/andresmon2490/api.git

# Instalar dependencias
npm install
```

### Desarrollo

```bash
# Iniciar servidor de desarrollo
npm run dev
```

## 🗺️ Hoja de Ruta

El plan de desarrollo detallado se encuentra en el directorio de planeación:

- [Estrategia Técnica y Roadmap](plan-de-desarrollo/estrategia.md)
- [Seguimiento de Metas](plan-de-desarrollo/README.md)

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
