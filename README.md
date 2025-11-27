🏡 Análisis y Predicción de Financiamientos de Vivienda en México (2023–2025)

Aplicación desarrollada en Streamlit para analizar y predecir el volumen de financiamientos de vivienda en México mediante visualizaciones interactivas, análisis exploratorio y modelos de Machine Learning (Regresión Lineal y Random Forest).
Incluye dashboard, análisis por entidad, organismo, destino, perfil del acreditado y proyecciones para meses futuros.

📌 1. Objetivo del proyecto

Desarrollar una solución analítica completa basada en datos reales de financiamientos de vivienda en México, capaz de:

Describir el comportamiento por año, entidad, organismo, destino y tipo.

Analizar características del acreditado (sexo, ingresos, clasificación de vivienda).

Detectar tendencias y patrones históricos.

Predecir el volumen mensual de financiamientos hacia 2025.

Comunicar hallazgos de forma ejecutiva.

📂 2. Estructura del repositorio
📁 proyecto-financiamientos
├── project_vivienda.py       # Código principal Streamlit
├── data/
│   ├── financiamiento_2023.csv
│   ├── financiamiento_2024.csv
│   └── financiamiento_2025.csv
├── README.md
└── requirements.txt


⚠️ Los archivos del dataset no se incluyen públicamente si contienen datos sensibles.
Puedes sustituirlos con tus propias fuentes (SNIIV / SEDATU / bancos / Estados).

🚀 3. ¿Cómo ejecutar el proyecto?
1) Instala dependencias
pip install -r requirements.txt

2) Ejecuta la app en Streamlit
streamlit run project_vivienda.py

3) Abre el navegador

Normalmente se abrirá en:

http://localhost:8501

🧩 4. Funcionalidades principales
🏠 Inicio

Resumen del proyecto

KPIs principales

Vista previa del dataset

📊 Análisis Exploratorio

Incluye tres secciones:

📅 Periodos

Monto total por año

Número de créditos por año

Evolución mensual por año

Comparativa 2023–2025

🏙️ Entidades y Organismos

Filtros globales:

Año

Organismo

Destino

Visualizaciones:

Top 15 entidades y organismos (sin filtros)

Mapas choropleth por:

Volumen por entidad

Monto total por entidad

Gráficas por organismo y año (volumen y monto total)

👤 Perfil del acreditado

Filtros globales:

Año

Tipo de financiamiento

Destino

Análisis:

Distribución por sexo

Distribución por ingresos (incluye nota UMA 2023–2025)

Monto por clasificación de valor de la vivienda

Relación destino vs tipo de financiamiento

📉 5. Predicción de Volumen

Modelos utilizados:

Regresión Lineal

Random Forest Regressor

Incluye:

Entrenamiento y evaluación

Métricas comparativas (RMSE, R², MAE)

Tabla e interpretación de coeficientes

Gráfica Real vs Predicho

Proyección futura de 1 a 12 meses

Gráfica integrada de histórico vs predicción

🤖 6. Tecnologías utilizadas

Python 3.8+

Streamlit – interfaz interactiva

Pandas – manipulación de datos

Plotly Express – visualizaciones dinámicas

Scikit-learn – modelos de Machine Learning

Requests – carga de GeoJSON para mapas

📈 7. Resultados principales (resumen)

Se identifican variaciones significativas entre organismos y destinos.

Las entidades con mayor volumen histórico mantienen tendencias estables.

El Random Forest presenta mejor desempeño predictivo que la Regresión Lineal.

La proyección muestra continuidad en el crecimiento moderado de financiamientos en 2025.

🎥 8. Video de presentación (elevator pitch)

Incluye aquí tu enlace a YouTube, Vimeo o TikTok cuando lo tengas.

📝 9. Autor

Karla Pérez
Proyecto final · Maestría / Ciencia de Datos

📄 10. Licencia

Este proyecto se distribuye bajo la licencia MIT. Puedes usarlo, modificarlo y adaptarlo libremente.
