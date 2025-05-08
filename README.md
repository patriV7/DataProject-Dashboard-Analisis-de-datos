# DataProject-Dashboard-Analisis-de-datos

Proyecto donde se aplican los conocimientos aprendidos en el módulo de Dashboard y Análisis de datos.
Objetivo del proyecto: Realizar un análisis exploratorio de un conjunto de datos de elección propia y reflejar en un dashboard. 

En este caso, mi análisis versa sobre cómo afectan los hábitos de distintos estudiantes en su rendimiento académico. El conjunto de datos simulado explora cómo los hábitos de vida afectan el rendimiento académico de los estudiantes. Con 1000 registros sintéticos de estudiantes y más de 15 características, incluyendo horas de estudio, patrones de sueño, uso de redes sociales, calidad de la dieta, salud mental y calificaciones de exámenes finales, entre otros.

¿Alguna vez te has preguntado cuánto afecta Netflix, el sueño o TikTok a tus calificaciones? 👀 Este conjunto de datos simula los hábitos diarios de 1000 estudiantes, desde el tiempo de estudio hasta la salud mental, y los compara con las calificaciones de los exámenes finales. Vamos a ello!!

● Transformación y limpieza de los datos.

En primer lugar, he cargado el fichero CSV de los datos con los que voy a trabajar y he hecho un análisis preliminar de los datos para comprobar qué información se incluye en el mismo. A continuación, antes de pasar al análisis en profundidad de los datos, he procedido a la limpieza y transformación de los datos (comprobación de duplicados, valores nulos y/o vacíos, establecer formato correcto -números, fechas, porcentajes-).

● Análisis descriptivo de los datos.

En primer lugar, en la hoja de mi Dashboard, he añadido el título de mi análisis y los KPI's principales (media del nº de horas diarias invertidas en: estudio, redes sociales, netflix, sueño). A simple vista podemos comprobar cómo, de media, los estudiantes invierten más tiempo en redes sociales y netflix (la suma de ambas es 4,33h) de lo que invierten en estudio (3,55h). 
En segundo lugar, he añadido unos gráficos circulares que muestran las horas de estudio, de redes sociales y de sueño por género, así como unos diagramas de dispersión para ver las relaciones positivas o negativas entre el rendimiento académico y las horas de estudio, de redes sociales y de sueño.
A continuación, he añadido unos gráficos de barras para analizar la distribución del rendimiento académico según la edad, el porcentaje de asistencia a clase y si tienen o no un trabajo a tiempo parcial que compaginan con el estudio. 
Finalmente, he añadido unos graficos de líneas para analizar cómo afecta al rendimiento el hecho de que los estudiantes tengan buenos hábitos como hacer deporte, una dieta saludable o buena salud mental.
El dashboard dispone de una serie de filtros en el lateral que funcionan de forma interactiva para analizar todos los puntos anteriores de una manera más segmentada en función de los distitnos intereses.

● Dashboard.

(https://docs.google.com/spreadsheets/d/1QcTCfyPT4xNsZPC70iiTTUQ8P31FNm4XMwYeYJFx2Tk/edit?gid=1160160238#gid=1160160238)

● Informe explicativo del análisis.

En primer lugar, me gustaría destacar que el análisis ha sido realizado teniendo en cuenta en las comparaciones la media del rendimiento académico de los alumnos, así como de horas de estudio y de horas en redes sociales o netflix (al ser una muestra de 1000 estudiantes repartidos proporcionalmente entre chicos y chicas no tenía mucho sentido hacer sumatorias del número de horas de la muestra total o del score en exámenes de la muestra total).
Tal y como mencioné al principio,  simple vista, gracias a los big numbers, podemos comprobar cómo, de media, los estudiantes invierten más tiempo en redes sociales y netflix (la suma de ambas es 4,33h) de lo que invierten en estudio (3,55h). 
Una vez que he realizado el análisis al completo, he decidido no incluir información de aquellas variables que no tienen un impacto significativo en el rendimiento académico y que, por tanto, no aportan valor al dashboard (variables tales como el nivel de formación de los padres, la calidad de la dieta o si tienen o no trabajo a tiempo parcial). Sí que he añadido prácticamente todas las variables como filtro para poder hacer comprobaciones entre las distintas categorías.
A rasgos generales, podemos observar cómo variables como las horas de estudio al día o el porcentaje de asistencia a clase tienen una relación positiva con el rendimiento académico. Por otra parte, las horas al día invertidas en redes sociales tienen una relación negativa con el rendimiento académico (aquellos alumnos que pasan un mayor número de horas en redes sociales tienen unos score de examen más bajos y viceversa). Las horas de sueño al día también están relacionadas positivamente con el rendimiento académico, tal como era de esperar. Otra de las variables que está afectando de manera significativa y positiva al rendimiento académico de los alumnos es la frecuencia con la que practican algún deporte. Finalmente, también es muy destacable el ratio de salud mental: a mayor salud mental mayor score de examen.

La conclusión que podemos sacar gracias al análisis es la siguiente: tener buenos hábitos tales como dormir suficiente, realizar ejercicio a menudo, tener una buena salud mental y dedicar tiempo al estudio y a la asistencia a clase contribuyen de manera positiva a mejorar el rendimiento académico de los estudiantes, mientras que tener hábitos como falta de sueño, demasiadas horas en redes sociales o netflix, sedentarismo o bajos ratios de salud mental contribuyen de manera negativa al rendimiento académico de los alumnos. 


