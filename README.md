Descripción de los datos
Datos utilizados en la primera parte del proyecto

/datasets/hypotheses_us.csv Descarga el dataset

Hypotheses: breves descripciones de las hipótesis
Reach: alcance del usuario, en una escala del uno a diez
Impact: impacto en los usuarios, en una escala del uno al diez
Confidence: confianza en la hipótesis, en una escala del uno al diez
Effort: los recursos necesarios para probar una hipótesis, en una escala del uno al diez. Cuanto mayor sea el valor Effort, más recursos requiere la prueba.
Datos utilizados en la segunda parte del proyecto

 /datasets/orders_us.csv Descarga el dataset

transactionId: identificador de pedido
visitorId: identificador del usuario que realizó el pedido
date: fecha del pedido
revenue: ingresos del pedido
group: el grupo del test A/B al que pertenece el usuario
/datasets/visits_us.csv Descarga el dataset

date: la fecha
group: grupo del test A/B
visits: el número de visitas en la fecha especificada para el grupo de test A/B especificado
Asegúrate de preprocesar los datos. Es posible que haya errores en los datasets originales; por ejemplo, algunos de los visitantes podrían haber entrado tanto en el grupo A como en el grupo B.

Parte 1. Priorizar hipótesis
El archivo hypotheses_us.csv contiene nueve hipótesis sobre cómo aumentar los ingresos de una tienda en línea con Reach, Impact, Confidence y Effort especificados para cada una.

El ejercicio consiste en:

Aplicar el framework ICE para priorizar hipótesis. Ordenarlas en orden descendente de prioridad.
Aplicar el framework RICE para priorizar hipótesis. Ordenarlas en orden descendente de prioridad.
Mostrar cómo cambia la priorización de hipótesis cuando utilizas RICE en lugar de ICE. Proporcionar una explicación de los cambios.
Parte 2. Análisis de test A/B
Realizaste un test A/B y obtuviste los resultados descritos en los archivos orders_us.csv y visitors_us.csv.

Ejercicio

Analiza el test A/B:

Representa gráficamente el ingreso acumulado por grupo. Haz conclusiones y conjeturas.
Representa gráficamente el tamaño de pedido promedio acumulado por grupo. Haz conclusiones y conjeturas.
Representa gráficamente la diferencia relativa en el tamaño de pedido promedio acumulado para el grupo B en comparación con el grupo A. Haz conclusiones y conjeturas.
Calcula la tasa de conversión de cada grupo como la relación entre los pedidos y el número de visitas de cada día. Representa gráficamente las tasas de conversión diarias de los dos grupos y describe la diferencia. Saca conclusiones y haz conjeturas.
Traza un gráfico de dispersión del número de pedidos por usuario. Haz conclusiones y conjeturas.
Calcula los percentiles 95 y 99 para el número de pedidos por usuario. Define el punto en el cual un punto de datos se convierte en una anomalía.
Traza un gráfico de dispersión de los precios de los pedidos. Haz conclusiones y conjeturas.
Calcula los percentiles 95 y 99 de los precios de los pedidos. Define el punto en el cual un punto de datos se convierte en una anomalía.
Encuentra la significancia estadística de la diferencia en la conversión entre los grupos utilizando los datos en bruto. Haz conclusiones y conjeturas.
Encuentra la significancia estadística de la diferencia en el tamaño promedio de pedido entre los grupos utilizando los datos en bruto. Haz conclusiones y conjeturas.
Encuentra la significancia estadística de la diferencia en la conversión entre los grupos utilizando los datos filtrados. Haz conclusiones y conjeturas.
Encuentra la significancia estadística de la diferencia en el tamaño promedio de pedido entre los grupos utilizando los datos filtrados. Haz conclusiones y conjeturas.
Toma una decisión basada en los resultados de la prueba. Las decisiones posibles son: 1. Para la prueba, considera a uno de los grupos como líder. 2. Para la prueba, concluye que no hay diferencia entre los grupos. 3. Continúa la prueba.
¿Cómo será evaluado mi proyecto?
Tu proyecto será evaluado según estos criterios. Léelos atentamente antes de empezar el proyecto. 

Esto es lo que buscan los revisores de proyecto cuando evalúan tu proyecto:

Cómo preparas los datos para el análisis
Cómo priorizas las hipótesis
Cómo interpretas los gráficos resultantes
Cómo calculas la significancia estadística
Qué conclusiones sacas con base en los resultados del test A/B
Si sigues la estructura del proyecto y mantienes el código ordenado
Las conclusiones que sacas
Si dejas comentarios en cada paso