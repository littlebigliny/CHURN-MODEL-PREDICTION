# CHURN MODEL PREDICTION

![Intro](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/1.jpg) 


## Descripción del Proyecto 

En el dinámico sector de las telecomunicaciones, la pérdida de clientes, mejor conocida como **churn**, representa una significativa amenaza para la sostenibilidad financiera.  
Este proyecto utiliza y compara **técnicas de Machine Learning** para predecir qué clientes tienen mayor probabilidad de abandonar el servicio, permitiendo a las empresas anticiparse y diseñar estrategias de retención personalizadas. Esto es de suma importancia, puesto que se ha visto que incluso pequeñas mejoras en la tasa de retención se traducen en incrementos sustanciales en ingresos. Nuestra solución ayuda a optimizar la toma de decisiones basada en datos, enfocándose en preservar el valor del cliente a largo plazo.

Durante la lectura de nuestro proyecto, podrán palpar cómo implementar un modelo predictivo de churn **reduce costos, mejora la fidelización y maximiza ingresos de la empresa**.

![Descripcion](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0008.jpg)

---

## Metodología del modelado
1. **Análisis Exploratorio de Datos (EDA)**  
Eliminación de aquellas variables que no ofrecen comportamientos nuevos en el análisis, se eliminan también aquellas variables que no deben ser tomadas en el análisis de acuerdo a lo mencionado en el archivo 'churn_dictionary'.

Las variables eliminadas por indicación del documento son:

*   Satisfaction Score
*   Customer Status
*   Churn Category
*   Churn Reason
*   Churn Score
*   Churn Label

Durante el proceso de data cleaning, también se realizó imputación de valores faltantes y selección de características clave.

2. **Modelado Predictivo**

Fueron utilizados los siguientes modelos predictivos:

   - **XGBoost**  
   - **LightGBM (LGBM)**  
   - **Regresión Logística**  

Todos nuestros modelos de Machine Learning fueron balanceados mediante técnicas como **SMOTE** y optimizados con **GridSearchCV** o **RandomizedSearchCV**. En esta imagen, pueden apreciar el modelo escogido y sus features.

![ModeladoRL](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0018.jpg)

3. **Evaluación**  
   Priorizamos la métrica de evaluación **Recall** para poder detectar la mayor cantidad de churners posibles, minimizando el riesgo de fuga de clientes no detectados.
   Esta decisión fue también tomada en base a muchos estudios que priorizan esta variable durante las predicciones de churn (Customer churn prediction - Francisco Lucio S. Bustamante, Customer churn prediction - Classification Models in Machine Learning)

---

## Resultados

**Impacto Económico Estimado**  
- **XGBoost**: Ahorro neto de **$34,000**  
- **LightGBM**: Ahorro neto de **$234,200**  
- **Regresión Logística**: Ahorro neto de **$272,400**

Con un recall de **80% para churners**, logramos anticipar la mayoría de las bajas, generando oportunidades de intervención proactiva.

> *"Cada cliente salvado es una victoria estratégica para el negocio."*


---

## Implementación en el Negocio

- Integración del modelo en sistemas **CRM** para monitoreo semanal del comportamiento de nuestros clientes.
- Clasificación automática de clientes en riesgo.
- Disparadores de campañas personalizadas (descuentos, llamadas, promociones).
- Monitoreo continuo del desempeño del modelo.

![Implementacion](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0034.jpg)

---
## Límites del modelo

La regresión logística asume una **relación lineal** entre las variables independientes y el logaritmo de las probabilidades. Los factores que determinan la diserción del cliente (churn) pueden interactuar de forma no lineal. Este tipo de relaciones no lineales entre variables podrían ser mejor capturadas por modelos como redes neuronales o árboles de decisión. 

Así mismo, el proceso de balanceo de clases mediante técnicas como SMOTE, utilizada en este modelado, requiere una **rigurosa calidad del preprocesamiento** de los datos presentes en el dataset. Si procesados de manera incorrecta, nos arriesgamos a que nuestro modelado aprenda errores o ruido, creando así muestra sintéticas poco representativas de nuestro dataset.

---

## Futuro del proyecto

Nuestro equipo propone:
- **Reentrenamiento trimestral** del modelo para adaptarse a nuevas dinámicas del cliente pues, como sabemos, los datos no siempre son lineares en el tiempo.
- Incorporación de **nuevas variables** de comportamiento y satisfacción.
- Desarrollo de nuevos **modelos sensibles al costo** para maximizar el retorno económico.
  
![Futuro](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0041.jpg)

---


##  Conclusiones y recomendaciones 

Se recomiendan 3 puntos cardinales:
* Integración con campañas personalizadas
* Comparación de múltiples modelos para optimizar su funcionalidad
* Preprocesamiento riguroso de los datos

**CHURN MODEL PREDICTION** es un modelo que no sólo identifica clientes en riesgo de cometer churn, su fin principal, sino que también se convierte en una herramienta estratégica para fidelizar usuarios y asegurar la competitividad de la empresa en un mercado cada vez más exigente.
La retención de nuestros clientes debe ser prioritaria, enfocándose en estrategias de fidelización temprana y ofertas personalizadas que reduzcan la percepción del costo y aumenten su compromiso.

---

# 👩‍💻 Autores

- [@sampvela](https://github.com/sampvela)
- [@Stefania2025](https://github.com/Stefania2025)
- [@alecruzmonge](https://github.com/alecruzmonge)
- [@littlebigliny](https://github.com/littlebigliny)
