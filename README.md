<img width="300" height="490" alt="popularidad" src="https://github.com/user-attachments/assets/0c368070-ae83-4a01-8af2-8bd1db7c6eb5" />
<img width="694" height="244" alt="pipeline_page-0001" src="https://github.com/user-attachments/assets/f19cc068-f3dc-4b5f-aacc-c1833b659ec4" />

# Análisis del sesgo de popularidad en reseñas turísticas mediante RoBERTa

## Descripción

Este repositorio contiene el código utilizado para el desarrollo de la investigación **"Análisis del sesgo de popularidad en las reseñas turísticas mediante técnicas de procesamiento del lenguaje natural"**.

El objetivo del estudio fue analizar la relación entre el nivel de popularidad de establecimientos turísticos y el sentimiento expresado en las reseñas de los usuarios mediante un modelo basado en la arquitectura **RoBERTa**.

## Contenido

- Carga y preparación del conjunto de datos.
- Generación de etiquetas de sentimiento.
- División de datos en entrenamiento y prueba.
- Tokenización mediante RoBERTa.
- Entrenamiento y evaluación del modelo.
- Clasificación automática de sentimientos.
- Análisis del sesgo de popularidad.
- Aplicación de la prueba estadística Chi-cuadrado.

## Conjunto de datos

El estudio utiliza el conjunto de datos **Yelp Restaurant Reviews Sentiment Dataset**, disponible en Zenodo:

https://doi.org/10.5281/zenodo.18723813

## Modelo utilizado

Se empleó el modelo **RoBERTa-base** para la clasificación automática de sentimientos.

Referencia:

Liu, Y., Ott, M., Goyal, N., et al. (2019). *RoBERTa: A Robustly Optimized BERT Pretraining Approach*. arXiv:1907.11692.

## Requisitos

- Python 3.10+
- pandas
- numpy
- scikit-learn
- transformers
- datasets
- evaluate
- accelerate
- torch
- scipy

## Ejecución

1. Descargar el conjunto de datos.
2. Colocar el archivo `yelp_sentiment_master_dataset.csv` en el mismo directorio del script.
3. Ejecutar el código principal.

## Autor

Magbis Mizraim Santiago López, Martha Patricia Soriano Mosqueira

Universidad Politécnica de Altamira

Programa Delfín 2026

Universidad Tecnológica de Bolívar, Cartagena Colombia
