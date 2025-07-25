# Análisis NLP de la Cohesión en Equipos de Trabajo

Este repositorio corresponde al proyecto de **Servicio Social 2024b-2025a**, desarrollado por:

-   **Autor:** Ignacio David Vázquez Pérez
-   **Padrón:** 20182928
-   **Carrera:** Ingeniería en Computación
-   **Asesora:** ADRIANA PENA PEREZ NEGRON

El objetivo principal de este proyecto es aplicar técnicas de **Procesamiento de Lenguaje Natural (NLP)** para analizar y comprender los factores que influyen en la **cohesión de los equipos de trabajo**, a partir de datos recopilados de profesionales del sector.

---

## Descripción de Archivos

A continuación se describe la estructura y contenido de los archivos principales del proyecto:

-   **`nlp_servicio_social.ipynb`**: Jupyter Notebook que contiene todo el código y la metodología del análisis NLP. Incluye la carga de datos, limpieza, preprocesamiento, análisis de frecuencia, visualizaciones y resumen de texto.

-   **`audios_escritos.xlsx` / `audios_escritos.csv`**: Fuentes de datos principales que contienen las transcripciones de las encuestas realizadas. Incluyen columnas con años de experiencia, empresa, puesto y respuestas abiertas sobre la cohesión en equipos de trabajo.

-   **`summarized_answers.csv`**: Archivo CSV con los resúmenes generados por un modelo de `transformers` para cada una de las preguntas de la encuesta.

| Columna | Resumen de Ejemplo |
|---|---|
| **Name** | Ramses Emmanuel Vazquez Galindo, Jose Antonio C... |
| **How many years of experience...** | 2, 3, 3.5, 1.6, 15 years |
| **What company do you work?** | SIAC SOFTWARE, SIAC, IBM, Oracle, Delaney... |
| **What is your position?** | JR developer, Software developer, Developer... |
| **What is the meaning of cohesion...** | Good team integration, teamwork that makes sense... |
| **APPOINTMENT A SITUATION THAT...** | Solving bugs, developing a project from scratch... |
| **There is some incident that...** | The lack of communication and organization... |

-   **`respuestas_d.docx`**: Documento de Word que contiene una recopilación adicional de respuestas sobre los factores que los profesionales consideran importantes para la cohesión.

-   **`output.csv`**: Versión procesada y estructurada de `respuestas_d.docx`, lista para ser analizada.

-   **`factors_summary_4.txt` / `factors_summary_5.txt`**: Archivos de texto plano que contienen los resúmenes generados sobre los factores clave para la cohesión, destacando la importancia de la comunicación, el liderazgo y la empatía.

-   **`reportes_bimestrales.docx`**: Documento utilizado para la elaboración de los informes de avance del servicio social.

---

## Resultados y Visualizaciones

El análisis produce diversas visualizaciones para interpretar los datos. A continuación se muestra una de las gráficas generadas.

-   **`output.png`**: Imagen que muestra una de las visualizaciones del análisis, como el siguiente gráfico de frecuencia de las frases más comunes relacionadas con la cohesión.

    ![Gráfico de Frecuencia de Palabras](https://github.com/nachovazquez98/servicio_social_inco_udg/blob/main/output.png?raw=true)
