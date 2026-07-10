# Análisis Exploratorio de Datos - Proyecto Piana

## Descripción del proyecto

Proyecto de análisis exploratorio de datos desarrollado en Python utilizando información de costos y compras de la empresa Constructora V y Q.

El dataset contiene registros relacionados con gastos de obra, proveedores, componentes, fases y montos ejecutados, permitiendo analizar el comportamiento de los costos y obtener información relevante para la gestión.

## Objetivo del análisis

Realizar un análisis exploratorio y consultas SQL sobre la información de costos y compras de Constructora V y Q, con el fin de evaluar la calidad de los datos, identificar patrones de comportamiento y generar información mediante análisis estadístico y visualizaciones.

## Fuente del dataset

Dataset interno proporcionado por la empresa Constructora V y Q.

*(No aplica enlace a Kaggle debido a que corresponde a información propia de la empresa.)*

## Etapas realizadas

El análisis contempla las siguientes etapas:

- **Carga de datos:** Importación del archivo Excel mediante Python y preparación inicial del dataset.
- **Exploración inicial (EDA):**
  - Revisión de estructura de datos.
  - Análisis de dimensiones del dataset.
  - Revisión de columnas y tipos de datos.
  - Identificación de valores faltantes e inconsistencias.
- **Análisis estadístico:**
  - Estadística descriptiva de variables numéricas y categóricas.
  - Identificación de distribuciones y principales características de los datos.
- **Visualizaciones:**
  - Generación de gráficos para analizar tendencias, distribución de costos y comportamiento de variables relevantes.
- **Consultas SQL con DuckDB:**
  - Ejecución de consultas SQL sobre el DataFrame utilizando DuckDB.
  - Consultas realizadas:
    - Inspección inicial de datos mediante `SELECT` y `LIMIT`.
    - Filtrado de información utilizando `WHERE`.
    - Agrupaciones y cálculos mediante `GROUP BY` y funciones de agregación.
    - Ranking y priorización mediante `ORDER BY`.
    - Consultas combinadas con condiciones, cálculos y agrupaciones.

## Tecnologías utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Duckdb
- Github
- -Plotly

## Ejecución del notebook

Para ejecutar el proyecto:

1. Descargar el archivo `.ipynb`.
2. Abrirlo mediante Google Colab.
3. Cargar el archivo Excel utilizado como fuente de datos.
4. Ejecutar las celdas del notebook en orden.

## Archivo principal

- `notebook_analisis_sql_python_constructora.ipynb`
