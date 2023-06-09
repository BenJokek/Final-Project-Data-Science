![header](src/dataBRIDGE_logo_black.png)

#  Google maps + Yelp! 🗺️ 🚀

## Contexto 🌍

La opinión de los usuarios se ha convertido en un dato invaluable en la planificación
de estrategias comerciales. Plataformas de reseñas como Yelp y
Google Maps proporcionan una gran cantidad de información sobre la
percepción de los usuarios respecto a diversos negocios, incluyendo restaurantes,
hoteles, esteticas y otros servicios relacionados. Esta retroalimentación
es escencial para las empresas, ya que les permite evaluar su desempeño,
identificar áreas de mejora y comprender cómo son percibidas por los
usuarios. Como parte de una consultora de data, se nos ha contratado para
realizar un análisis detallado de la opinión de los usuarios en Yelp y Google
Maps sobre negocios relacionados con el cuidado personal y la estética en el
mercado estadounidense.
El rubro de belleza abarca una amplia gama de servicios y establecimientos
relacionados con el cuidado personal y la estética. Algunos ejemplos de negocios
dentro de este rubro son los salones de belleza, spas, peluquerías, barberías,
salones de uñas, centros de estética, salones de masajes y tiendas de
productos de belleza.

## Contenidos 

* [Descripción + Objetivo](#descripcion-+-objetivo)
* [Demo](#demo)
* [KPIs](#kpis)
* [Tech Stack](#stack-tecnológico)
* [Metodología + Cronograma](#metodologia-+cronograma)
* [Modelo ER](#modelo-er)
* [Diccionario Datos](#diccionario-datos)
* [Visualizaciones](#visualizaciones)
* [Machine Learning](#machine-learning)
* [App usuario](#app-usuario)
* [Conclusiones](#conslusiones)
* [Equipo](#equipo)
* [Disclaimers](#disclaimer)

## Descripción + Objetivo 🏆

Nuestro proyecto consiste en recopilar, depurar y analizar datos de reseñas de
Yelp y Google Maps, utilizando técnicas de análisis de sentimientos y machine
learning para determinar las ubicaciones más adecuadas para establecer
nuevos locales comerciales y descubrir oportunidades de inversión investigando
aspectos como el crecimiento del mercado, la demanda de servicios de
belleza, la competencia existente y las tendencias emergentes.
Con base en el análisis realizado, generaremos recomendaciones claras y fundamentadas
para el inversor. Estas recomendaciones mostrarán las oportunidades
de inversión más atractivas en el rubro de belleza, destacando los
aspectos clave que respaldan la viabilidad y el potencial de crecimiento de
cada oportunidad.
Aunque nos enfocaremos principalmente en el sector de estetica, la metodología
puede aplicarse a otros tipos de comercios.

**El objetivo principal del proyecto** es brindar a nuestro cliente inversor de la
industria estética latinoamericana una visión general del mercado estadounidense
con el fin de que tome las decisiones mas informadas e inteligentes
para incorporarse como competidor en dicho mercado. Gracias a un análisis
exhaustivo de la opinión de los usuarios en Yelp y Google Maps podremos
identificar tendencias, predecir el crecimiento o decaimiento de rubros
comerciales y tomar decisiones estratégicas informadas para mejorar
la gestión e inversión en negocios.

## Demo 🔌

<p align='center'>
<img alt="stack" src="src/demo.gif" width="95%">
</p>

# KPIs 📈📉

En nuestro dashboard podemos visualizar 5 KPIs de distinta índole

***- Puntaje promedio de Reviews*** indica dicha información segun los filtros, teniendo como objetivo un minimo de rating de 4.2 estrellas.

***- Cantidad de Reviews*** hace referencia al promedio según los filtros. Este dato es importante ya que debe superar un minimo de 20 reviews ya que si el mismo es menor, puede significar que, mas alla de que el proemdio de reviews sea alto, la cantidad de datos de muestra de los cuales se llega a esta conclusion son pocos, por ende no confiables. 

***- La variabilidad*** KPIs se refiere a la volatilidad de los datos referidos al puntaje, cuanto menos variacion mejor, ya que los puntajes son mas predecibles, con un minimo de 0.5 de variacion. 

**-** El KPI ***Confiabildiad*** es un calculo a partir del producto de la estandarizacion del primer y segundo KPI, mostrando un dato mas exacto de que tan confiable en terminos estadísticos es dicho filtro de mercado seleccionado. 

**-** Por último el KPI ***Variacion del promedio del puntaje de reviews a través de dos divisiones diferentes de tiempo***, meses y trimestres. Con un minimo de 0,4% de aumento de las reviews con respecto al anterior periodo.

***Cabe recalcar que los objetivos fueron concluidos, no solo desde un juicio de contexto de mercado, sino tambien en base a la distribución de datos***

## Stack Tecnológico 💻

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
 ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
   ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat-square&logo=apachespark&logoColor=black) 
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0) ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)


![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white) ![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white) ![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white) ![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white) ![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white) ![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white) ![Adobe Illustrator](https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white) ![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white) ![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white)



![Google Meet](https://img.shields.io/badge/Google%20Meet-00897B?style=for-the-badge&logo=google-meet&logoColor=white) ![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)

<p align='center'>
<img alt="stack" src="src/stackfinal.png" width="75%">
</p>

## Metodología + Cronograma 📆

<p align='center'>
<img alt="stack" src="src/modelo-scrum_BLACK_solo.png" width="75%">
</p>

Trabajamos siguiendo el **CRONOGRAMA** a continuación:

<p align='center'>
<img alt="stack" src="src/GANTT.png" width="75%">
</p>

## Modelo ER 

<p align='center'>
<img alt="stack" src="src/Modelo_ER2.png" width="75%">
</p>

## Diccionario Datos 

Yelp!

Estos conjuntos de datos proporcionan información sobre negocios, reseñas,
usuarios, horarios de check-in y consejos en Yelp.
"business.pkl": contiene información sobre negocios. Las columnas incluyen el
ID del negocio, nombre, dirección, ciudad, estado, código postal, latitud, longitud,
rating en estrellas, número de reseñas, estado de apertura, atributos del negocio,
categorías y horarios de atención.
"review.json": contiene reseñas completas. Las columnas incluyen el ID de la
reseña, ID único del usuario que la escribió, ID del negocio al que se refiere la
reseña, puntaje en estrellas, fecha, texto de la reseña y votos útiles, graciosos y
cool.
"user.parquet": contiene información sobre usuarios. Las columnas incluyen el ID
del usuario, nombre, número de reseñas escritas, fecha de creación de la cuenta,
lista de amigos, votos útiles, graciosos y cool recibidos, número de fans, años
como miembro elite, promedio de valor de las reseñas y totales de cumplidos recibidos
en diferentes categorías.
"checkin.json": registra los horarios de check-in en los negocios. Las columnas
incluyen el ID del negocio y una lista de fechas y horas de check-in.
"tip.json": contiene consejos escritos por los usuarios. Las columnas incluyen el
texto del consejo, fecha de escritura, cantidad de cumplidos recibidos, ID del negocio
al que se refiere e ID del usuario que lo escribió.

Google Maps

Estos conjuntos de datos proporcionan información detallada
sobre comercios y reseñas relacionadas con Google Maps.
"metadata_sitios": contiene información sobre comercios y sus atributos,
como el nombre, dirección, ubicación geográfica, categoría,
puntaje promedio, precios y horarios de atención.
"review-estados": contiene reseñas de usuarios organizadas por estados
de EE. UU.

## Visualizaciones 

POWER BI

-screen de un dashboard -

View the application at [Deployed Project Link](Link)

<h1 align="center">Machine Learning 🤖</h1>
<h1 align="center"></h1>
<h1 align="center">Análisis de sentimientos</h1>

Aplicación de técnicas de procesamiento de lenguaje
natural (NLP) para analizar el sentimiento de las reseñas y clasificarlas
en positivas, negativas o neutrales. Haciendo uso de la libreria "SentimentIntensityAnalyzer" del conjunto "nltk.sentiment" la cual genera una nueva columna donde se clasifica cada reseña, reemplazando/traduciendo así la reseña misma a su categoría representante.

Es así como podemos ordenar y filtrar para dar a conocer cuales Estados se encuentran mas contentos con el servicio y cuales no.

## Google Maps

### Tabla resultante:

<p align='center'>
<img alt="stack" src="src/GmapTable_Análisis de Sentimientos -  Example.png" width="60%">
</p>

Esta tabla de hechos representa las características y resultados de cada una de las reviews, filtradas del rubro belleza y estética, conjunto a una nueva columna llamada Sentimiento donde se expresa si la review fue Positiva, Neutral o Negativa

Cabe recalcar que en los siguientes gráfico no se decidió tener en cuenta los "Neutrales" ya que representaban menos del 1%.
<h3 align="center">Top 5 Estados con mayor cantidad de reviews positivas</h3>

<p align='center'>
<img alt="stack" src="src/GmapPOS.png" width="60%">
</p>

<h3 align="center">Top 5 Estados con mayor cantidad de reviews negativas</h3>

<p align='center'>
<img alt="stack" src="src/GmapNEG.png" width="60%">
</p>

## Yelp

### Tabla resultante:

<p align='center'>
<img alt="stack" src="src/YelpTable_Análisis de Sentimientos -  Example.png" width="60%">
</p>

La descripción de esta tabla es idéntica que la anterior, Google Maps, solo varía de donde se extrajeron los datos; en este caso el dataset de Yelp.

<h3 align="center">Top 5 Estados con mayor cantidad de reviews positivas</h3>

<p align='center'>
<img alt="stack" src="src/YelpPOS.png" width="60%">
</p>

<h3 align="center">Top 5 Estados con mayor cantidad de reviews negativas</h3>

<p align='center'>
<img alt="stack" src="src/YelpNEG.png" width="60%">
</p>

<h1 align="center">Clustering</h1>

A través de un modelo de clustering en tres dimensiones (latitud, longitud y promedio de rating) se investigan y se agrupan los negocios. Esto orientado a sus ubicaciones geográficas específicas (Estado y Condado/County) junto a sus tendencias de rating. Complementando así con la vigente competencia en cada locación; ordenado desde el elemento con mas rating hacia el menor.
En el mismo se utilizó la librería sklearn donde se extrajo las sublibrerías StandardScaler para estandarizar los datos, KMeans para el proceso de clustering y por ultimo una segunda libreria llamada geodesic del conjunto de geopy para identificar los condados y Estados de las ubicaciones investigadas.

### Tabla resultante:

Gracias al proceso que implica el clustering al extraer los puntos centrales de cada cluster tenemos una ubicación geográfica exacta de dicho conjunto. Es así como se procede a traducir estos datos en las columnas "Estado" y "Condado"; agregando a su vez el promedio de los puntajes de las reviews de dicha zona.
Por otro lado podemos ver a la vez una comparación entre la Cantidad de Negocios presente vs la cantidad de Negocios Competidores, refiriéndose a un rubro en común; la última columna expresa la relación de esta competencia, es decir, cuanto más alto es el porcentaje, mayor competencia se encuentra presente en esta ubicación. 
Gracias a este conjunto de datos como parámetros de decisión se puede dar a conocer a cuales Estados y Condados conviene invertir dependiendo del promedio de Rating, como a su vez teniendo en cuenta el porcentaje de competición presente en cada zona. Ya que si el cliente desea un entorno de negocio con poca competencia entonces conviene buscar una zona con poca competencia en comparación a los demás. En caso contrario si el cliente desea sumarse al grupo de competentes en las zonas presentes también es factible ya que simboliza que el negocio da frutos en dicho lugar.

<p align='center'>
<img alt="stack" src="src/Clusters_Results_Table.png" width="60%">
</p>

<h3 align="center">Gráfico de Elbow</h3>

<p align='center'>
<img alt="stack" src="src/Elbow - Graph.png" width="60%">
</p>

Se puede observar que dicho gráfico indica que el número óptimo de clusters a aplicar son de aproximadamente 5. Pero el contexto de negocio de este proyecto nos exige una clasficación de las ubicaciones con mayores particiones. Por eso se optó por utilizar la cantidad de 50 clusters; así podemos tener 50 localizaciones distintas.

<h3 align="center">Gráfico 3D del clustering</h3>

En este gráfico se puede apreciar inicialmente la forma tridimensional de Estados Unidos, donde los colores representan los clusters conjunto a sus contenidos (puntos).

<p align='center'>
<img alt="stack" src="src/Clustering - Graph.png" width="60%">
</p>

Finalmente esta visualizacion demuestra la distribución de los datos geográficamente, expresados en colores dependiendo del rating de cada reseña. Se puede apreciar que las reseñas por encima de 4 (verdes) son las mas abundantes.

<p align='center'>
<img alt="stack" src="img/Mapa_Imagen_Clustering.png" width="60%">
</p>

####

# App usuario

STREAMLIT APP

<p align='center'>
<img alt="stack" src="src/app-mockup.png" width="95%">
</p>

Se puede acceder a la aplicación a través de [ESTE LINK](https://databrick-app-ro1106uif3t.streamlit.app/Proyecto)

## Equipo 🫂

| Nombre   | LinkedIn ↘️ | GitHub                | Función |
|------------|---|-----------------------|------------|
| Paula Pallares | [linkedin.com/in/paupallares/](https://www.linkedin.com/in/paupallares/) | [paupallares](https://github.com/paupallares) | Analista funcional |
| Benjamín Zambelli	| [linkedin.com/in/benjamin-zambelli/](https://www.linkedin.com/in/benjamin-zambelli/) | [BenJokek](https://github.com/BenJokek) | Data Engineer |
| Beder Rivera | [linkedin.com/in/beder-rivera/](https://www.linkedin.com/in/beder-rivera/) | [cullanco-huaman](https://github.com/cullanco-huaman) | Data Engineer | 
| Claritzo Pérez Marcano | [linkedin.com/in/claritzoperez/](https://www.linkedin.com/in/claritzoperez) | [Claritzo](https://github.com/Claritzo) | Data Analyst | 
| Gonzalo Schwerdt | [linkedin.com/in/gonzalo-schwerdt/](https://www.linkedin.com/in/gonzalo-schwerdt-84641a214/) | [GonzaloSchwerdt](https://github.com/GonzaloSchwerdt) | ML Engineer | 


## Disclaimer

Este material se proporciona únicamente con fines educativos. No se pretende ni se debe interpretar como asesoramiento legal, financiero o profesional de ningún tipo. La información contenida en este material es precisa y completa en la medida de nuestro conocimiento, pero no garantizamos su exactitud, integridad o actualidad.

El uso de este material es bajo su propio riesgo. No nos hacemos responsables de ningún daño, pérdida o inconveniente causado por el uso de este material.

<p align='center'>
<img alt="stack" src="[src/app-mockup.png](https://i.gifer.com/3b4.gif)https://i.gifer.com/3b4.gif">
</p>

