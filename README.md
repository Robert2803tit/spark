# Práctica Spark: Análisis de Movilidad Urbana

![Spark Logo](https://spark.apache.org/images/spark-logo-trademark.png)

Este proyecto aplica Apache Spark para analizar patrones de movilidad en la Ciudad de México utilizando datos abiertos. El análisis identifica rutas congestionadas, horarios pico y zonas de alta actividad ciclista.

## Objetivos del Proyecto

- Aplicar conceptos fundamentales de Spark (RDDs, DataFrames, transformaciones/acciones)
- Analizar datasets reales de movilidad urbana
- Identificar patrones de congestión y demanda de transporte
- Generar visualizaciones significativas de los resultados

## Tecnologías Utilizadas

- **Apache Spark 3.x**: Procesamiento distribuido de los datos
- **PySpark**: API de Python para Spark
- **Jupyter Notebook**: Ambiente interactivo para desarrollo y análisis
- **matplotlib**: Visualización de resultados
- **Datos abiertos CDMX**: Fuente de datos reales

## Estructura del Proyecto
/practica-spark-movilidad/
│
├── notebooks/
│ ├── analisis_paseos.ipynb # Notebook principal con el análisis
│ └── visualizaciones.ipynb # Generación de gráficos
│
├── data/
│ ├── paseos_dominicales_muevete_en_bici.csv # Dataset original
│ └── resultados_analisis/ # Outputs procesados
│
├── docs/
│ ├── informe_tecnico.pdf # Documentación detallada
│ └── referencias.md # Fuentes de datos y bibliografía
│
└── src/
└── funciones_utiles.py # Funciones auxiliares para el análisis


## Dataset Utilizado

El análisis utiliza datos del programa ["Muévete en Bici"](https://datos.cdmx.gob.mx/) de la CDMX, que contiene:

- Registros históricos de paseos dominicales
- Datos por edición del evento (fecha, asistencia)
- Variables simuladas (horario, zona geográfica)

## Cómo Ejecutar el Proyecto

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/practica-spark-movilidad.git
   cd practica-spark-movilidad 
