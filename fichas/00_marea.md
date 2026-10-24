
# Marea · demostración guiada

**Pregunta:** ¿el crecimiento de facturación entre el primer semestre de 2025 y el de 2026 también produjo una mejora económica?

**Grano principal:** un movimiento de facturación por cliente, plan, región y fecha.

**Trabajo de clase:** recordar Power Query con transformaciones guiadas, conectar costos con las dimensiones compartidas, crear una tabla calendario desde cero, aplicar inteligencia de tiempo, definir medidas, analizar y construir una historia breve respaldada por el dashboard.

**Cuidado:** facturación no equivale a utilidad. Los costos están a un grano agregado y no deben sumarse después de una relación muchos a muchos ambigua.

## Consultas de demostración

- `Movimientos` y `NotasCredito`: combinar por `movimiento_id` mediante unión izquierda, expandir el monto y comprobar que no cambie la cantidad de movimientos.
- `Periodos`: reconocer `fecha_inicio`, que después se relacionará con la tabla calendario creada en DAX.
- `DemoMesesAnchos`: duplicar para comparar **Transponer** con **Anular dinamización de otras columnas**. La transformación útil para análisis es convertir enero, febrero y marzo en filas.
- `DemoVentasEnero` y `DemoVentasFebrero`: usar **Anexar consultas como nuevas** para obtener una tercera consulta con las seis filas. No anexar sobre una de las consultas de origen, porque produciría una referencia cíclica.

Las consultas `Demo...` son ejercicios de estructura y no forman parte del análisis de negocio de Marea.
