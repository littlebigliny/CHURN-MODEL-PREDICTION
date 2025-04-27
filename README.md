# CHURN MODEL PREDICTION

![Intro](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/1.jpg) 


## Descripción del Proyecto 
![Descripcion](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0008.jpg)
En el dinámico sector de las telecomunicaciones, la pérdida de clientes, mejor conocida como **churn**, representa una significativa amenaza para la sostenibilidad financiera.  
Este proyecto utiliza y compara **técnicas de Machine Learning** para predecir qué clientes tienen mayor probabilidad de abandonar el servicio, permitiendo a las empresas anticiparse y diseñar estrategias de retención personalizadas. Esto es de suma importancia, puesto que se ha visto que incluso pequeñas mejoras en la tasa de retención se traducen en incrementos sustanciales en ingresos. Nuestra solución ayuda a optimizar la toma de decisiones basada en datos, enfocándose en preservar el valor del cliente a largo plazo.
Durante la lectura de nuestro proyecto, podrán palpar cómo implementar un modelo predictivo de churn **reduce costos, mejora la fidelización y maximiza ingresos de la empresa**.

---

## Metodología del modelado
1. **Análisis Exploratorio de Datos (EDA)**  
   Eliminación de columnas redundantes, imputación de valores faltantes, y selección de características clave.

2. **Modelos Predictivos Utilizados**

![Descripcion](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0018.jpg)
   - **XGBoost**  
   - **LightGBM (LGBM)**  
   - **Regresión Logística**  
   Todos balanceados mediante técnicas como **SMOTE** y optimizados con **GridSearchCV** o **RandomizedSearchCV**. En esta imagen, pueden apreciar el modelo escogido y sus métricas.

3. **Evaluación**  
   Priorizamos **Recall** para capturar la mayor cantidad de churners posibles, minimizando el riesgo de fuga de clientes no detectados.

---

## Resultados
![Resultados](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0020.jpg)

**Impacto Económico Estimado**  
- XGBoost: Ahorro neto de **$34,000**  
- LightGBM: Ahorro neto de **$234,200**  
- Regresión Logística: Ahorro neto de **$272,400**

Con un recall de **80% para churners**, logramos anticipar la mayoría de las bajas, generando oportunidades de intervención proactiva.

> *"Cada cliente salvado es una victoria estratégica para el negocio."*

---

## Implementación en el Negocio
![Implementacion](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0034.jpg)
- Integración del modelo en sistemas **CRM** para monitoreo semanal del comportamiento de nuestros clientes.
- Clasificación automática de clientes en riesgo.
- Disparadores de campañas personalizadas (descuentos, llamadas, promociones).
- Monitoreo continuo del desempeño del modelo.


---

## Futuro del proyecto
![Futuro](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0041.jpg)

Nuestro equipo propone:
- Reentrenamiento trimestral del modelo para adaptarse a nuevas dinámicas del cliente pues, como sabemos, los datos no siempre son lineares en el tiempo.
- Incorporación de nuevas variables de comportamiento y satisfacción.
- Desarrollo de nuevos modelos sensibles al costo para maximizar el retorno económico.

---



## ** Conclusión **
![Conclusion](https://github.com/littlebigliny/CHURN-MODEL-PREDICTION/blob/main/proyectofinalgit_page-0039.jpg)
**CHURN MODEL PREDICTION** es un modelo que no sólo identifica clientes en riesgo de cometer churn, su fin principal, sino que también se convierte en una herramienta estratégica para fidelizar usuarios y asegurar la competitividad de la empresa en un mercado cada vez más exigente.

---

# 👩‍💻 Autores

- [@sampvela](https://github.com/sampvela)
- [@Stefania2025](https://github.com/Stefania2025)
- [@alecruzmonge](https://github.com/alecruzmonge)
- [@littlebigliny](https://github.com/littlebigliny)
