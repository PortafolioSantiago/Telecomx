# 📊 Análisis de Evasión de Clientes (`Churn`) - Telco Dataset

Este proyecto tiene como objetivo analizar y predecir la evasión de clientes (churn) en una empresa de telecomunicaciones, utilizando herramientas de ciencia de datos como Python, Pandas, Seaborn y Matplotlib.

---

## 📁 Contenido del Proyecto

- **1. Carga y limpieza de datos**
  - Conversión de tipos `object` a `string`
  - Detección y tratamiento de valores nulos (`NaN`) y erróneos (como `-1`)
  - Relleno por media o valores personalizados
  - Reemplazo de valores categóricos (`Yes/No`) por binarios (`1/0`)

- **2. Análisis exploratorio**
  - Estadísticas descriptivas
  - Distribución de la variable `Churn`
  - Relación entre evasión y variables categóricas (como género, tipo de contrato, método de pago)
  - Relación entre evasión y variables numéricas (como tiempo de contrato y cargos mensuales)

- **3. Análisis de correlación**
  - Matriz de correlación para identificar variables relevantes
  - Visualización con `heatmap`
  - Cálculo de número de servicios contratados por cliente

---

## 📌 Hallazgos Clave

1. 🔻 La tasa de cancelación es moderada (~23%).
2. 🧑‍🤝‍🧑 Menos de la mitad de los clientes tiene pareja o dependientes.
3. 📞 La mayoría usa servicios telefónicos y facturación electrónica.
4. 💰 Existe gran variabilidad en los cargos mensuales.
5. ⚠️ Se identificaron valores erróneos (-1) que deben ser tratados antes del modelado.

---

## 📊 Herramientas Utilizadas

- Python 3
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---
## 🧠 Autor

**Santiago Isaias Sandoval Guerrero**  
Proyecto académico – Ciencia de Datos 2025


