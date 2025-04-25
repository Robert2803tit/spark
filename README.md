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


2. **Configurar entorno (requiere Python 3.8+ y Spark)**:
   ```bash
   pip install pyspark matplotlib jupyter



3. **Ejecutar el análisis**
   Abrir el notebook principal:
   ```bash
   jupyter notebook notebooks/analisis de los paseos.ipynb

## Hallazgos Principales


**Patrones de congestión**:

Evento más concurrido: Edición 629 (115,728 participantes)

Zona Centro con mayor afluencia promedio

**Distribución horaria**:

Hora pico: 19:00 hrs (49,177 asistentes promedio)

Hora valle: 00:00 hrs (40,167 asistentes)

**Recomendaciones**:

Redistribución de recursos en zonas críticas

Optimización de horarios para eventos futuros


Documentación técnica detallada disponible en **Informe_spark.pdf** que esta en este repositorio





