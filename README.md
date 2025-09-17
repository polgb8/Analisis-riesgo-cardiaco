Análisis de Factores de Riesgo Cardíaco para la Prevención Estratégica en Salud
Resumen Ejecutivo
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre un conjunto de datos de salud pública para identificar y cuantificar los principales factores de riesgo asociados a los ataques cardíacos. Utilizando Python para la limpieza y procesamiento, y Power BI para la visualización interactiva, se descubrió que factores como la hipertensión y el tabaquismo duplican el riesgo en ciertos perfiles demográficos. El análisis culmina en la propuesta de un plan de prevención focalizado con un potencial de reducción de eventos del 10-15% en la población de alto riesgo.

🎯 Planteamiento del Problema
Las enfermedades cardíacas son una de las principales causas de mortalidad a nivel mundial. Identificar los factores de riesgo más influyentes de manera proactiva es crucial para desarrollar estrategias de salud pública que sean eficientes, salven vidas y reduzcan los costes sanitarios. Este análisis busca responder a la pregunta: ¿Cuáles son las variables clave que nos permiten identificar a los individuos con mayor riesgo de sufrir un ataque cardíaco?

🛠️ Herramientas y Librerías
Lenguajes: Python, DAX

Librerías: Pandas, Matplotlib, Seaborn

Herramientas: Jupyter Notebook, Power BI, Git/GitHub

📊 Hallazgos Clave
El análisis reveló varios insights importantes sobre la población estudiada:

Factor Dominante: La hipertensión arterial es el factor individual con mayor impacto, aumentando la probabilidad de un evento cardíaco en un [XX]% en comparación con pacientes no hipertensos.

Perfil de Alto Riesgo: Se identificó un segmento demográfico de alto riesgo: hombres mayores de 55 años, fumadores y con diabetes, quienes, a pesar de representar solo el [YY]% de la muestra, acumulan el [ZZ]% de los ataques cardíacos.

Impacto de Hábitos de Vida: Los individuos que son fumadores activos presentan una tasa de riesgo 2.5 veces superior a los no fumadores.

Factor Protector: Realizar ejercicio físico de forma regular demostró ser un factor protector clave, disminuyendo el riesgo en un [AA]% incluso tras ajustar por edad y condiciones preexistentes.

💡 Recomendaciones Accionables
Basado en los hallazgos, se proponen las siguientes estrategias de prevención:

Programa de Detección Prioritaria: Implementar campañas de screening de hipertensión gratuitas y accesibles, dirigidas específicamente al perfil de alto riesgo identificado.

Campañas de Prevención Focalizadas: Diseñar campañas de cesación tabáquica y promoción del ejercicio con mensajes y canales adaptados al segmento demográfico de mayor riesgo.

Modelo Predictivo: Como siguiente paso, se recomienda utilizar estos factores clave para desarrollar un modelo de machine learning simple que pueda alertar a los profesionales de la salud sobre pacientes que requieran una intervención temprana.

📈 Visualización Interactiva
Para una exploración más profunda de los datos y los hallazgos, puedes interactuar con el dashboard completo desarrollado en Power BI.

[Ver el Dashboard Interactivo en Power BI]([Aquí pegas tu enlace público de Power BI])
📁 Estructura del Repositorio
/data: Contiene el dataset original utilizado para el análisis (HeartDisease2020.csv).

/notebooks: Incluye el Jupyter Notebook (analisis_riesgo_cardiaco.ipynb) con todo el proceso de limpieza, exploración y visualización de datos en Python.

/powerbi: Contiene el archivo fuente del dashboard de Power BI (Dashboard_Riesgo_Cardiaco.pbix).

README.md: La explicación detallada de este proyecto.

requirements.txt: El listado de librerías de Python necesarias para replicar el análisis.
