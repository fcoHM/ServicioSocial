# Servicio Social – Comparativa de Modelos de Visión Computacional para Clasificación de Contaminantes en Cosechas de Chile 🌶️

Este repositorio contiene el desarrollo de mi **servicio social**, cuyo objetivo es realizar una **comparativa de distintos modelos de visión por computadora** aplicados a la **clasificación de contaminantes en cosechas de chile**.

El proyecto evalúa el desempeño de múltiples arquitecturas de **deep learning para clasificación de imágenes**, utilizando un **dataset proporcionado por una escuela colaboradora**, con el fin de determinar qué modelo resulta más eficaz para esta tarea agrícola específica.

---

## Objetivo del Proyecto

- Evaluar y comparar diferentes modelos de **clasificación de imágenes**.
- Analizar el impacto del **ajuste de hiperparámetros** en el desempeño de cada modelo.
- Determinar la arquitectura más adecuada para la detección de contaminantes en cosechas de chile.
- Documentar los resultados de forma **reproducible y estructurada**.

---

## Metodología

El proyecto se desarrolla siguiendo la metodología **CRISP-DM (Cross Industry Standard Process for Data Mining)**, la cual permite un enfoque iterativo y experimental adecuado para proyectos de visión computacional.

Las fases aplicadas son:

1. **Comprensión del problema**
2. **Comprensión de los datos**
3. **Preparación de los datos**
4. **Modelado**
5. **Evaluación**
6. **Documentación de resultados**

---

## Dataset

- Tipo: Imágenes de cosechas de chile
- Etiquetas: Presencia de distintos tipos de contaminantes
- Origen: Escuela colaboradora
- Uso: Exclusivamente académico y de investigación


---

## Modelos de Clasificación Utilizados

En este proyecto se emplean modelos disponibles en librerías oficiales de visión computacional, con y sin pesos preentrenados.  
Los modelos evaluados incluyen:

- **AlexNet**
- **ConvNeXt**
- **DenseNet**
- **EfficientNet**
- **EfficientNetV2**
- **GoogLeNet**
- **Inception V3**
- **MaxVit**
- **MNASNet**
- **MobileNet V2**
- **MobileNet V3**
- **RegNet**
- **ResNet**
- **ResNeXt**
- **ShuffleNet V2**
- **SqueezeNet**
- **Swin Transformer**
- **VGG**
- **Vision Transformer (ViT)**
- **Wide ResNet**

Estos modelos permiten comparar arquitecturas:
- Convolucionales clásicas
- Redes profundas modernas
- Modelos ligeros para dispositivos con recursos limitados
- Transformers aplicados a visión computacional

---

## Ajuste de Hiperparámetros

Para cada modelo se experimenta con distintos hiperparámetros, tales como:

- Learning rate
- Batch size
- Número de epochs
- Optimizador
- Tamaño de imagen de entrada

El objetivo es analizar cómo estos parámetros influyen en el rendimiento del modelo.

---

## Métricas de Evaluación

El desempeño de los modelos se evalúa mediante métricas estándar de clasificación:

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión
- Curvas de entrenamiento (loss y accuracy)

Estas métricas permiten una comparación objetiva entre las arquitecturas evaluadas.

---

## Resultados

Los resultados obtenidos se documentan mediante:
- Tablas comparativas de métricas
- Gráficas de entrenamiento
- Análisis cualitativo y cuantitativo

El modelo con mejor desempeño será propuesto como la solución más adecuada para el problema planteado.

---

## Tecnologías Utilizadas

- Python
- PyTorch / TorchVision
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Consideraciones Finales

Este proyecto tiene fines **académicos** y forma parte del cumplimiento del servicio social.  
Los resultados obtenidos pueden servir como base para futuras investigaciones en el área de **agricultura inteligente y visión por computadora**.

---

## Autor

**José Francisco Hurtado Muro** 
Ingeniería de Software  
Universidad Autónoma de Zacatecas

**Jaime Gabriel Robles Felix** 
Ingeniería de Software  
Universidad Autónoma de Zacatecas  

