
# Power BI · Clase 2: del dato a la historia

Material de clase para practicar el recorrido completo desde una pregunta de negocio hasta una historia visual en Power BI.

## Qué contiene

- `proyectos/00_marea`: demostración guiada. Conserva el modelo de la clase anterior, agrega `CostosServicio` y deja abiertas tareas breves para combinar, transponer, anular dinamización/pivotar y anexar. No incluye tabla calendario ni medidas: la tabla calendario se crea desde cero durante la clase.
- `proyectos/01_ropa`: reto de ventas de una cadena de moda.
- `proyectos/02_musica`: reto de eventos y ocupación.
- `proyectos/03_logistica`: reto de entregas y cumplimiento.
- `proyectos/04_atencion`: reto de solicitudes y SLA.
- `datos`: archivos CSV sintéticos usados por los proyectos.
- `fichas`: pregunta, grano, campos y reglas de cada caso.
- `fichas/ACTIVIDAD_PASO_A_PASO.md`: secuencia común para desarrollar y revisar cualquiera de los cuatro retos.
- `temas`: cinco temas JSON importables. Son un punto de partida; no reemplazan las decisiones de jerarquía visual y storytelling.

Los cuatro retos tienen datos limpios, calendario y relaciones preparadas. No tienen medidas DAX ni visualizaciones: esas decisiones corresponden al equipo.

## Cómo abrir un proyecto

1. Descarga el repositorio completo con **Code → Download ZIP** o clónalo con Git.
2. Abre el archivo `.pbip` dentro de la carpeta del caso.
3. Si Power BI solicita credenciales para `raw.githubusercontent.com`, elige **Anónimo** y aplica el permiso al dominio.
4. Actualiza el modelo.

No copies únicamente el archivo `.pbip`: necesita las carpetas `.Report` y `.SemanticModel` que están a su lado.

Los datos quedan publicados en GitHub y las consultas usan una URL fija de la versión `clase2-v3`. Esto hace reproducible la clase.

## Tamaño de los casos

| Caso | Filas de la tabla de hechos |
|---|---:|
| Ropa | 7,179 |
| Música | 264 |
| Logística | 4,992 |
| Atención | 3,510 |

Todos los nombres y datos son ficticios y fueron creados con fines educativos.
