# **INDIVIUDAL PROJECT Nº3**
# **Author: Hector Javier Herrera Espínola**


**Updated: 26/03/2023**



# <h1 align="center">**` TELECOMMUNICATIONS`**</h1>

### **INTRODUCTION**
The telecommunications industry has played a vital role in our society, facilitating information on an international scale and enabling continuous communication even in the midst of a global pandemic. The transfer of data and communication is carried out mostly through the internet, fixed telephone lines, mobile telephony, almost anywhere in the world.
In this project, an analysis will be carried out to recognize the behavior of the sector in order to establish conclusions that will allow the development of objectives to achieve an expansion in terms of telecommunication services: Internet access, fixed telephone lines and mobile telephony.

This analysis will be carried out at the National level in Argentina and for this the data will be obtained from the following official source: 
https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/




![Workflow](_scr\Workflow.jpg)



### **OBJETIVOS**

The objectives established for this project are divided into three fundamental stages:

*Exploratory Analysis*
The exploitation analysis was carried out with the Python tool and **Pandas Profiling** was used as the main library. This tool allows a general analysis that allows a more efficient work. In turn, within this analysis you will find the justifications and considerations for the use of certain data.
It is important to note that as a first version of the project, the data upload to carry out the exploration will be through the download of files in csv format. As a second potential version, it will be possible to consider importing the data through the REST API developed by the official source.
In the following link you will find the entire EDA process: [Jupyter Notebook EDA](ExploratoyDataAnalysis.ipynb)


*Sector Analysis*
In order to interpret the information obtained in the previous step. In order to establish the best understanding, 4 KPIs are proposed in order to represent the current situation of the sector, as well as to be able to plan objectives for the coming years, in terms of access to the service, necessary infrastructure, among others.
The KPIs to determine are:
- Increase or decrease in the quarterly percentage variation of Internet service per 100 households by province.
- Quarterly percentage variation of users with more frequent technologies
- Nationwide speed ranges


In order to measure and interpret the proposed KPIs, the Business Intelligence tool will be used: **POWER BI** for the creation of dashboards that allow the visualization and correct interpretation of the data.




*Visualizaciones y Dasboard*
With Power BI, some transformations of the data were carried out and the tables were adapted to be able to work in the different visualizations that allow the correct understanding of the situation to be considered.
Different criteria were applied to determine the established KPIs in order to draw the corresponding conclusions.
Firstly, access to different country connection technologies per inhabitant was determined. This shows us what average population has access to the Internet and by what means.
The intention of this analysis is to establish strategies to reach those areas where access to technologies that allow better use of the Internet.

