 # ProyectoCD

Para la Maestría en Behavioral Data Science, se solicitó diseñar una investigación reproducible en ciencias de datos, en este caso me tomé la libertad de explorar con mayor profundidad temas sociales que me atraviesan personalmente. Al revisar las bases de datos disponibles en Gapminder, encontré una gran variedad de información relacionada con las mujeres, lo que despertó en mí una inquietud sobre la posible relación entre la longevidad femenina y la maternidad.
En Costa Rica, existe una expresión popular según la cual “tener hijos te riega las bilis”, lo que en el imaginario colectivo podría asociarse con la idea de que la maternidad acorta la vida. Esta creencia me llevó a preguntarme si realmente existe una relación significativa entre la esperanza de vida de las mujeres y la cantidad promedio de hijos o hijas que tienen.
En lo personal, mi familia ilustra esta interrogante de forma particular. Mi madre tuvo una sola hermana, quien no tuvo hijos y falleció a una edad relativamente baja para los estándares actuales. Por otro lado, espero que mi madre —quien sí tuvo hijos— viva muchos más años que el promedio nacional. Aunque anecdótica, esta observación familiar me motivó a profundizar en la investigación científica sobre el tema.
En el proceso, encontré tres estudios que llamaron mi atención. Vaupel (2001) plantea que podría existir una relación positiva entre el número de hijos y la longevidad en las mujeres, especialmente cuando el último parto ocurre a una edad avanzada. Por su parte, Zhang et al. (2023) afirman que las mujeres que tienen entre tres y cinco hijos tienden a vivir más tiempo, mientras que aquellas con uno o ningún hijo presentan una esperanza de vida más corta.
Me resulta interesante cómo estas investigaciones se reflejan, de alguna forma, en la experiencia de mi propia familia. A mis 35 años, nunca había considerado que la decisión de tener hijos pudiera estar vinculada con la longevidad. Aunque esta no ha sido una motivación personal, estos hallazgos abren la posibilidad de considerar la maternidad desde una perspectiva distinta.
Por otro lado, Hampton (2021) analiza la relación entre desarrollo y fecundidad, señalando que, aunque existe la idea de que a mayor desarrollo económico se podría esperar un aumento de la fecundidad, en la práctica no se observa una asociación directa. Su estudio concluye que, al menos en la última década, los niveles elevados de desarrollo humano ya no están vinculados con repuntes en la tasa de natalidad.

# Objetivo

Ante estas inquietudes el Objetivo General es:
Explorar la posible relación entre la esperanza de vida femenina, la fecundidad y el nivel de desarrollo económico en países del mundo, a partir de datos históricos entre 1950 y 2021 disponibles en Gapminder.
En cuanto a los objetivos específicos son:
1.	Analizar patrones y tendencias en la relación entre esperanza de vida femenina y número promedio de hijos por mujer, identificando posibles asociaciones según región geográfica y a lo largo del tiempo.
2.	Explorar la relación entre el producto interno bruto per cápita (ajustado por poder adquisitivo) y los niveles de fecundidad y longevidad femenina, para determinar si existen diferencias significativas entre países con distinto nivel de desarrollo económico.

Ante estos objetivos he decidido trabajar con tres conjuntos de datos disponibles en Gapminder para desarrollar un análisis exploratorio de datos:

•	Life_expectancy_female: esperanza de vida al nacer de mujeres (en años).

•	Children_per_women_total_fertility: número promedio de hijos por mujer a lo largo de su vida.

•	Gross domestic product per person: producto interno bruto per cápita ajustado por paridad de poder adquisitivo al año 2021.

Estos conjuntos de datos cubren periodos desde 1800 hasta 2100, por lo que el análisis se centrará en los datos comunes disponibles a partir de 1950.

# Carpeta Datos
Vas a encontrar la información general sobre los datos tanto originales como depurados.

**1. Carpeta Base de Datos Original**

En esta carpeta vas a encontrar las tres bases de datos antes mencionadas en su formato EXCEL.

**2. Carpeta Código de depuración**

En el documento codigo-depuracion.RMD se puede encontrar el documento donde se realizó la depuración y también donde se empezó a realizar gráficos comparaciones y análisis para el Reto 1.
El documento codigo-depuracion.pdf se puede encontrar el mismo pero renderizado para PDF. Para poder acceder a el más facilmente.

# Base de Datos Depurada.

Al terminar la depuración del código, se colocó la base de datos en la carpeta correspondiente. 

# Carpeta Dashboard
Puede encontrar el Dashboard interactivo para poder realizar un análisis sobre cómo se relaciona la esperanza de vida, la cantidad de hijos por mujer y el producto interno bruto. Tanto en Rmd como en html.

# Carpeta Informe
Se puede encontrar el informe del proyecto, tanto en Rmd, html como en PDF, para poder acceder a las concluisiones del proyecto. Además se puede encontrar un pequeño Dashbor no interactivo con el nombre de Informe Fecundidad, esperanza de vida y GDP.Rmd

# Carpeta Presentación
En esta carpeta puede encontrar la presentación concreta del proyecto de ciencias de datos tanto en Rmd, html y pdf.


