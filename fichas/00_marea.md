
# Marea · demostración guiada

**Pregunta:** ¿el crecimiento de facturación entre el primer semestre de 2025 y el de 2026 también produjo una mejora económica?

**Grano principal:** un movimiento de facturación por cliente, plan, región y fecha.

**Trabajo de clase:** recordar Power Query con transformaciones guiadas, ampliar el modelo con el puente de periodo–plan–región y costos, crear una tabla calendario, aplicar inteligencia de tiempo, definir medidas, analizar y construir una historia breve respaldada por el dashboard.

**Cuidado:** facturación no equivale a utilidad. Los costos están a un grano agregado y no deben sumarse después de una relación muchos a muchos ambigua.

## Consultas de demostración

- `Movimientos` y `NotasCredito`: combinar por `movimiento_id` mediante unión izquierda, expandir el monto y comprobar que no cambie la cantidad de movimientos.
- `PuentePeriodoPlanRegion`: crear `fecha_inicio` a partir de año y mes para relacionar la tabla calendario.
- `DemoMesesAnchos`: duplicar para comparar **Transponer** con **Anular dinamización de otras columnas**. La transformación útil para análisis es convertir enero, febrero y marzo en filas.
- `DemoVentasEnero` y `DemoVentasFebrero`: usar **Anexar consultas como nueva** para obtener una sola tabla de movimientos con la misma estructura.

Las consultas `Demo...` son ejercicios de estructura y no forman parte del análisis de negocio de Marea.
