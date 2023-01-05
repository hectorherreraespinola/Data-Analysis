# **PROYECTO INDIVIDUAL Nº3**
# **Autor: Hector Javier Herrera Espínola**


**Fecha : 3/01/2023**



# <h1 align="center">**` TEMA: Telecomunicaciones`**</h1>

### **INTRODUCCION**
La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, casi en cualquier lugar del mundo.
En este proyecto se realizará un análisis que permita reconocer el comportamiento del sector con el fin de establecer conclusiones que permitarán el desarrollo de objetivos para lograr una expansión en terminos de servicios de telecomunicación: Acceso a internet, líneas telefónicas fijas y telefonía móvil.

Este análisis se realizará a nivel Nacional en Argentina y para ello se obtendrán los datos desde la siguiente fuente oficial: 
https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/



### **OBJETIVOS**
Los objetivos establecidos para esté proyecto se dividen en tres etapas fundamentales:

`Análisis Exploratorio de los Datos`(Exploratory Data Analysis = EDA):
El análisis explotario se realizó con la herramienta Python y como librería principal se utilizó **Pandas Profiling**. Está herramienta permite realizar un análisis general que permite un trabajo más eficiente. A su vez, dentro de este análisis se encontrará las justificaciones  y consideraciones de la utilización de ciertos datos.
Es importante destacar que como una primera versión del proyecto, la carga de datos para realizar la exploración será por medio de la descarga de archivos en formato csv. Como segunda potencial versión se podrá plantear la importación de los datos por medio de la API REST desarrollada por la fuente oficial.
En el siguiente link encontrarán todo el proceso de EDA: [Jupyter Notebook EDA](ExploratoyDataAnalysis.ipynb)


`Análisis del Sector`:
Con el fin de interpretar la información obtenida en el paso anterior. Con el fin de establecer el mejor entendimiento, se plantean 4 KPIs con el fin de representar la situación actual del sector, así cómo también poder planear objetivos para los próximos años, en términos de acceso al servicio, infraestructura necesaria, entre otros.
Los KPIs a determinar son:
- Aumento o disminución de la variación porcental trimestral del servicio de internet cada 100 hogares por provincia.
- Tecnología disponible por habitante
- Velocidad Medida Nacional
- Ingresos anuales Telefonía Móvil, Fija e Intenter

Con el fin de medir e interpretar los KPIs propuestos se trabajará con la herramienta de Business Intelligence: **POWER BI** para la creación de dashboards que permitan la visualización y correcta interpretación de los datos.




`Visualizaciones y Dasboard`
Con Power BI se realizarón algunas transformaciones de los datos y se adecuaron las tablas para poder trabajar en las distintas visualizaciones que permita el correcto entendimiento de la situación a plantear.
En algunos casos se han aplicado transformaciones de Python con el fin de realizar transformaciones y complementar el uso de tecnología disponible.
Se aplicaron distintos criterios para determinar los KPIs establecidos con el fin de efectuar las conclusiones correspondientes.
En primer lugar se determinó el acceso a distintas tecnologías de conexión de país por habitantes. Esto nos muestra que promedio de la población tiene acceso a internet y por qué medios.
La intención de este análisis es el de establecer estrategias para alcanzar aquellos zonas donde el acceso a tecnologías que permitan un mejor uso de internet.

Ejmplo de la situación al 2022

![Alt text](_scr/Promedio%20Habitantes%20con%20acceso%20a%20tecnologias%20internet.PNG)

Esto nos indica que en términos de promedio, la población nacional cuenta con un acceso a internet por medio de cable modem. Esto podría transformarse en una oportunidad para mejorar la infraestructura, en cable modem y/o fibra óptica para que mayor población cuenta con este tipo de tecnología.


En segundo lugar se determinó la máxima y mínima velocidad (a nivel promedio) a nivel nacional.

![Alt text](_scr/velocidad%20media.PNG)

Esto nos indica que Buenos Aires (Capital Federal) es quien cuenta con la mayor velocidad de bajada y a su vez qué provincia cuenta con la menor velocidad.


Como tercer punto analizado, se determino la variación porcentual por trimestra del servicio de internet. Esto nos permite determinar la evolución del acceso a internet a nivel nacional a través de los años.
Se puede observar que a partir de Enero del 2020 la variación no cuenta con valores negativos. Esto puede deberse que a partir de ese período la pandemia del Covid 19 aceleró el uso de internet por lo que hasta el año actual la variación se mantuve positiva.

Quien se lleva distribución de ingresos para el año 2022 es la red de telefónia móvil y en segundo lugar internet. En mi criterio, esto es una buena oportunidad para combiar dos servicios requeridos para la población, acceso a internet de calidad por datos móviles.

![Alt text](_scr/Distribucion%20de%20Ingresos.PNG)



`Conclusiones`
Mediante la aplicación de distintas técnicas de programación, visualización y conocimiento del mercado, se han podido analizar el comportamiento del sector. Esto permitirá, junto a otros objetivos, enfocarse en las principales oportunidades con el fin de proyectar con inversiones a largo plazo, otorgando servicios a la población y generando revenue para la organización mediante la implementación de estas inversiones, cómo pueden ser: Mejorar la infraestructura fuera de Buenos Aires, utilizar las antenas de redes móviles para mejorar la calidad de conexión y enforcase en aquellas provincias donde aún el acceso a internet no es de calidad.


Muchas gracias por llegar hasta esta instancia