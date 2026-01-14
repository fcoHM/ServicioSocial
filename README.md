# Servicio Social – Comparativa de Modelos de Visión Computacional para Detección de Contaminantes en Cosechas de Chile 🌶️

Este repositorio contiene el desarrollo de mi **servicio social**, cuyo objetivo es realizar una **comparativa de modelos de visión computacional para detección de objetos**, aplicados a la **detección de contaminantes en cosechas de chile**.

El proyecto evalúa el desempeño de distintas arquitecturas de **detección de objetos**, utilizando un **dataset proporcionado por una escuela colaboradora**, con el fin de identificar qué modelo ofrece mejores resultados para este problema específico.

---

## Objetivo

- Detectar la **presencia de contaminantes** en imágenes de cosechas de chile.
- Localizar los contaminantes dentro de la imagen.
- Comparar distintos **modelos de detección de objetos**.
- Evaluar el efecto del ajuste de hiperparámetros.

---

## Metodología

Se utiliza la metodología **CRISP-DM**, aplicada de forma experimental:

1. Comprensión del problema  
2. Comprensión de los datos  
3. Preparación de los datos  
4. Modelado  
5. Evaluación  
6. Documentación de resultados  

---

## Dataset

- Imágenes de cosechas de chile  
- Múltiples instancias por imagen  
- Uso académico  

---

## Enfoque del Problema

El problema se aborda como **detección de objetos**, no como clasificación.  
El objetivo es identificar **si existen contaminantes y su ubicación** dentro de la imagen.

---

## Modelos de Detección Evaluados

Los modelos evaluados en este repositorio son:

- **YOLO**
- **Faster R-CNN**
- **SSD**
- **RetinaNet**
- **EfficientDet**

Los siguientes modelos forman parte del trabajo realizado por mi compañero en un [repositorio](https://github.com/JaimeRob23/Servicio_Social) independiente:

- **DETR**
- **Deformable DETR**
- **FCOS**
- **CenterNet**
- **Mask R-CNN**

---

## Ajuste de Hiperparámetros

- Learning rate  
- Batch size  
- Número de epochs  
- Tamaño de imagen de entrada  

---

## Métricas de Evaluación

Para validar el desempeño de los modelos de **detección de objetos**, se utilizan las siguientes métricas:

- **IoU (Intersection over Union)**  
  Mide qué tan bien se ajusta la caja detectada por el modelo a la caja real del objeto.  
  Un valor más alto indica una mejor localización.

- **Precision**  
  Indica qué porcentaje de las detecciones realizadas por el modelo son correctas.  
  Ayuda a medir la cantidad de falsas detecciones.

- **Recall**  
  Indica qué porcentaje de los objetos reales fueron detectados por el modelo.  
  Mide la capacidad del modelo para encontrar todos los objetos presentes.

- **mAP (mean Average Precision)**  
  Es la métrica principal en detección de objetos.  
  Resume el desempeño general del modelo combinando precisión, recall y calidad de localización.

Estas métricas permiten comparar objetivamente los distintos modelos evaluados.

---

## Autores

**José Francisco Hurtado Muro**  
Ingeniería de Software – Universidad Autónoma de Zacatecas  

**Jaime Gabriel Robles Felix**  
Ingeniería de Software – Universidad Autónoma de Zacatecas  
