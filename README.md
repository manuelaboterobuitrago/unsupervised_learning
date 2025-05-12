# Segmentación de Clientes con aprendizaje no supervisado

Este proyecto aplica técnicas de **aprendizaje no supervisado** para segmentar clientes en grupos con características similares. 
Se utiliza **PCA** para reducción de dimensionalidad y **K-Means** para identificar patrones en los datos.

## 📂 Dataset

El conjunto de datos fue obtenido de Kaggle y contiene 4 variables numéricas:
CustomerID: Identificador único del cliente.
Genre: Género del cliente (Male/Female).
Age: Edad del cliente.
Annual Income (k$): Ingreso anual en miles de dólares.
Spending Score (1-100): Puntuación de gasto del cliente (1-100).

El dataset fue limpiado previamente: no contiene valores nulos ni categorías no numéricas.


## 🧪 Técnicas aplicadas

- **Estandarización** con `StandardScaler`
- **Análisis de Componentes Principales (PCA)**
- **Selección de variables** mediante análisis de correlación
- **K-Means clustering**
- Visualización con gráficos de dispersión, scree plot, elbow plot y silhouette score

## 📈 Resultados

- El mejor agrupamiento se logró usando el dataset original con **K=5** clusters.
- El **Silhouette Score** fue de **0.55**, lo que indica una buena cohesión interna y separación entre los grupos.
- Se observaron segmentos distintos de clientes:
  - Jóvenes con gasto alto y bajo ingreso.
  - Adultos con ingresos altos pero bajo gasto.
  - Otros grupos con combinaciones específicas de edad, ingreso y consumo.
 -Este trabajo demuestra cómo el aprendizaje no supervisado permite segmentar poblaciones sin etiquetas previas, revelando patrones valiosos para la toma de decisiones, como el diseño de campañas o estrategias comerciales.

## 👤 Autor
Manuela Botero Buitrago
