
# Marea · demostración guiada

**Pregunta:** ¿el crecimiento de facturación entre el primer semestre de 2025 y el de 2026 también produjo una mejora económica?

**Grano principal:** un movimiento de facturación por cliente, plan, región y fecha.

**Trabajo de clase:** auditar Power Query, ampliar el modelo con el puente de periodo–plan–región y costos, crear calendario, definir medidas, analizar y diseñar una historia de tres actos.

**Cuidado:** facturación no equivale a utilidad. Los costos están a un grano agregado y no deben sumarse después de una relación muchos a muchos ambigua.

## Consultas de demostración

- `DemoMesesAnchos`: duplicar para comparar **Transponer** con **Anular dinamización de otras columnas**. La transformación útil para análisis es convertir enero, febrero y marzo en filas.
- `DemoVentasEnero` y `DemoVentasFebrero`: usar **Anexar consultas como nueva** para obtener una sola tabla de movimientos con la misma estructura.

Estas tablas son ejercicios de Power Query y no forman parte del análisis de negocio de Marea.
