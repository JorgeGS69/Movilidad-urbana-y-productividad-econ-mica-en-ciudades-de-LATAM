# Movilidad-urbana-y-productividad-econ-mica-en-ciudades-de-LATAM
Proyecto 5_ Movilidad urbana y productividad económica en ciudades de LATAM - TripleTen_files
Contexto & objetivo:

Responde la pregunta central del análisis: ¿qué relación existe entre la movilidad urbana (congestión, tiempos de viaje) y la productividad económica (PIB per cápita)?
En base a los datos ya las graficas podemos notar que no contamos con una relacion clara o logica que nos pudira establecer una relacion en os resultados de los tiempos de viaje Vs la productividade economiva
Explica brevemente las variables clave utilizadas y su relevancia para la toma de decisiones.
Las variables utilizadas en este analisis fueron jams_delay y city_gdp_capita.
jams_delay es una metrica tomada por TomTom que nos indica el teimpo que estamos en el trafico de la ciudad.
city_gdp_capita es el producto interno bruto por habitante de la ciudad nos podra ayudar a saber los presupuestos o flujo que tiene la ciudad para infraestructura vial en este analisis.
Cobertura de datos:

Analizamos el año 2024 para 7 paises y 15 ciudades
Metodología (alto nivel):

Describe los procesos principales: limpieza de datos (formatos, estandarización de columnas).
Primero. ''Explorar la estructura y tipos de datos' Identificar columnas con tipos incorrectos, distribución y nulos, anotar las columnas que requieren conversión.
Segundo. 'Renombrar columnas', Asegurar que las columnas de fechas y valores numéricos estén en formatos correctos para permitir análisis, cálculos y comparaciones precisas.
Tercero. 'Corregir formatos numéricos y de fecha', Asegurar que las columnas de fechas y valores numéricos estén en formatos correctos para permitir análisis, cálculos y comparaciones precisas.
Explica la agregación por ciudad–año y el uso de una unión INNER para integrar tráfico y economía.
Primero. 'Extraer año y filtrar', Identificar el año de cada registro y mantener solo los registros del 2024.
Segundo. 'Unir movilidad y economía', Combinar la información de tráfico y economía en un solo DataFrame para analizar cómo las condiciones económicas se relacionan con la movilidad urbana.
Menciona las validaciones visuales empleadas (distribuciones, outliers, tendencias generales).
'Visualizar relaciones entre economía y tráfic', Analizar visualmente la distribución y la relación entre indicadores de tráfico y economía en 2024, para identificar posibles patrones o tendencias generales entre ambas variables.
Primero. 'Boxplot', Visualiza la distribución del tráfico. Podemos notar que tenemos algunos datos que se salen de lo normal (outliers) la mediana esta muy por abajo de estos valores hay que revisar estas mediciones.
Segundo. 'Histograma', Visualiza la distribución de la economía. La distribucion tenemos que la mayotia esta abajho aunque tenemos algunas ciudades con valores altos.
Tercero. 'Gráfico de barras', Compara ambas variables. En la relacion de nuestros datos tiempos de viaje Vs la productividade economiva, podemos notar que estan disparados algunas ciudades.
Hallazgos iniciales:

Resume los patrones más importantes entre índices de tráfico y PIB per cápita.
Podemos notar que el PIB realmente no teine relacion con los indices de trafico, ni tampoco tiene que ver con la cantidad de personas que viven en la ciudad.
Destaca anomalías u outliers que podrían requerir revisión adicional o un análisis más profundo.
Hay que revisar los outliers en nuestra informacion y que los datos son extermos y se modifican los resultados. Por ejemplo Montevideo tiene un PIB muy alto con el menor trafico de todo el estucio con lo cual salimos de parametros.
Recomendaciones
Aterriza los hallazgos en acciones: ciudades prioritarias, necesidad de validar fuentes, requerimiento de análisis adicionales, o propuestas de inversión.

¿Qué ciudad : Bogotá, Lima o Buenos Aires o alguna otra en particular, muestra la mayor correlación significativa entre altos niveles de congestión vehicular y bajos indicadores de productividad económica, sugiriendo ser una ciudad prioritaria para inversión en infraestructura de transporte?
Santiago presenta un gran problema de conjestionamiento vial y bajo su PIB lo cual nos invita a invertir en infraestructura de trasporte. Mexico presenta la mejor oportunidad para invertir en infraestructura y que el PIB es el segundo mas alto con mucha complejidad en congestionamiento vial, buscando nuevas soluciones para mejorar la problematica de trafico. Montevideo presenta el PIB mas alto de toso con la menor tasa de congestionamiento vehicular si los datos son reales podemos buscar el creciemiendo del parque vehicular para invertir en el mercado de coches.
