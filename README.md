# ICCS
El Estudio Internacional de Cívica y Ciudadanía (ICCS), tiene como propósito brindar información sobre el conocimiento y la comprensión que tienen los estudiantes sobre conceptos y asuntos que se relacionan con la educación cívica y ciudadania. Asimismo, busca informar acerca de los
valores, actitudes, comportamientos ciudadanos y sobre las características de los contextos en los que estos aprendizajes se sitúan. El diseño muestral es por conglomerados, estratificado y bietápico, siendo la primera unidad de muestreo la escuela (conglomerado) y la segunda unidad una sección de cada
escuela. La base de datos del ICCS consta de 5 valores plausibles.
La oficina es responsable de la construcción del marco muestral y del cálculo de resultados. Para ello, se han desarrollado las siguientes funciones:

## 1. Marco muestral: Generación automatizada del marco para la selección de la muestra.
El marco muestral permite seleccionar una muestra de estudiantes que refleje fielmente la realidad educativa del país. Esto garantiza que los resultados puedan generalizarse a toda la población objetivo (.....) y 
compararse válidamente con los de otros países participantes.

## 2. Cálculo de resultados: Obtención de medidas estadísticas y niveles de logro por diversos estratos.

El Estudio Internacional de Educación Cívica y Ciudadanía (ICCS) tiene como objetivo proporcionar información sobre el conocimiento y la comprensión que los estudiantes poseen respecto a conceptos y temas relacionados con la educación cívica y ciudadana. Además, busca analizar sus valores, actitudes y comportamientos ciudadanos, así como las características del contexto en el que se desarrollan estos aprendizajes.

El diseño muestral de ICCS es por conglomerados, estratificado y bietápico. La primera unidad de muestreo es la escuela (conglomerado), y la segunda, los estudiantes. La base de datos de PISA incluye 10 valores plausibles por cada área evaluada y 75 pesos replicados, calculados mediante el método BRR-Fay.

Para el cálculo de estimaciones, se tomó como referencia el documento PISA Data Analysis Manual, el cual puede descargarse en el siguiente enlace:
👉 https://www.iea.nl/sites/default/files/2024-07/ICCS%202022%20Technical%20Report.pdf

La funciones MP_ICSS y NL_ICSS requieren los siguientes argumentos:

** data : Base de datos con la información a procesar.

** estrato: Nivel de desagregación para los resultados del estudio. Puede ser por país (COUNTRY), por sexo (TFGender), por área geográfica (area), o por tipo de gestión de la institución educativa (gestion).

** año: Año del estudio, es 2016.

A continuación, se pueden descargar las funciones para el cálculo de la medida promedio y los niveles de logro en las evaluaciones internacionales:
Medida promedio : devtools::source_url("https://raw.githubusercontent.com/Sadith20/ICCS/refs/heads/main/02.1%20Funcion_MP_ICSS.R")

Niveles de logro : devtools::source_url("https://raw.githubusercontent.com/Sadith20/ICCS/refs/heads/main/02.2%20Funcion_NL_ICSS.R")

## 3. Gráficos: Visualización de los resultados mediante gráficos generados de forma automatizada.

