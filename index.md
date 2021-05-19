# PEC 3: Visualización interactiva

#### @Author
    Adonis González Godoy
    
## 1. Descripción de los datos seleccionados

Los dataset seleccionados para esta pec son los siguientes:

 - Data on the daily number of new reported COVID-19 cases and deaths by EU/EEA country
 - Data on COVID-19 vaccination in the EU/EEA

Los datos han sido descargados desde la página oficina European Centre for Disease Prevention and Control. Los datos son públicos siempre que se reconozca al CEPCE como la fuente original del material. La última fecha registrada de actualización de los datos fue el día 13 de Mayo del 2021.

### 1.1 Los datos

- [Datasets](https://github.com/adions025/visualizacion_interactiva/blob/gh-pages/data){:target="_blank"}

## 2. Exploración de los datos 

El primer contacto con el dataset ha sido realizado usando Jupyter Notebook en un conda enviroment que ejecuta la versión 3.6 de Python. 
Algunas de las librerías que se han usado son: Padas, Numpy, Matplotlib.

- [Exploración formato (web)](https://adions025.github.io/visualizacion_interactiva/PEC3_adonis_gonzalez.html){:target="_blank"}

- [Github - Jupyter Notebook](https://github.com/adions025/visualizacion_interactiva/blob/gh-pages/src/PEC3_adonis_gonzalez.ipynb){:target="_blank"}

- [Download - Jupyter Notebook](src/PEC3_adonis_gonzalez.ipynb)

## 3. Mockup

El mockup ha sido realizado usando la herramienta Figma Charts. Esta herramienta Contiene los patrones de visualización de 
datos más comunes, desde simples gráficos de barras hasta heatmaps.

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FNuArSJOAu8aoMDVxHIGkx5%2FFigma-Charts-Infographics-UI-kit-Community%3Fnode-id%3D1253%253A275193" allowfullscreen></iframe>

- [Mockup (web)](https://adions025.github.io/visualizacion_interactiva/mockup_vaccination.html){:target="_blank"}

## 4. Visualisations

Después del primer contacto con el dataset se intentará responder a las siguientes preguntas:

¿Qué países de la unión europea han administrado más vacunas? 
¿Qué tipo de vacunas se han administrados más y en que países? 
¿En qué semanas se han administrado más dosis (primera dosis, segunda y toral) de vacunas durante el 2021?
¿En qué países se ha registrado más casos de COVID?
¿En qué países se ha registrado más muerte por COVID?

#### Data on COVID-19 vaccination in the EU/EEA

- [Flourish - Vaccination](https://adions025.github.io/visualizacion_interactiva/flourish_vaccination.html){:target="_blank"}
- [Tableu public](https://public.tableau.com/profile/adonis.gonz.lez#!/vizhome/DataonCOVID-19vaccinationintheEUEEA/Dashboard1?publish=yes){:target="_blank"}

#### Data on the daily number of new reported COVID-19 cases and deaths by EU/EEA country

- [Flourish - Daily reported](https://adions025.github.io/visualizacion_interactiva/flourish_daily_reported.html){:target="_blank"}
- [RawGraphs - Daily reported](https://adions025.github.io/visualizacion_interactiva/rawgraphs_reported.html){:target="_blank"}

## 5. Conclusiones

### 5.1 Conclusiones de las visualizaciones

- Alemania es el país que se ha administrado más la segunda dosis.
- Alemania, Italia y España son los países que más vacunas han administrado.
- Se puede observar que en la semana número 17 del 2021 fue cuando se administró más dosis.
- Las vacunas más administradas en Europa son:
    - CN = BBIBV-CorV –CNBG
    - SPU = Sputnik V -Gamaleya 
    - COM = Comirnaty –Pfizer/BioNTech
- Los países con más casos reportados son Francia, Italia, Alemania y España.
- Los países con más muertes reportadas por COVID son:
    - Italia
    - Francia
    - Alemania
    - España
    - Polonia
- En el mes de febrero se ha reportados más casos y más muertes por COVID.

### 5.2 Herramientas

La herramienta Flourish nos permite generar gráficos fácilmente en línea en su versión gratuita ya que incluye datos de
ejemplo por lo que la curva de aprendizaje es muy rápida. Unas de las principales ventajas de esta herramienta es que se 
puede generar el código JavaScript embeber para adaptarlo en una página web con tan solo un solo clic.

También permite crear historias, estilo de presentaciones de visualizaciones. Además de permitir mantener la 
visualización en sus servidores y poder compartirla a través de un enlace, pero en su versión gratuita serían publicas 
estas visualizaciones.

Por otro lado, con esta herramienta parece un poco más complicado generar visualizaciones de geográficos sin tener los 
datos geométricos, si comparamos con Tableau, permite transformar datos de nombre de países o códigos a función 
geográfica expresar datos visualmente al transformar acciones de arrastrar y soltar en consultas de dados, en una 
interfaz intuitiva, puede permitir incluso aprendizaje automático, estadísticos, lenguaje natural y preparación de 
los datos inteligentes para que sean más eficaces y permitan aumentar la creatividad de las personas que lo utilizan 
para hacer análisis. En otras palabras, con Flourish no se permite transformaciones de los datos, los datos deben están 
en su formato para utilizarse.

RawGraph también nos permite crear visualizaciones, es una herramienta online basada en vectores sobre la biblioteca 
d3.js. También se puede instalar en local, pero para esta actividad solo se ha usado el modo online y este permite 
solo generar visualizaciones estáticas para ser descargadas en formato imagen.



### Author 

Adonis González Godoy