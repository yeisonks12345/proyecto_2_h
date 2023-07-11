# Internet fijo y telefonía móvil en Argentina
## Descripción
A partir de los datos abiertos suministrados por el *gobierno de Argentina* se realiza un analisis general relacionado con los accesos de internet fijo por provincia, de igual , se  analizan los ingresos generados por concepto de uso de telefonía móvil a partir del año 2013 hasta el año 2022. Como información adicional se uso una base de datos suministrada por el instituto nacional de estadistica y censo INDEC con información sobre total de la población, total de viviendas discriminado por provincias entre otros, para el desarrollo del presente análisis se uso *google colab* producto de google que permite ejecutar codigo de python.
**las librerias empleadas en el EDA son**:
1. Pandas
2. Numpy
3. Matplotlib.pyplot
4. Seaborn
**En este repositorio encotrarán los siguientes archivos:**
1. df: contiene los archivos en formato csv para los diferentes analisis.
2. EDAda.ipynb: Notebook donde se encuentra el EDA.
   
## Objetivo
Explorar los data sets que contiene información sobre accesos de internet, telefonía móvil y población en Argentina, para identificar oportunidades de crecimiento para el sector de las telecomunicaciones.
## EDA
Al cargar los datos en colab con pandas, se identifica que son leidos con el tipo de dato correcto,lo que agiliza el trabajo de exploración de los datos. Para el conjunto de datos denominado accesos internet fijo  por tecnología y localidad creamos una función de agregación por provincia de Argentina e identificamos que las cinco provincias con mayor acceso a internet con corte al tercer trimestre del año 2022 son: Buenos Aires, CABA, Córdoba, Santa Fe y Mendoza.
También se identifica que las principales tecnologías usadas con corte del mismo periodo son: Cablemodem con un 55% de participación seguido de Fibra optica con 26%, ADSL y Wireless.
En el set de datos denominado censo Argentina 2022 se encuentra que para el año 2022 en Argentina hay 17.8 millones de viviendas, si tenemos en cuenta que para el mismo años los accesos de internet son de 11 millones, evidenciamos una amplia posibilidad de expansión para el sector. Al realizar la razón entre accesos de internet sobre total de viviendas discriminado por provincia encontramos que provincias como Formosa, Santiago del estero, Corrientes y Chaco el ratio esta por debajo del 36%, es decir que casi 6 de cada 10 viviendas no cuentan con acceso de internet. Otro hallazgo relevante se encuentra en el data set internet accesos por tecnologia, al graficar la tendencia de acceso a internet en las tres provincias con mayor acceso las cuales son Buenos Aires, CABA y Cordoba se observa que en Buenos Aires presenta un acelerado crecimiento en cuanto a accesos de internet, mientras que en CABA la tendencia ha sido constante en el intervalo 2014-2021. Podría explicarse a que la relación accesos internet por vivienda esta sobre el 94% lo que implica un margen de crecimiento limitado.
Para el dataset historico velocidad internet y cruzar la informacón de mbps con respecto a los ingresos se encuentra una relación directa entre ambas variables, lo que implica que a mayor media de baja en mbps mayor ingreso generado.
Por último a comparar los ingresos generados por concepto de acceso de internet fijo vs telefonia movil, se identifica que esta última supera en casi tres veces los ingresos generados por concepto de internet fijo. 
## KPI`S
1. **Para el cuarto trimestre del año 2024 el objetivo es aumentar el acceso de internet por**      
   viviendas en un 70 % para la provincia  de Córdoba.
   De acuerdo a los datos se identifica que en la provincia de cordoba la razón entre el total de accesos y el total de viviendas es del 64%, dado que la provincia de Córdoba es una de las principales en cuanto a población y generación de ingresos, se considera que es ideal para expandir la tecnología de internet.

2. **Incrementar en un 30% la cobertura de tecnología de fibra óptica en Argentina  al finalizar**  
   el curto trimestre del año 2024.
   Dado que la tecnología de fibra optica representa el 26% de la tecnologia usada en Argentina, se considera idonea para captar nuevos clientes en las provincias con bajo acceso de internet, las propiedades de velocidad, fiabilidad y costos son la carta de presentación perfecta.

3. **Para el cuarto trimestre del año 2024  incrementar en un 10% el servicio de telefonía móvil modalidad pospago.** 
   Los datos nos muestran que de 46 millones de habitantes en la Argentina solo 6 millones disponen de un servicio pospago, se encuentra un alto potencial de crecimiento al poder ofrecer servicios de internet que incluya fribra optica e iternet movil. 
