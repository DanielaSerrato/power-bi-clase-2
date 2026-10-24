# Actividad autónoma · Paso a paso

Elige uno de los cuatro sectores. El proyecto ya contiene datos limpios, relaciones y calendario. No abras Power Query ni cambies el modelo.

## 1. Abrir y formular la pregunta

1. Abre el `.pbip` desde la carpeta completa del caso.
2. Guarda una copia con tu nombre.
3. Lee la ficha y el diccionario.
4. En la vista Modelo identifica el hecho, las dimensiones y el calendario.
5. Completa: «Quiero saber ___ para que ___ pueda decidir ___».
6. Escribe el periodo actual, el periodo comparable y el límite principal de los datos.

## 2. Diseñar el mapa de medidas

1. Escribe cuatro resultados necesarios para responder la pregunta.
2. Para cada resultado define tabla/columna, operación, unidad y filtros esperados.
3. Clasifica como **base** la medida que agrega una columna.
4. Clasifica como **derivada** la medida que combina otras medidas.
5. Incluye al menos dos medidas base, una derivada y una proporción.

## 3. Construir y comprobar DAX

1. Ve a **Modelado → Nueva medida**.
2. Crea primero las medidas base con `SUM`, `COUNTROWS` o `DISTINCTCOUNT`.
3. Formatea cada resultado según su unidad.
4. Colócalo en una tarjeta o tabla temporal y comprueba un total.
5. Crea las derivadas reutilizando las medidas base.
6. Para la proporción, declara numerador y denominador y usa `DIVIDE`.
7. Prueba un filtro y verifica qué resultados deben cambiar según las relaciones.

## 4. Comparar periodos

1. Elige la medida que responde la pregunta principal.
2. Crea su valor del periodo anterior con la tabla calendario.
3. Calcula diferencia y variación cuando sean necesarias.
4. Comprueba actual y anterior en una tabla por año y mes.
5. Verifica que ambos periodos tengan la misma cobertura.

## 5. Diseñar la página

1. Escribe una pregunta para cada gráfico.
2. Elige el gráfico según la tarea: comparar, ver evolución o mostrar composición.
3. Construye con dimensión y medida.
4. Revisa orden, escala, unidad y título.
5. Organiza la página desde indicador general hasta desglose.
6. Añade solo filtros útiles y comprueba que toda la página responda.

## 6. Interpretar y revisar

1. Escribe dos hallazgos con cifra, comparación y alcance.
2. Separa evidencia de interpretación.
3. Propón una acción para considerar.
4. Declara una limitación y una siguiente pregunta.
5. Revisa con otra persona un total, un filtro, el denominador, los periodos, los gráficos y la fuerza de las afirmaciones.
6. Ensaya en 90 segundos: situación → pregunta → hallazgo → evidencia → interpretación → límite → siguiente paso.
