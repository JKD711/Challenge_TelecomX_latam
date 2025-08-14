# 📊 Telecom X: Análisis y Predicción de Evasion de Clientes

## 📌 Descripción del Proyecto
Este proyecto tiene como objetivo **analizar y predecir la fuga de clientes (churn)** en una empresa de telecomunicaciones, utilizando técnicas de **Ciencia de Datos y Machine Learning**.  
Se estudian patrones de comportamiento y características de los clientes para identificar factores que influyen en la cancelación de servicios y desarrollar un modelo predictivo que ayude a implementar estrategias de retención.

---

## 🎯 Objetivos
- Analizar el comportamiento de los clientes y sus características.
- Identificar las principales variables que influyen en el **churn**.
- Desarrollar modelos de **Machine Learning** para predecir la fuga de clientes.
- Proporcionar recomendaciones basadas en datos para mejorar la retención.

---
## 📂 Estructura del Proyecto

El proyecto sigue una metodología estructurada que incluye las siguientes etapas:

1️⃣ **Introducción**  
   - Contexto del problema y objetivos del análisis.

2️⃣ **Extracción**  
   - Importación de librerías necesarias.  
   - Carga y extracción de datos desde la fuente.

3️⃣ **Transformación**  
   - Comprobación de incoherencias en los datos.  
   - Manejo y corrección de inconsistencias.  
   - Estandarización y transformación de datos.  
     - Conversión de valores textuales.  
     - Renombrado de columnas.

4️⃣ **Carga y Análisis**  
   - Análisis descriptivo inicial.  
   - Distribución de la evasión (churn).  
   - Recuento de evasión por variables categóricas.  
   - Conteo de evasión por variables numéricas.  
   - Análisis de correlación entre variables.

5️⃣ **Conclusiones e Insights**  
   - Resumen de hallazgos clave.

6️⃣ **Recomendaciones**  
   - Estrategias basadas en el análisis para reducir el churn.

---
## 📊 Metodología
1. **Recolección de datos:** Dataset de clientes de telecomunicaciones.
2. **Análisis exploratorio (EDA):**
   - Distribución de variables.
   - Detección de correlaciones.
   - Limpieza de datos y tratamiento de valores nulos.
3. **Preprocesamiento:**
   - Codificación de variables categóricas.
   - Escalado de datos numéricos.
   - Balanceo de clases con técnicas como SMOTE.
4. **Modelado y predicción:**
   - Modelos probados: **Logistic Regression, Random Forest, XGBoost**.
   - Evaluación con métricas: Accuracy, Precision, Recall, F1-Score, ROC-AUC.
5. **Interpretación y recomendaciones.**

---

## 📈 Resultados
<img width="1489" height="2990" alt="image" src="https://github.com/user-attachments/assets/ef95aaa9-a9fe-48a8-9105-004ae056ec44" />
<img width="1489" height="989" alt="image" src="https://github.com/user-attachments/assets/96e5b8ba-c860-4bb5-94fc-eeb1976e1c04" />
<img width="1031" height="805" alt="image" src="https://github.com/user-attachments/assets/b4c414c3-870f-4182-bd57-ba0b31cc0182" />

- Las variables más influyentes en la evasion fueron:
  1. Tiempo de permanencia.
  2. Tipo de contrato.
  3. Cargos mensuales.
  4. Uso de servicios adicionales.

---

## 🔹 Conclusiones
1. Los clientes con **contratos mensuales** y **altos cargos mensuales** tienen mayor probabilidad de abandonar el servicio.
2. La **retención temprana** es clave: la probabilidad de churn disminuye después del primer año.
3. Los **servicios adicionales** (Internet, TV, teléfono) influyen positivamente en la fidelización.
4. La predicción de churn permite actuar **proactivamente** antes de la cancelación.

---

## 🔹 Recomendaciones
1. Ofrecer **descuentos o beneficios** a clientes con contratos mensuales de alta facturación.
2. Implementar **programas de fidelización** desde los primeros meses.
3. Promocionar **paquetes de servicios combinados** para aumentar la permanencia.
4. Monitorear periódicamente a los clientes con alto riesgo usando el modelo desarrollado.

---

## 🛠️ Tecnologías Utilizadas
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- **Google Colab**
- **Visualización de Datos**
- **Análisis Exploratorio de Datos (EDA)**

---
