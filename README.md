# <h1 align=center>**`Proyecto Individual - Data Analytics`**</h1>

### Tópicos 

- [Descripción del Proyecto](#descripcion-del-proyecto)

- [Fases](#fases)

- [KPI's](#kpis)

- [Herramientas Utilizadas](#herramientas-utilizadas)

- [Conclusiones](#conclusiones)

- [Fuentes de Datos](#fuentes-de-datos)

<hr>

## Descripción del Proyecto

<p align="justify">
El objetivo del proyecto fue analizar, indagar y sacar conclusiones a partir de los datos de situación del sector de telecomunicaciones en Argentina, específicamente de las conexiones a Internet. Los datasets fueron adquiridos del sitio web del Ente Nacional de Comunicaciones (ENACOM), el cual es un ente público de Argentina. Cabe destacar que se realizó un análisis a Nivel Nacional y por Provincias.

Es importante acotar, que para este proyecto solamente utilizamos los datos correspondientes a los años 2018, 2019, 2020, 2021 y 2022.
</p>

<hr>

## Fases

1 - `Obtención de los datasets:` Se realizó un estudio detallado de todos los datasets que tenían relación con el servicio de internet, el cual es nuestro caso de estudio, y se tomaron aquellos que se consideraron relevantes: Velocidades, Tecnologías, Medias de Bajadas y penetración por Hogares y Habitantes. En total se utilizaron 8 datasets.

2 - `Unión y limpieza de datos - ETL:` Se realizó una segmentación de la información, pudiendo generar dos datasets, es decir, uno correspondiente a los datos a Nivel Nacional y otro dataset a Nivel de Provincias. En esta fase se realizaron uniones de datasets, así como también formateo de campos y nombres de las variables.

3 - `Análisis Exploratorio de Datos - EDA:` Se realizó una análisis de los dos datasets que se generaron en la fase anterior: dataset_nacional.csv y dataset_provincias.csv. El EDA consistió en análisis univariados, incluyendo la visualización de las principales estadísticas descriptivas de las variables numéricas, boxplots, barplots y mapas. El análisis bivariado del EDA incluyó la generación de un mapa de calor y barplots entre las variables más importantes y relevantes.

4 - `Dashboard:` Se elaboró utilizando Power BI, una herramienta de análisis y visualización de datos de Microsoft. Se desarrollaron medidas, columnas y tablas específicas para cada KPI, en función de su complejidad. Para cada KPI se generó un informe completo que presenta los gráficos más relevantes, variables destacadas, tarjetas informativas. 

<hr>

## KPI's

- KPI 1 - Penetración de Internet: Este KPI mide el porcentaje de personas o hogares en una determinada población que tienen acceso a Internet. Objetivo de crecimiento 2% anual.

- KPI 2 - Ingresos Totales: Este KPI mide el total de ingresos generados. Se calcula determinando el período de tiempo para el cual deseas calcular el KPI de ingresos totales, en nuestro caso es anual. Objetivo de crecimiento: 5% anual.

- KPI 3 - Velocidad de conexión: Este KPI analiza la velocidad promedio de conexión a Internet. Una mejora en este indicador implica un aumento en la calidad y capacidad de los accesos a Internet. Objetivo de crecimiento: 5% anual.

<hr>

## Herramientas Utilizadas

 <a href="https://matplotlib.org/" target="_blank"> <img src="https://matplotlib.org/stable/_static/images/logo2.svg" alt="matplotlib" width="100" height="100"/> </a> <a href="https://seaborn.pydata.org/" target="_blank"> <img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" alt="seaborn" width="100" height="100"/> </a> 
 
 <a href="https://plotly.com/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/Plotly-logo.png/220px-Plotly-logo.png" alt="plotly" width="150" height="40"/> </a> <a href="https://numpy.org/" target="_blank"> <img src="https://numpy.org/images/logo.svg" alt="Numpy" width="60" height="60"/> </a>  <a href="https://powerbi.microsoft.com//" target="_blank"> <img src="https://1000marcas.net/wp-content/uploads/2022/08/Microsoft-Power-BI-Logo-500x281.png" alt="PB" width="70" height="50"/> </a>  <a href="https://pandas.pydata.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/512px-Pandas_logo.svg.png" alt="Pandas" width="100" height="50"/> </a>

###

<hr>

## Conclusiones

- El año 2019 fue el que tuvo mayores cambios debido al tema pandemia. El acceso a internet independientemente del tipo de velocidad tuvo una mayor demanda ya que por motivos académicos y laborales, fue un recurso necesario.

- Entre los años 2018 y 2019 la velocidad entre 1 Mbps hasta 6 Mbps tuvo mayor demanda por los usuarios. Pero a partir del 2018 se puede observar una gran disminución de la cantidad de accesos para este segmento.

- La velocidad de más de 30 Mbps tuvo una demanda exponencial el año 2019, la cual no ha parado, esto se debe a la situación Pandemia, la cual cambió la dinámica laboral y académica, donde los usuarios requieren mayor velocidad y estabilidad en sus conexiones.

- La demanda de la tecnología ADSL ha venido decreciendo desde el año 2018, esto se debe a que en la actualizad existen otras opciones que brindan accesos con mayor velocidad y estabilidad.

- La tecnología de Fibra óptica ha venido en un aumento importante desde el año 2019, este incremento se debe a la situación Pandemia que vivimos, impactando en el teletrabajo, por lo cual necesitamos mejor conectividad para llevar a cabo nuestras tareas profesionales y académicas, impactando positivamente en la demanda del servicio.

- La tecnología Cable Modem ha sido la tecnología con mayor demanda de conexiones a lo largo de los años.

- El incremento de los ingresos por Prestación de Servicio de Internet Fijo ha sido constante a lo largo de los años, esto se debe al aumento del trabajo remoto, la educación en línea y el mayor consumo de contenido digital.

- La velocidad media de bajada en Mbps, ha ido incrementado exponencialmente con el correr de los años.

- Desde los últimos 5 años desde el 2018 este valor se incrementó notablemente, obteniendo valores máximos.

- La tasa de penetración por cada 100 hogares es de aproximadamente el 77%. Es importante acotar que este valor puede variar dependiendo de la ubicación geográfica, el nivel socioeconómico y la infraestructura de conexión a Internet en cada área.

- La tasa de penetración por cada 100 habitantes es de aproximadamente el 24%. Es importante acotar que este valor puede variar dependiendo de la ubicación geográfica, el nivel socioeconómico y la infraestructura de conexión a Internet en cada área.

- Se pudo visualizar que Capital Federal refleja la mayor proporción de accesos por cada 100 Hogares. Siendo el caso contrario para la Provincia de Santa Cruz, Formosa y Chaco, cabe destacar que estas provincias se encuentran muy alejadas.

- Se pudo visualizar que Capital Federal refleja la mayor proporción de la Media de Bajada en Mbps. Siendo el caso contrario para la Provincia de Santa Cruz, Tierra del Fuego y Chubut, cabe destacar que estas provincias se encuentran muy alejadas.

- Aquellas Provincias donde la actividad económica y el turismo es alto, existen mayor demanda de accesos a internet de velocidades altas.

- La Provincia de Tierra del Fuego es la que menos tiene accesos a velocidades entre 512 Kbps y mas de 30 Mbps, pero se puede observar que posee accesos a otras velocidades.

<hr>

## Fuentes de Datos

ENACOM - Ente Nacional de Comunicaciones. [Ir a sitio web](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/)

INDEC - Instituto Nacional de Estadística y Censos - Republica Argentina. [Ir a sitio web](https://www.indec.gob.ar/indec/web/Institucional-Indec-BasesDeDatos-3)

<hr>

