# Novapalma · Reglas del Agente y Memoria Persistente

## Memoria a Largo Plazo (Obsidian Vault)
* La documentación destilada, arquitectura técnica y bitácora de este proyecto residen en tu Segundo Cerebro:
  * Bitácora y estado actual: `/home/asher/Vault/Novapalma/Bitacora.md`
  * Visión general y stack: `/home/asher/Vault/Novapalma/Overview.md`
  * Grafo y lienzo visual de entidades: `/home/asher/Vault/Novapalma/Grafo/`
  * Documentación técnica local: `docs/`

## Directrices de Eficiencia de Tokens
1. **Consulta primero la bóveda:** Antes de inspeccionar archivos fuente o base de datos a ciegas, consulta `Overview.md` o `Bitacora.md` para entender el modelo de datos PERN y el estado actual. Esto ahorra hasta un 95% de tokens en cada sesión.
2. **Actualización de bitácora:** Al finalizar un cambio significativo o hito de desarrollo, actualiza la sección de sesiones recientes en `/home/asher/Vault/Novapalma/Bitacora.md`.

## Estilo de Desarrollo
* Mantener la integridad transaccional ACID en viajes y pesajes.
* Validación estricta con esquemas Zod en entradas y DTOs.
* Prisma v7 con `@prisma/adapter-pg` para operaciones sobre PostgreSQL.
