# Landing-Page-A-B-Experiment-Analysis
Este repositorio contiene el análisis de un experimento A/B realizado sobre una página de inicio (landing page), con dos versiones — A y B — expuestas a distintos usuarios, con el objetivo de apoyar una decisión de negocio basada en datos.
El dataset landing_experiment.csv incluye información de usuarios expuestos al experimento: región, dispositivo, fuente de tráfico, tipo de usuario, conversión y gasto.

📂 Contenido del repositorio
notebooks/landing_experiment_analysis.ipynb → Notebook principal con carga y validación de datos, pruebas estadísticas (t de Student, z de proporciones, chi-cuadrado), visualizaciones y conclusiones ejecutivas.
▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

Open In Colab

O:

Abre el archivo .ipynb en GitHub
Haz clic en Open in Colab
📘 Cómo reproducir el análisis
Abre notebooks/landing_experiment_analysis.ipynb
Ejecuta las celdas en orden
El notebook carga automáticamente el dataset desde /datasets/landing_experiment.csv (o desde un enlace público, según corresponda)
🧠 Objetivo del análisis
Validar la calidad e integridad de los datos del experimento
Comparar el gasto promedio por usuario convertido entre las páginas A y B
Comparar la tasa de conversión entre las páginas A y B
Analizar la relación entre la fuente de tráfico y la conversión
Analizar la relación entre el tipo de usuario y la conversión
Generar un insight ejecutivo con recomendaciones accionables para el negocio
📊 Métodos estadísticos utilizados
Prueba t de Student (gasto promedio A vs B)
Prueba z de proporciones (tasa de conversión A vs B)
Prueba chi-cuadrado de independencia (fuente de tráfico y tipo de usuario vs conversión)
🌟 Hallazgos principales
La Página B tiene un gasto promedio por usuario convertido significativamente mayor que la Página A.
La Página B convierte a una mayor proporción de usuarios (15.96%) que la Página A (12.57%).
La conversión muestra una asociación significativa (aunque débil) con la fuente de tráfico: Email y Ads convierten mejor en tasa que Organic y Referral.
No hay evidencia de que la conversión dependa del tipo de usuario (nuevo vs recurrente).
