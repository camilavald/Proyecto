# Análisis de Municipios en Colombia

Este repositorio contiene el análisis de los municipios de Colombia utilizando datos de salud y servicios públicos a nivel municipal. El objetivo del proyecto es identificar patrones y segmentar los municipios para mejorar la planificación de políticas públicas.

## Estructura del Repositorio

- `/data`: Contiene los datos utilizados en el análisis. Incluye:
  - `PANEL_SALUD_Y_SERVICIOS.xlsx`: Datos originales descargados de Papyrus Datos.
  - `processed_data.csv`: Datos preprocesados listos para el análisis.
  
- `/scripts`: Contiene todos los scripts utilizados para el preprocesamiento y análisis de clustering. 
  - `clustering_analysis.ipynb`: Script para realizar el análisis de clustering con diferentes algoritmos (K-means, DBSCAN, GMM).

- `/results`: Contiene los resultados generados por los algoritmos de clustering.
  - `clustered_data.csv`: Resultados del clustering jerárquico, K-means, DBSCAN y GMM.
  - `dbscan_cluster_distribution.png`: Distribución de los clusters identificados por DBSCAN.
  - `dbscan_clustered_data.csv`: Resultados del clustering de DBSCAN.
  - `dbscan_clusters.png`: Visualización de los clusters identificados por DBSCAN.
  - `dbscan_clusters_final.png`: Visualización final de los clusters de DBSCAN.
  - `dendrogram.png`: Dendrograma generado por el análisis de clustering jerárquico.
  - `gmm_clustered_data.csv`: Resultados del clustering con GMM.
  - `gmm_clusters.png`: Gráfico de los clusters generados por GMM.
  - `kdistances.png`: Gráfico de distancias para determinar el parámetro óptimo de DBSCAN.
  - `kmeans_cluster_distribution.png`: Distribución de los clusters generados por K-means.
  - `kmeans_clusters.png`: Visualización de los clusters generados por K-means.

- `/document`: Contiene el documento final del proyecto.
  - `Segmentación de Municipios en Colombia según Acceso a Servicios Públicos y Variables de Salud.docx`: Documento editable del proyecto.
  - `Segmentación de Municipios en Colombia según Acceso a Servicios Públicos y Variables de Salud.pdf`: Documento final en formato PDF.

## Cómo Ejecutar los Scripts

1. **Preprocesamiento de Datos**: Para preparar los datos para el análisis, ejecuta:
   ```bash
   python scripts/clustering_analysis.ipynb
