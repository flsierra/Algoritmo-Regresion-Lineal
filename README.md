# Algoritmo de Regresión Lineal - Análisis de Datos UNAD

Este repositorio contiene el desarrollo de un modelo de **Regresión Lineal** como parte del curso de Análisis de Datos de la **Universidad Nacional Abierta y a Distancia (UNAD)**. El proyecto fue desarrollado en **Python** utilizando **Anaconda** y **Jupyter Notebooks**.

## 🧪 Estructura del Proyecto

El análisis y desarrollo del modelo se llevó a cabo en los siguientes pasos:

1. **Realizar el análisis exploratorio de los datos**
   - Revisión del conjunto de datos.
   - Estadísticas descriptivas y exploración visual.
   - Identificación de relaciones entre variables.

2. **Procesar los datos limpiándolos, tratando valores faltantes y transformándolos**
   - Manejo de valores nulos o inconsistentes.
   - Normalización o estandarización de variables.
   - Codificación de variables categóricas si aplica.

3. **Seleccionar las características más relevantes para entrenar el modelo utilizando selección de características**
   - Evaluación de la importancia de las variables.
   - Aplicación de técnicas como `SelectKBest`, correlaciones, etc.

4. **Dividir el dataset en Train y Test para evaluar correctamente el modelo**
   - Separación de los datos en conjuntos de entrenamiento y prueba usando `train_test_split`.
   - Uso de una semilla aleatoria para garantizar reproducibilidad.

5. **Entrenar el modelo configurando los diferentes hiperparámetros**
   - Implementación del modelo de Regresión Lineal.
   - Ajuste de parámetros si es necesario (regularización, normalización, etc.).
   - Validación del modelo.

6. **Evaluar el desempeño del modelo en el conjunto de Test con métricas como precisión, recall, F1-score**
   - Evaluación con métricas como MSE, RMSE y R² (ya que es un problema de regresión).
   - En caso de clasificación, se puede complementar con precisión, recall y F1-score.

7. **Realizar las diferentes gráficas que permitan visualizar los resultados del modelo**
   - Comparación entre valores reales y predichos.
   - Residuales, error de predicción, dispersión de resultados.
   - Gráficas de correlación y distribución.

## 🛠️ Herramientas Utilizadas

- **Lenguaje:** Python 3.9+
- **Entorno:** Anaconda y Jupyter Notebooks
- **Librerías principales:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `matplotlib.pyplot`

## 📦 Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/tu_usuario/nombre_del_repositorio.git
