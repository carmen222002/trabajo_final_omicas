# trabajo_final_omicas_2025

**ANÁLISIS DE BULK-RNA-SEQ**

Este repositorio contiene el análisis de datos de secuenciación de ARN (Bulk RNA-seq) basado en el conjunto de datos GSE111003, con normalización, análisis multivariante, análisis de expresión diferencial y análisis de enriquecimiento.

📁 **Estructura del repositorio**

Bulk-RNA-seq
- data
    - GSE111003_RAW/ # Datos crudos obtenidos de GEO 
- src # Funciones auxiliares para el análisis 
- analisis_RNA-seq.Rmd # Análisis de la matriz de expresión 
- analisis_RNA-seq.pdf # Explicación detallada del análisis

📥 **Datos**

Los datos utilizados en este análisis provienen de GSE111003, un conjunto de datos de muestras individualizadas de un artículo publicado en Proceedings of the National Academy of Sciences (DOI: 10.1073/pnas.2102698118).

📊 **Análisis realizado**

- Construcción de la matriz de expresión a partir de los datos crudos.

- Normalización de los datos para minimizar sesgos técnicos.

- Análisis multivariante:

  - PCA (Análisis de Componentes Principales)

  - Matriz de correlaciones y distancias

- Análisis de expresión diferencial usando el modelo limma para identificar genes regulados diferencialmente.

- Análisis de enriquecimiento mediante el análisis de sobrerrepresentación para interpretar los resultados biológicamente.

🚀 **Uso**

- Clonar este repositorio: git clone https://github.com/carmen222002/Bulk-RNA-seq.git cd Bulk-RNA-seq

- Asegurar que tienes R y RStudio instalados.

- Instalar paquetes necesarios ejecutando el código dentro de analisis_RNA-seq.Rmd.

- Ejecutar el análisis en R Markdown para obtener los resultados.

📄 **Referencias**

GSE111003 - NCBI GEO: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE111003

Artículo original: https://www.pnas.org/doi/10.1073/pnas.2102698118
