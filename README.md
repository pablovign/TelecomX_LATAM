# Análisis de Evasión de Clientes (Churn) - TelecomX LATAM

Este proyecto analiza los datos de clientes de TelecomX LATAM para identificar patrones asociados con la cancelación del servicio (`churn`). El objetivo es obtener insights que permitan desarrollar estrategias de retención basadas en datos.

## 📌 Objetivo

- Identificar los factores que influyen en la cancelación de clientes.
- Detectar perfiles de clientes con mayor propensión al churn.
- Brindar recomendaciones estratégicas basadas en el análisis de datos.

---

## 📁 Estructura del Proyecto

El análisis se desarrolla completamente en el archivo `TelecomX_LATAM.ipynb`, que contiene:

1. **Importación y limpieza de datos**
2. **Análisis exploratorio de variables numéricas y categóricas**
3. **Visualizaciones**
4. **Insights clave y conclusiones**
5. **Creación de nuevas variables**
6. **(Opcional) Análisis de correlaciones**
7. **Informe final estructurado**

---

## ⚙️ Requisitos y Dependencias

Este proyecto fue desarrollado en Python 3 y requiere las siguientes bibliotecas:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Instalación rápida (opcional):

```bash
pip install pandas numpy matplotlib seaborn
```

---

## ▶️ Cómo ejecutar el proyecto

1. Cloná el repositorio o descargá el archivo `.ipynb`.
2. Abrilo con Jupyter Notebook o Google Colab.
3. Ejecutá las celdas en orden para reproducir el análisis completo.

---

## 🧼 Limpieza y Procesamiento de Datos

- Se renombran columnas para mayor claridad.
- Se convierten variables a tipo categórico donde corresponde.
- Se crean nuevas variables derivadas, como la `cantidad_servicios` contratados por cada cliente.

---

## 📊 Análisis Exploratorio

- Se analiza el comportamiento de clientes que cancelaron vs. los que permanecen.
- Se visualizan diferencias por antigüedad, cargos mensuales, uso diario y servicios contratados.
- Se identifican variables con mayor correlación con la evasión.

---

## ✅ Conclusiones

- Clientes más nuevos y con cargos mensuales altos tienden a cancelar más.
- Quienes contratan menos servicios también presentan mayor tasa de cancelación.
- Existen patrones claros que permiten segmentar el riesgo de churn.

---

## 💡 Recomendaciones

- Foco en retener nuevos clientes con cargos mensuales elevados.
- Ofrecer beneficios escalonados según la antigüedad del cliente.
- Promover la contratación de paquetes de servicios combinados.
- Detectar clientes con alto uso diario para encuestas de satisfacción temprana.

---

## 📌 Autor

- 📧 *Tu Nombre* – *pablovignoni@gmail.com*
- 💼 Proyecto realizado como parte de un desafío de análisis de datos.

