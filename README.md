# Detección de Retinopatía Diabética
Trabajo final del Máster en Ciencia de Datos (UOC)

Este repositorio contiene los códigos implementados para detectar el grado de retinopatía diabética (RD) en imágenes de fondo de ojo. Los datos han sido descargados directamente a través de estas urls: https://www.kaggle.com/c/aptos2019-blindness-detection/data y https://www.kaggle.com/datasets/valmmm/aptos2015

Las imágenes están clasificadas en cinco clases distintas que corresponden a: 

0 - Sin RD

1 - RD leve

2 - RD moderada

3 - RD grave

4 - RD proliferativa

Las carpetas que contiene este repositorio son las siguientes:

- Preprocesamiento: Contiene el código de procesado de imágenes aplicado sobre el conjunto de APTOS 2015 y APTOS 2019. 
- Evaluación de modelos: Contiene modelos preentrenados usados para entrenar las imágenes y la comparativa de los resultados
- Optimización: Contiene la implementación de varios entrenamientos con varias opciones de hiperparámetros para optimizar el modelo 
- Entrenamiento y validación: Contiene los algoritmos de los modelos finales, con varias opciones de mejora en búsqueda de una mejor accuracy
- Pruebas: Código para probar de detectar RD en imágenes tomadas con dispositivos móviles, usando el modelo con mejores resultados.

Todos los códigos han sido desarrollados con Python 3.0, a través de Jupyter Notebook. 
