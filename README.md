# 📈ConnetaTell-Analysis
Este repositorio contiene el análisis de datos registrados hasta el año 2024 de la empresa ConnectaTell, la cual opera en México y Colombia. Este análisis tiene el fin demostrar como los clientes usan realmente los servicios móviles (llamadas y mensajes), patrones de uso, comportamientos atípicos y la comprender que segmentos de clientes muestran necesidades con el fin de mejorar la experencia de usuario y oferta comercial. 

## 📋DATASETS UTILIZADOS
- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

## 📊ETAPAS DEL ANALISIS. 
 1. Cargar y explorar	Cargar y explorar plans, users_latam, usage.	Visión clara de la estructura y tipos de columna de cada dataset.
 2. Identificación de problemas de calidad. Contar nulos, detectar sentinels, revisar fechas fuera de rango. Lista priorizada de problemas que pueden sesgar decisiones.
 3. Limpieza básica	Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas.	Datos consistentes y listos para análisis estadístico.
 4. Summary statistics	Revisar las medidas clave en variables categóricas y numéricas.	Medidas clave (media, mediana, percentiles) que muestran el comportamiento típico y extremo.
 5. Visualización & outliers	Creación de histogramas y boxplots.	Visualización de sesgos, patrones de usuarios o datos atípicos.
 6. Segmentación	Crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots.	Segmentos accionables que permiten diseñar ofertas, campañas y migraciones de plan.
7. Insight ejecutivo. Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.	Responder a las preguntas del negocio y proponer acciones concretas.

## 🧩EJECUCION DEL NOTEBOOK.
Abre google colab o haz click en el siguiente enlace https://colab.research.google.com/drive/16-RMJZwSnNj-3Q-ZhGQ5GaLOIQfLXbOp?usp=sharing
o abre el notebook `.ipynb` en GitHub y abre el archivo en Colab.

## 📝GUIA DE REPRODUCCION. 
1. Abre `S7_Version_Estudiante_Project_ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)
