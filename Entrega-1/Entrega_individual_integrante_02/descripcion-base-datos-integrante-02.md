# Contexto y Descripción del Material #

Esta base de datos ha sido diseñada como un registro especializado en la incidencia de infracciones y sanciones disciplinarias en los enfrentamientos entre Colo-Colo y Universidad de Chile. El material busca cuantificar de manera aislada la fricción física del encuentro, permitiendo comparar el volumen de faltas y el rigor de las amonestaciones a lo largo de las últimas dos décadas y media. Al centrarse únicamente en estos indicadores, se facilita el análisis de correlación entre el paso del tiempo y la supuesta disminución de la rudeza en el campo de juego.

## Ficha Técnica de la Base de Datos ##

### Autor y publicación de los datos ### 

Los datos primarios son de propiedad pública y corresponden a los informes oficiales de la Asociación Nacional de Fútbol Profesional (ANFP). La base de datos consolidada es de autoría propia de los integrantes del grupo, quienes han recopilado y procesado la información desde portales de estadística deportiva como SoloFutbol.cl, SofaScore y los archivos digitales de la prensa deportiva nacional.

### Contenido ###

La base contiene la estadística disciplinaria dura de cada Superclásico disputado en el siglo XXI.

#### Tipo de datos: #### 

Cuantitativos discretos.

#### Variables ####

Fecha (Identificador temporal), Local (Equipo), Visita (Equipo), Faltas_Totales (Suma de infracciones de ambos equipos), Tarjetas_Amarillas (Cantidad total) y Tarjetas_Rojas (Cantidad total).

#### Periodo: ####

El levantamiento abarca desde el año 2000 hasta el presente año 2026.

### Pertinencia ### 

Este material es la herramienta fundamental para probar nuestra hipótesis. La base es valiosa porque permite aislar el factor "agresividad" de otras variables del juego. Para nuestro reportaje, estos datos sirven para crear visualizaciones de tendencia (gráficos de líneas y barras) que demuestren si el número de faltas y tarjetas ha seguido una trayectoria descendente de manera sostenida.

### Metodología ###

El plan de construcción de la base de datos se divide en dos fases técnicas:

#### Levantamiento Manual (2000-2012) #### 

Inscripción manual de datos mediante la revisión de fichas técnicas históricas y crónicas de partidos. En este periodo, las tarjetas son el dato más accesible y confiable, mientras que las faltas se obtienen de los reportes detallados de la prensa.
   
#### Extracción Automatizada (2013-2026) #####

Uso de herramientas de consulta en sitios de estadística en tiempo real (web scraping) para obtener el conteo exacto de faltas y amonestaciones sancionadas oficialmente.
   
#### Consolidación #####

Los datos se unifican en un archivo .csv con una estructura de tabla limpia, eliminando cualquier ruido informativo externo para enfocarse en la frecuencia de las infracciones.
   
