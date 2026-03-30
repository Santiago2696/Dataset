# 📊 Dataset de Deserción Estudiantil

## 📌 Descripción

Este dataset fue generado de manera sintética con el propósito de simular un escenario real en el cual una institución educativa busca predecir la deserción estudiantil durante el primer año académico.

El objetivo es utilizar técnicas de Machine Learning para identificar estudiantes en riesgo y apoyar la toma de decisiones.

---

## 📁 Contenido del Dataset

El dataset contiene **500 registros**, donde cada fila representa un estudiante y sus características.

---

## 🧾 Variables

### 🔹 Datos Demográficos

* **edad**: Edad del estudiante (16 – 30 años)
* **genero**: Masculino / Femenino
* **ciudad**: Ciudad de origen (Barranquilla, Bogotá, Medellín, Cali, Cartagena)

### 🔹 Datos Académicos

* **promedio_colegio**: Promedio académico previo (2.0 – 5.0)
* **puntaje_examen**: Resultado del examen de admisión (100 – 500)
* **nota_semestre**: Nota del primer semestre (2.0 – 5.0)

### 🔹 Datos Financieros

* **nivel_socioeconomico**: Bajo / Medio / Alto
* **beca**: Indica si el estudiante posee apoyo financiero (Sí / No)

### 🔹 Variable Objetivo

* **desercion**: Indica si el estudiante abandonó sus estudios (Sí / No)

---

## ⚙️ Generación de Datos

Los datos fueron generados utilizando Python y librerías como `pandas` y `numpy`, simulando condiciones reales de estudiantes.

La variable **deserción** fue creada con base en reglas como:

* Bajo rendimiento académico
* Bajo nivel socioeconómico

---

## ⚠️ Datos Nulos

Se introdujo aproximadamente un **5% de valores nulos** de forma aleatoria en diferentes columnas para simular datos incompletos en escenarios reales.

---

## 📉 Outliers

Se agregaron valores atípicos (outliers) en algunas variables:

* **nota_semestre**: valores extremadamente bajos
* **puntaje_examen**: valores fuera del rango esperado

Esto permite probar técnicas de limpieza y análisis de datos.

---

## 🎯 Uso del Dataset

Este dataset puede ser utilizado para:

* Modelos de clasificación (Machine Learning)
* Análisis de datos
* Prácticas de limpieza de datos
* Predicción de deserción estudiantil

---

## 👨‍💻 Autor

Santiago Álvarez

---

## 📌 Nota

Este dataset es completamente sintético y fue creado únicamente con fines académicos.
