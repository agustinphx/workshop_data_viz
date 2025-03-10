# Pandemia   <img src="https://img.icons8.com/dusk/48/000000/coronavirus.png"/>
###  Introducción
La crisis del COVID19 representa uno de los fenómenos más importantes de gestión orientada a datos de la historia ya que demuestra el uso intensivo del Business Analytics como marco de trabajo para la gestión de metas en un mundo globalizado y digital.

## Data Analytics Workflow <img src="https://img.icons8.com/clouds/78/000000/workflow.png"/>
### 1- Definición de preguntas <img src="https://img.icons8.com/ios/30/000000/question-mark--v2.png"/>
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> ¿En qué continente impacto más la pandemia?
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> ¿A qué países les fue mejor y peor?
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> ¿Qué impacto tuvieron las políticas de confinamiento social?
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> ¿Qué relación hay entre la mortalidad y la expectativa de vida ?
‎      ‏‏‎
### 2- Exploración de fuentes <img src="https://img.icons8.com/officel/36/000000/grid-3.png"/>
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Una de las partes más importantes de cualquier proceso de Business Analytics es la exploración preliminar de las fuentes de datos. En este caso usaremos los datos hasta Octubre del 2020.
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Fuente principal: https://ourworldindata.org/coronavirus-source-data
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Datos: [owid-covid-data.xlsx](https://github.com/agustinrp/2_Workshop-BI/files/6565460/owid-covid-data.xlsx)
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Campos: [owid-covid-codebook.xlsx](https://github.com/agustinrp/2_Workshop-BI/files/6565459/owid-covid-codebook.xlsx)
‎      ‏‏‎
### 3- Identificación de variables <img src="https://img.icons8.com/ios/28/000000/variable.png"/>
####  <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/>  País
####  <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/>  Población
####  <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/>  Continente
####  <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/>  Contagios
####  <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/>  Muertes
####  <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/>  Tasa de mortalidad
####  <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/>  Confinamiento
####  <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/>  PBI
‎      ‏‏‎
### 4- Estrategias de análisis <img src="https://img.icons8.com/dusk/40/000000/strategy-board.png"/>  
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Para responder a las preguntas definidas, vamos a usar las variables identificadas.
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> En el caso de la primer pregunta: ¿En general dónde impacto más la pandemia? 
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Vamos a utilizar una métrica absoluta (Muertes).
‎      ‏‏‎
#### Para la segunda pregunta: ¿A qué países les fue mejor y peor? 
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Necesitamos una métrica de proporción (Mortalidad) y una medida de referencia (Media) para poder tener un valor que nos permita agrupar los países, por un lado los mejores y por el otro los peores.
‎      ‏‏‎
### 5- Estructura de información <img src="https://img.icons8.com/material-two-tone/36/000000/data-configuration--v1.png"/>
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Ya sabemos cuáles son nuestras fuentes de datos, ahora debemos ver cómo están estructurados los datos para ver y entender cómo vamos a crear las métricas necesarias. 

#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Para llevar a cabo esta actividad, es necesario realizar un proceso ETL para dejar los datos preparados su posterior análisis. Cuando se transforman los datos en el proceso ETL, estos se convierten en información ya que no dejan de ser los datos ''en bruto'' para convertirse información valiosa.

‎      ‏‏‎
### 6- Análisis exploratorio <img src="https://img.icons8.com/color/50/000000/export-collections.png"/>
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Cuando ya tenemos la información estructurada de la manera que consideramos óptima, comenzamos con el análisis exploratorio.
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Este análisis consiste en la verificación de la información, donde nos haremos preguntas para verificar y explorar la granularidad de la misma: 
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Análisis de distribución: deberían estar todos los elementos en nuestro análisis?
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Consistencia:hay variables poco consistentes como nulos,faltantes,no-confiables?
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Máximos y Mínimos: que hay en los extremos de nuestra población?
#### <img src="https://img.icons8.com/plumpy/15/000000/sphere.png"/> Outliers: se ven elementos demasiado exagerados respecto al resto? Por qué?
‎      ‏‏‎
## Trabajo presentado <img src="https://img.icons8.com/color/50/000000/business-report.png"/>
### Mejor desempeño:
![Best](https://user-images.githubusercontent.com/58674979/120110041-6f0c2000-c142-11eb-905e-adc18ef729c3.png)

‎      ‏‏‎
### Peor desempeño:
![Worst](https://user-images.githubusercontent.com/58674979/120110050-7a5f4b80-c142-11eb-80ce-4c87f146830e.png)
‎      ‏‏‎
## Herramienta de visualización: Power BI  <img src="https://img.icons8.com/dusk/36/000000/power-bi.png"/>
https://powerbi.microsoft.com/es-es/desktop/
