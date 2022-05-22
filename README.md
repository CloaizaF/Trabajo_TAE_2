## Integrantes

- Camilo Loaiza Fonnegra
- Juan Pablo Rivera Sierra
- Eduardo Santos Ruiz
- Juan Diego Marin Rodriguez
- Ivan Andrés Velasco Arias


## Planteamiento del Problema

### Objetivo:

* Crear un modelo para predecir la probabilidad de que un individuo incumpla sus obligaciones financieras en los siguientes 12 meses a la fecha de originación de su crédito.

### Tipo de Problema:

* Problema de predicción de la probabilidad de que un individuo incumpla sus obligaciones financieras en los siguientes 12 meses a la fecha de originación de su crédito.

### Información Disponible:

* El insumo principal de este trabajo son los datos de las solicitudes de préstamo encontrados en [Loan_data_2007_2014](https://drive.google.com/file/d/1M0UVAKomoPEPjmzhxOYb3H_yyHRx_9dE/view) (466285 registros).

### Método de Machine Learning:

* Realización de dos modelos, uno de redes neuronales y otro de regresión logística. Ambos con el fin de realizar la predicción de riesgo de crédito.
    
    * Para la realización del modelo de redes neuronales se seleccionaron todas las características contenidas en el conjunto de datos debido a que esto permite una mejor rendimiento del modelo. 
    * Para la realización del modelo de regresión logística se seleccionaron 10 características utilizando el método RFE ya que su objetivo es seleccionar características considerando de forma recursiva conjuntos de características cada vez más pequeños.

### Evaluación de Métricas, Protocolo de Entrenamiento y Validación:

* accuracy, precision, recall, f1-score y support serán utilizados para evaluar el rendimiento predictivo de los modelos.
* 311832 registros de solicitudes de préstamo para entrenamiento y 153590 registros para validación. Se utilizó la misma partición para ambos modelos ya que se considero adecuada para ambos.

## Definiciones

* Se considerará que un cliente incumple sus obligaciones financieras si está en default o si tiene un atraso de más de 30 días en su pago.

## Análisis Descriptivo

## Flujo de Trabajo

A continuación se presenta el flujo de trabajo realizado: 

## Fuentes de Datos y Preprocesamiento

### Poblaciones:

### Registro de Muestra y Características de Medición:

### Recopilación de Datos:

### Estructuras de Datos y Tipos:

### Preprocesamiento de Datos:

### Link a la Información:

## Desarrollo de los Modelos y Validación

### Software Utilizado:

* Modelo realizado en [Google Collaboratory](https://www.google.com/url?q=https://colab.research.google.com/notebooks/welcome.ipynb?hl%3Des&sa=D&source=editors&ust=1651468799400076&usg=AOvVaw3BsmzIFA0LLERerLBE2zcG) con el lenguaje de programación Python utilizando la librería ...

### Entrenamiento y Validación de los Modelos:

### Características Seleccionadas y Entrada a los Modelos:

### Variable a Predecir y Salida de los Modelos:

### Método de Validación:

### Reproducibilidad y Reutilización del Código:

## Modelo en Producción

## Video Promocional

## Conclusiones 
