# Análisis de Municipios en Colombia

Este repositorio contiene el análisis de los municipios de Colombia utilizando datos de salud y servicios públicos a nivel municipal. El objetivo del proyecto es identificar patrones y segmentar los municipios para mejorar la planificación de políticas públicas.

## Estructura del Repositorio

- `/data`: Contiene los datos utilizados en el análisis. Incluye:
  - `PANEL_SALUD_Y_SERVICIOS.xlsx`: Datos originales descargados de Papyrus Datos.
  - `processed_data.csv`: Datos preprocesados listos para el análisis.
  
- `/scripts`: Contiene todos los scripts utilizados para el preprocesamiento, análisis y visualización de los datos.
  - `preprocessing.py`: Script para cargar y limpiar los datos.
  - `clustering_analysis.py`: Script para realizar el análisis de clustering.
  - `visualization.py`: Script para generar gráficos y visualizaciones.

- `/results`: Contiene los resultados preliminares del análisis.
  - `dendrogram.png`: Dendrograma generado por el análisis de clustering jerárquico.
  - `kmeans_clusters.png`: Gráfico de los clusters generados por K-means.
  - `dbscan_clusters.png`: Visualización de los clusters identificados por DBSCAN.

- `/document`: Contiene el documento de la entrega del proyecto.
  - `proyecto_final.docx`: Documento editable del proyecto.
  - `proyecto_final.pdf`: Documento final en PDF para la entrega.

## Cómo Ejecutar los Scripts

1. **Preprocesamiento de Datos**: Para preparar los datos para el análisis, ejecuta:
   ```bash
   python scripts/preprocessing.py
