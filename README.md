Proyecto Big Data: Análisis de Morosidad en Préstamos Bancarios
Objetivo del Proyecto
El propósito de este proyecto es analizar los patrones y factores que influyen en la morosidad de los préstamos bancarios. Con este análisis, las entidades financieras podrán anticipar el riesgo de impago y tomar medidas preventivas para reducir la morosidad, lo que contribuye a la estabilidad financiera y mejora la eficiencia operativa.

Descripción del Problema
La morosidad en los préstamos bancarios representa un desafío significativo para las instituciones financieras, afectando su liquidez, estabilidad y costos operativos. Identificar los factores que contribuyen al incumplimiento de los préstamos es crucial para gestionar el riesgo y minimizar los efectos negativos sobre el negocio.

Datos Utilizados
Se utilizaron datos históricos de clientes y préstamos, que incluyen información sobre:

Monto del préstamo
Tipo de préstamo
Tasa de interés
Estado de pagos (incumplido o no)
Información personal del solicitante (género, edad, ingresos, puntaje crediticio, etc.)
El conjunto de datos consta de 34 columnas y 148,670 filas, lo que abarca diversas características relacionadas con los solicitantes de préstamos y sus historiales financieros.

Técnicas de Análisis
Distribución de variables clave: Se analizaron variables como género, edad, puntaje crediticio, monto del préstamo, ingresos, y estado del préstamo para entender su distribución y relevancia.

Predicción de incumplimiento: Se utilizó la columna estado de préstamo como variable objetivo para predecir el incumplimiento de los préstamos.

Segmentación de clientes: Se realizó una segmentación de los solicitantes basada en características como edad y solvencia financiera.

Análisis de correlación: Se identificaron los factores más correlacionados con el incumplimiento, como la tasa de interés, puntaje crediticio, y tipo de préstamo.

Visualización de Datos
Se utilizaron herramientas de visualización para explorar y comunicar los resultados del análisis de datos, facilitando la identificación de patrones y tendencias importantes.

Columnas Principales del Dataset
Algunas de las columnas clave utilizadas en el análisis incluyen:

Solicitud de préstamo: Identificación de la solicitud.
Año de solicitud: Año en que se solicitó el préstamo.
Límite del préstamo: Indica si el préstamo es conforme (cf) o no conforme (ncf).
Género: Género del solicitante (masculino, femenino, conjunto, no disponible).
Tipo de préstamo: Fines comerciales, empresariales o personales.
Monto del préstamo: Cantidad total solicitada.
Tasa de interés: Tasa aplicada al préstamo.
Ingresos: Ingresos anuales del solicitante.
Puntuación crediticia: Valor crediticio del solicitante.
Relación deuda-ingreso (DTI): Relación entre las deudas del solicitante y sus ingresos.
Herramientas y Tecnologías Utilizadas
Este proyecto fue implementado utilizando:

Python: Para el procesamiento de datos y modelado.
Pandas: Manipulación y análisis de datos.
Numpy: Operaciones matemáticas y de álgebra lineal.
Matplotlib: Visualización de datos.
Contribución
Este análisis proporciona información valiosa para los bancos y otras entidades financieras sobre los factores de riesgo que contribuyen a la morosidad, lo que puede ayudarles a mejorar sus estrategias de crédito y gestión de riesgos.
