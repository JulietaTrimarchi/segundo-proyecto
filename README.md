<p align="center">
    <img src="images/logo.png" alt="Logo del Proyecto" width="400"/>
</p>
<h1 align="center">Análisis de Penetración y Acceso a Tecnologías de Internet en Argentina</h1>

Este trabajo tiene como objetivo  analizar los accesos por tecnología en cada provincia de Argentina para detectar cuáles tienen una mayor y menor penetración de tecnologías más modernas o eficientes. Además, identificar provincias con baja cantidad de accesos para enfocar allí oportunidades de crecimiento. A través de un EDA inicial y la creación de un dashboard en Power BI, se busca identificar oportunidades de crecimiento en cuanto a la infraestructura y a la penetración y ayudar a la toma de desiciones estratégicas. El análisis se centra en los accesos por tecnología, la penetración por cada 100 habitantes y evaluación de zonas con baja conectividad. 

## Descripción General

El análisis se basa en datos de acceso a tecnologías de Internet en Argentina, desglosados por provincias y tipos de tecnología así como también en datos de acceso cada 100 habitantes desglosados por provincias y trimestres del año. El proyecto busca evaluar qué provincias tienen tecnologías más modernas o más tradicionales y detectar provincias con baja conectividad para proponer estrategias de mejora. 

## Contenido del Repositorio

- Datasets: Contiene el archivo llamado "Internet" que contiene la data utilizada para el análisis EDA. El mismo fue descargado de la página oficial de ENACOM (Ente Nacional de Comunicaciones).
- Data_Processed: Contiene los archivos de datos creados en el EDA luego de limpiar y procesar la data para su posterior utilización en Power BI. Detallo a continuación cada uno de estos:
*accesos_tecnologia_años*: contiene los accesos a las distintas tecnologías por provincia, año y trimestre.
*accesos_tecnologia_provincias*: contiene los accesos a las distintas tecnologías por localidad, partido y provincia. 
*penetracion_provincias_con_outliers*: contiene los accesos cada 100 habitantes por provincia, año y trimestre. Cuenta con los outliers detectados.
*penetracion_provincias_sin_outliers*: contiene los accesos cada 100 habitantes por provincia, año y trimestre. No cuenta con los outliers detectados. 
- Notebooks: Contiene un notebook que es el informe EDA (Análisis Exploratorio de Datos) donde se realiza el análisis y estudio del dataset y se detallan los insights obtenidos a partir del mismo.
- Dashboard.pbix: Archivo de Power BI que contiene el dashboard con visualizaciones interactivas. 
- README.md: Es un archivo que contiene la descripción general del proyecto.

## Descripción del Análisis y Reporte de KPIs

**Análisis y Dashboard**

Voy a detallar dos visualizaciones que fueron realizadas en el dashboard para los aspectos analizados en el EDA.
- *Mapa de calor* que muestra la distribución de acceso a las distintas tecnologías en cada provincia. 
- *Gráfico de barras horizontales* para comparar la penetración por provincia. 

**Reporte de KPIs** 

- *KPI 1: Identificación de provincias con baja penetración*: Evalúa qué provincias tienen una penetración por debajo del promedio global con un objetivo del 2% anual. Su propósito es medir si el acceso a internet en cada provincia ha alcanzado la meta de crecimiento y detectar si hay un aumento sostenido en la penetración.
- *KPI 2: Crecimiento de tecnologías modernas vs tradicionales*: Mide el crecimiento de las tecnologías modernas (Fibra Óptica y Cablemodem) en comparación con las tecnologías tradicionales (ADSL, Dial Up, entre otras) en cada provincia. Su propósito es identificar si las provincias están adoptando cada vez más tecnologías eficientes y modernas que ofrecen mayor velocidad y estabilidad. Las tecnologías modernas deberían representar al menos un 60% de los accesos totales en cada provincia en un rango anual.
- *KPI 3: Provincias con mayor crecimiento en penetración por cada 100 habitantes*: Mide el crecimiento de la penetración por cada 100 habitantes en cada provincia a lo largo del tiempo, identificando las provincias que muestran un mayor aumento en la penetración de internet. Su objetivo es lograr un crecimiento sostenido de al menos un 5% anual en penetración por cada 100 habitantes en las provincias con menor acceso. 

## Conclusiones y Recomendaciones

**Conclusiones**

- Cablemodem y Fibra Óptica son las tecnologías predominantes en la mayoría de las provincias, mientras que Dial Up tiene muy pocos accesos. 
- Tecnologías como Satelital y WiMAX tienen accesos bajos en casi todas las provincias.
- La penetración de accesos es considerablemente mayor en las provincias del centro y del sur del país, mientras que las provincias del norte y noroeste tienen menor acceso.

**Recomendaciones**

- La empresa podría enfocarse en mejorar el acceso en las provincias de baja penetración para aumentar su participación en el mercado y contribuir a la reducción de la brecha digital.
- Promover la adopción de tecnologías modernas en regiones donde aún predominan tecnologías absoletas.
- Focalizar esfuerzos de expansión en las provincias que han mostrado crecimiento estable. 

## Instrucciones de Uso

1) Clonar el repositorio: 
git clone https://github.com/JulietaTrimarchi/segundo-proyecto.git

2) Asegúrate de tener instaladas las dependencias necesarias.

3) Abre el archivo Informe_EDA.ipynb que se encuentra dentro de la carpeta Notebooks para ver el análisis exploratorio.

4) Abre el archivo Dashboard.pbix en Power BI para interactuar con el dashboard.



