# AI Data Engineering Pipeline

Proyecto de ingeniería de datos e inteligencia artificial para construir pipelines
batch reproducibles, transformar información en Snowflake y habilitar experiencias
de consulta y enriquecimiento con modelos de lenguaje.

## Tecnologías

- **Amazon S3**: almacenamiento de objetos para datos crudos, intermedios y
  procesados.
- **AWS IAM**: gestión de identidades, roles y permisos de acceso a los recursos
  de AWS.
- **Snowflake**: data warehouse para almacenar, modelar y consultar los datos
  analíticos.
- **dbt**: transformación SQL, modelado dimensional, documentación y pruebas de
  calidad de datos.
- **Python**: desarrollo de extractores, transformaciones, utilidades y lógica de
  enriquecimiento.
- **Apache Airflow**: orquestación, calendarización, dependencias, reintentos y
  monitoreo de los workflows.
- **Docker**: empaquetado y ejecución reproducible de los componentes del
  pipeline.
- **Streamlit**: interfaz web para explorar los datos y consumir las capacidades
  analíticas y de IA.
- **Batch pipelines**: procesamiento por lotes de grandes volúmenes de datos de
  forma programada y trazable.
- **Medallion architecture**: organización de los datos en capas **Bronze**,
  **Silver** y **Gold**.
- **LLM enrichment**: enriquecimiento de registros mediante modelos de lenguaje,
  por ejemplo extracción de entidades, clasificación, resumen y generación de
  metadatos.
- **RAG (Retrieval-Augmented Generation)**: recuperación de contexto relevante
  desde los datos para mejorar las respuestas del modelo de lenguaje.
- **Text-to-SQL**: conversión de preguntas en lenguaje natural a consultas SQL
  para facilitar el acceso autoservicio a la información.

## Objetivos

- Centralizar y gobernar datos de múltiples fuentes.
- Mantener pipelines reproducibles, automatizados y observables.
- Separar claramente la ingesta, transformación y presentación de los datos.
- Aplicar controles de acceso mediante IAM.
- Facilitar el análisis mediante consultas SQL y lenguaje natural.
- Incorporar capacidades de IA sin perder trazabilidad sobre los datos utilizados.