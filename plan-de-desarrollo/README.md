# Hono API - Learning Path: Backend & Infra

El objetivo de este proyecto es profundizar en el desarrollo backend y la gestión de infraestructura moderna. La elección de Hono.js se fundamenta en su compatibilidad nativa con diversos entornos de ejecución de JavaScript (lenguaje que ya conozco), permitiendo un despliegue versátil que abarca desde arquitecturas tradicionales conmo VPS, hasta soluciones de Edge Functions, servicios Serverless y contenedores. Esta portabilidad + el uso de arquitectura hexagonal asegura que la lógica de negocio permanezca desacoplada de la infraestructura de hosting, facilitando la escalabilidad y la migración entre proveedores de nube sin alteraciones en el código fuente."

## 🎯 Objetivos del Proyecto
* **Dominio de Web Standards en el Backend:** Implementar una API basada estrictamente en estándares de la Web (Fetch API), eliminando la dependencia histórica de librerías vinculadas exclusivamente a Node.js.
* **Abstracción de Infraestructura:** Validar el despliegue de una misma base de código en múltiples arquitecturas (Serverless, Containers y Edge) sin realizar refactorizaciones.
* **Optimización de Latencia:** Comprender y aplicar el concepto de *Edge Computing* para ejecutar lógica de negocio lo más cerca posible del usuario final.

## 🗺️ Roadmap de Metas
- [x] **Fase 0:** Consulta y planeación.
- [ ] **Fase 1:** Configuración del entorno Hono y manejo de rutas básicas.
- [ ] **Fase 2:** Implementación de Middleware (Logger, Auth, CORS).
- [ ] **Fase 3:** Integración con persistencia de datos (Database Layer).
- [ ] **Fase 4:** CI/CD y despliegue a entorno de producción en el Edge.
- [ ] **Fase 5:** CI/CD y despliegue a entorno de producción en VPS.
- [ ] **Fase 6:** Dockerización de la aplicación.
- [ ] **Fase 7:** Consulta de despliegue de contenedores y orquestación.
- [ ] **Fase 8:** CI/CD y despliegue de contenedor.