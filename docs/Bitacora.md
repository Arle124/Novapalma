# Novapalma · Bitácora de Desarrollo

* **Estado del Proyecto:** Operativo con base PERN y Docker Compose
* **Última revisión:** Septiembre 2026

---

## Componentes y Arquitectura

* **Servidor (`/server`):**
  * Express con rutas modularizadas para viajes, vehículos, conductores y tarifas.
  * Modelado relacional en Prisma (`prisma/schema.prisma`).
* **Cliente (`/client`):**
  * Panel administrativo y vistas de operador en React + Vite.
* **Documentación Técnica Local:**
  * Diccionario de datos: `Novapalma/docs/DATA_DICTIONARY.md`
  * Métodos y clases: `Novapalma/docs/METODOS_Y_CLASES.md`
  * Guía de pruebas: `Novapalma/docs/TESTING_GUIDE.md`

---

## Tareas y Próximos Pasos

- [ ] Revisión de migraciones Prisma y pools de conexión con `@prisma/adapter-pg`.
- [ ] Optimización de filtros en reportes financieros por rango de fechas y conductores.
- [ ] Mantenimiento de suites E2E con Selenium WebDriver.
