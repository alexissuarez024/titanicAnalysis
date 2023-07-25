# PySpark para el análisis y modelado de datos

Este es un trabajo de procesamiento y modelado de datos con PySpark.     
Trabajé con un set de datos sobre los pasajeros del Titanic en donde analicé en qué condiciones estaban los datos, para posteriormente generar distintas transformaciónes y establecer el archivo principal como el 'origen' desde donde se iban a ramificar las distintas etapas del modelado.

Luego proyecté y generé con el set de origen, un modelo tipo 'estrella', formando las distintas 'dimensiones' y la tabla de 'fact' en la que posteriormente se realizarian los análisis.

En la etapa final de analisis utilice la herramienta de visualización **Power BI** para realizar los distintos gráficos.

### Aclaración
Cambie la variable 'path' en donde se encuentre el archivo de origen 'pasajeros_titanic.csv' para poder tener los mismos resultados.
Solo tome la variable pathNotebook ya que se trabajo con ella. Si desea cambiarla recuerde cambiarla a lo largo del proyecto.

```python
pathNotebook = 'yourPath/'
archivo_1 = 'pasajeros_titanic.csv'
```

