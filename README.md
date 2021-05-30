# Workshop - Caso de análisis: Pandemia   <img src="https://img.icons8.com/dusk/48/000000/coronavirus.png"/>
##  Introducción al caso: 
### La crisis del COVID19 representa uno de los fenómenos más importantes de gestión orientada a datos de la historia ya que demuestra el uso intensivo del Business Analytics como marco de trabajo para la gestión de metas en un mundo globalizado y digital.

## Data Analytics Workflow <img src="https://img.icons8.com/clouds/78/000000/workflow.png"/>
## <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> 1- Definición de preguntas <img src="https://img.icons8.com/ios/30/000000/question-mark--v2.png"/>
### ¿En general dónde impacto más la pandemia?
### ¿A qué países les fue mejor y peor?
### ¿Qué impacto tuvieron las políticas de confinamiento social?
### ¿Hay diferencias entre países ricos y pobres?
‎      ‏‏‎
## <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> 2- Exploración de fuentes <img src="https://img.icons8.com/officel/36/000000/grid-3.png"/>
### Una de las partes más importantes de cualquier proceso de Business Analytics es la exploración preliminar de las fuentes de datos.
### Fuente principal: https://ourworldindata.org/coronavirus-source-data
### Datos: [owid-covid-data.xlsx](https://github.com/agustinrp/2_Workshop-BI/files/6565460/owid-covid-data.xlsx)
### Campos: [owid-covid-codebook.xlsx](https://github.com/agustinrp/2_Workshop-BI/files/6565459/owid-covid-codebook.xlsx)
‎      ‏‏‎
## <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> 3- Identificación de variables <img src="https://img.icons8.com/ios/28/000000/variable.png"/>
### - País
### - Población
### - Continente
### - Contagios
### - Muertes
### - Tasa de mortalidad
### - Confinamiento
### - PBI
‎      ‏‏‎
## <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> 4- Estrategias de análisis <img src="https://img.icons8.com/dusk/40/000000/strategy-board.png"/>  
### Para responder a las preguntas definidas, vamos a usar las variables identificadas.
### En el caso de la primer pregunta: ¿En general dónde impacto más la pandemia? 
### Vamos a utilizar una métrica absoluta (Muertes).
‎      ‏‏‎
### Para la segunda pregunta: ¿A qué países les fue mejor y peor? 
### Necesitamos una métrica de proporción (Mortalidad) y una medida de referencia (Media) para poder tener un valor que nos permita agrupar los países, por un lado los mejores y por el otro los peores.
‎      ‏‏‎
## <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> 5- Estructura de información <img src="https://img.icons8.com/material-two-tone/36/000000/data-configuration--v1.png"/>
### Ya sabemos cuáles son nuestras fuentes de datos, ahora debemos ver cómo están estructurados los datos para ver y entender cómo vamos a crear las métricas necesarias. 

### Para llevar a cabo esta actividad, es necesario realizar un proceso ETL para dejar los datos preparados su posterior análisis. Cuando se transforman los datos en el proceso ETL, estos se convierten en información ya que no dejan de ser los datos ''en bruto'' para convertirse información valiosa.

‎      ‏‏‎
## <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> 6- Análisis exploratorio <img src="https://img.icons8.com/color/50/000000/export-collections.png"/>
### Cuando ya tenemos la información estructurada de la manera que consideramos óptima, comenzamos con el análisis exploratorio.
### Este análisis consiste en la verificación de la información, donde nos haremos preguntas para verificar y explorar la granularidad de la misma: 
### - Análisis de distribución: deberían estar todos los elementos en nuestro análisis?
### - Consistencia:hay variables poco consistentes como nulos,faltantes,no-confiables?
### - Máximos y Mínimos: que hay en los extremos de nuestra población?
### - Outliers: se ven elementos demasiado exagerados respecto al resto? Por qué?
‎      ‏‏‎
## Trabajo presentado
### Respondiendo las preguntas iniciales, incluyendo las variables identificadas y utilizando las métricas mejor consideradas:

## Herramienta de visualización: Power BI  <img src="https://img.icons8.com/dusk/36/000000/power-bi.png"/>
https://powerbi.microsoft.com/es-es/desktop/
