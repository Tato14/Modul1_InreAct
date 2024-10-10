# **Iniciación al Uso de la IA en Salud**

Este repositorio contiene una serie de notebooks diseñados para introducir a los usuarios en el uso de la Inteligencia Artificial (IA) en el sector de la salud. Los notebooks cubren diferentes áreas del aprendizaje automático, incluyendo aprendizaje supervisado, no supervisado y por refuerzo, y están enfocados en aplicaciones prácticas y análisis de sesgos en modelos de IA.

## **Contenido del Repositorio**

1. [**Exploración de Datos y Detección de Sesgos**](#1-exploración-de-datos-y-detección-de-sesgos)
2. [**Predicción de Enfermedades**](#2-predicción-de-enfermedades)
3. [**Agrupamiento de Pacientes**](#3-agrupamiento-de-pacientes)
4. [**Simulación de Decisiones Clínicas con Aprendizaje por Refuerzo**](#4-simulación-de-decisiones-clínicas-con-aprendizaje-por-refuerzo)

---

### **1. Exploración de Datos y Detección de Sesgos**

**Archivo:** `Modul1_Lab1.ipynb`

**Descripción:**

En este notebook, exploramos un conjunto de datos médicos relacionado con enfermedades cardíacas. Realizamos un análisis exploratorio de datos para detectar posibles sesgos en variables demográficas como edad y sexo. Este análisis es fundamental para garantizar que los modelos de aprendizaje automático sean justos y no perpetúen desigualdades.

**Objetivos:**

- Realizar un análisis exploratorio de datos.
- Identificar y visualizar distribuciones de variables clave.
- Detectar posibles sesgos en los datos.
- Entender la importancia de abordar los sesgos antes de modelar.

---

### **2. Predicción de Enfermedades**

**Archivo:** `Modul1_Lab2.ipynb`

**Descripción:**

Este notebook se enfoca en construir un modelo de aprendizaje supervisado para predecir la presencia de enfermedades cardíacas. Además, analizamos el rendimiento del modelo en diferentes subgrupos demográficos para identificar y entender posibles sesgos en las predicciones.

**Objetivos:**

- Preprocesar datos y preparar conjuntos de entrenamiento y prueba.
- Entrenar un modelo de clasificación (por ejemplo, regresión logística).
- Evaluar el rendimiento del modelo utilizando métricas como precisión, sensibilidad y especificidad.
- Analizar el rendimiento del modelo en subgrupos demográficos.

---

### **3. Agrupamiento de Pacientes**

**Archivo:** `Modul1_Lab3.ipynb`

**Descripción:**

En este notebook, aplicamos técnicas de aprendizaje no supervisado, específicamente el algoritmo K-Means, para agrupar pacientes basándonos en características clínicas. Posteriormente, analizamos los grupos formados para identificar posibles sesgos y disparidades entre diferentes subgrupos demográficos.

**Objetivos:**

- Aplicar técnicas de reducción de dimensionalidad (PCA).
- Utilizar el algoritmo K-Means para agrupar datos.
- Visualizar los clústeres y entender su composición.
- Analizar posibles sesgos en los grupos formados.

---

### **4. Simulación de Decisiones Clínicas con Aprendizaje por Refuerzo**

**Archivo:** `Modul1_Lab4.ipynb`

**Descripción:**

Este notebook implementa una simulación básica de decisiones clínicas utilizando técnicas de aprendizaje por refuerzo. Creamos un entorno simulado donde un agente aprende a seleccionar el mejor tratamiento para pacientes, basándose en las recompensas obtenidas de los resultados de salud.

**Objetivos:**

- Definir un entorno simulado para el aprendizaje por refuerzo.
- Implementar un agente que utiliza el algoritmo Q-Learning.
- Entrenar el agente para que aprenda la política óptima.
- Evaluar y visualizar los resultados del aprendizaje.

---

## **Instrucciones para Utilizar los Notebooks**

1. **Clonar el Repositorio:**

   ```bash
   git clone https://github.com/Tato14/Modul1_InreAct.git
   ```

2. **Acceder a la carpeta del Repositorio:**

   ```bash
   cd nombre_del_repositorio
   ```

3. **Abrir los Notebooks:**

- Puedes abrir los notebooks utilizando [Jupyter Notebook](https://jupyter.org/install) o [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html).
- Alternativamente, puedes cargarlos en [Google Colab](https://colab.research.google.com/):
    Ve a Archivo > Subir notebook y selecciona el archivo `.ipynb` que deseas abrir.

## **Trabajar Directamente en Google Colab**

 - Puedes abrir los notebook directamente en [Google Colab](https://colab.research.google.com/):
    - 1. Ve a Archivo > Abrir Cuaderno
    - 2. Ve a la pestaña "Github" y en la url añade la del repositorio: "https://github.com/Tato14/Modul1_InreAct"
    - 3. Selecciona el notebook con el que quieres trabajar
