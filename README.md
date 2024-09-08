# TC3006C - Portafolio de Análisis

### Proyecto: Evaluación y Optimización de Modelos de Redes Neuronales

Este repositorio contiene el **Portafolio de Análisis** realizado para la materia de **Inteligencia Artificial Avanzada para la Ciencia de Datos I**. El propósito de este análisis es evaluar el rendimiento de distintos modelos de aprendizaje supervisado, incluyendo un perceptrón, una red neuronal básica y una red neuronal optimizada, aplicada al **Pima Indians Diabetes Dataset**.

Liga al portafolio de Implementación: https://github.com/Axel3246/TC3006C_Portafolio_Implementacion_Framework_A00829837

## Contenido del repositorio:
- **PortafolioAnálisis-A00829837.pdf**: Documento en formato PDF que detalla el análisis completo de los modelos, sus resultados, las métricas utilizadas, y las conclusiones obtenidas.

## Descripción del Análisis:
El análisis se enfoca en la evaluación de tres modelos distintos:
1. **Perceptrón**: Un modelo simple que mostró altos niveles de underfitting debido a su incapacidad para capturar relaciones no lineales entre las variables.
2. **Red Neuronal no Optimizada**: Modelo que mejoró el rendimiento respecto al perceptrón, pero presentó overfitting, lo que indica una mala capacidad de generalización.
3. **Red Neuronal Optimizada**: Aplicación de técnicas de regularización y ajuste de hiperparámetros como Dropout, Batch Normalization, Early Stopping y reducción de la tasa de aprendizaje, logrando un modelo balanceado con bajo bias y baja varianza.

## Conjunto de Datos:
El dataset utilizado es el **Pima Indians Diabetes Database**, disponible en [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database). Este dataset contiene 768 instancias y 8 features, siendo el objetivo predecir si un paciente padece diabetes o no.

## Estructura del Documento:
1. **Introducción**: Objetivos y descripción general del análisis.
2. **Separación de Datos**: Detalles sobre el conjunto de entrenamiento, validación y prueba.
3. **Evaluación del Perceptrón**: Análisis de su desempeño, bias y varianza.
4. **Evaluación de la Red Neuronal**: Análisis de su desempeño, bias y varianza.
5. **Optimización de la Red Neuronal**: Técnicas aplicadas y análisis de su desempeño, bias y varianza.
6. **Conclusión**: Comparación de los tres modelos y conclusiones generales sobre el mejor modelo.

## Conclusiones:
- La red neuronal optimizada mostró un mejor rendimiento general en comparación con los otros modelos, demostrando una buena capacidad de generalización gracias a las técnicas de regularización.
- El perceptrón y la red neuronal no optimizada sufrieron de underfitting y overfitting, respectivamente, demostrando la importancia de la correcta optimización de los modelos de machine learning.

## Referencias:
- UCI Machine Learning. (2016). Pima Indians Diabetes Database. Kaggle. Retrieved September 4, 2024, from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).
