# Análisis de Regresión Múltiple, Ridge y Lasso para Pronóstico de Emisiones de CO2

Este proyecto tiene como objetivo construir y evaluar modelos de regresión múltiple, Ridge y Lasso para predecir las emisiones de CO2 utilizando un conjunto de datos real. A través de este análisis, se busca determinar cuál de los modelos es el más adecuado para realizar pronósticos precisos.

## Descripción del Proyecto

El proyecto se centra en el análisis de un conjunto de datos que contiene información sobre emisiones de CO2 y otras variables relacionadas. Se aplican técnicas de regresión múltiple, Ridge y Lasso para construir modelos predictivos y evaluar su desempeño mediante métricas de bondad de ajuste. Finalmente, se comparan los resultados de los modelos para determinar cuál es el más efectivo.

## Objetivos

1. **Preprocesamiento de datos**:
   - Eliminar columnas categóricas del conjunto de datos.
   - Verificar y manejar valores nulos para garantizar la calidad de los datos.

2. **Regresión Múltiple**:
   - Construir un modelo de regresión múltiple para predecir la variable objetivo `CO2 EMISSIONS`.
   - Calcular métricas de evaluación como:
     - Coeficiente de determinación (R²).
     - Error medio absoluto (MAE).
     - Error cuadrático medio (MSE).
   - Utilizar los coeficientes del modelo para realizar un pronóstico de la primera observación del conjunto de prueba y compararlo con el resultado obtenido mediante la función `predict`.

3. **Regresión Ridge**:
   - Aplicar un modelo de regresión Ridge utilizando el valor óptimo de Alpha.
   - Evaluar el modelo con las mismas métricas de bondad de ajuste.
   - Comparar los resultados con los obtenidos en la regresión múltiple.

4. **Regresión Lasso**:
   - Aplicar un modelo de regresión Lasso utilizando el valor óptimo de Alpha.
   - Evaluar el modelo con las mismas métricas de bondad de ajuste.
   - Comparar los resultados con los obtenidos en los modelos anteriores.

5. **Comparación de Modelos**:
   - Analizar los resultados de los tres modelos (Regresión Múltiple, Ridge y Lasso).
   - Determinar cuál de los modelos es el más adecuado para predecir las emisiones de CO2 y explicar las razones detrás de esta elección.

## Conjunto de Datos

El conjunto de datos utilizado en este proyecto contiene información sobre emisiones de CO2 y otras variables relacionadas. Antes de realizar el análisis, se llevaron a cabo las siguientes tareas de preprocesamiento:

- Eliminación de columnas categóricas.
- Verificación y eliminación de valores nulos.

### Variables principales:

- **CO2 EMISSIONS**: Variable objetivo que representa las emisiones de CO2.
- **Variables predictoras**: Variables numéricas relacionadas con las emisiones de CO2.

## Metodología

1. **Preprocesamiento de datos**:
   - Se eliminaron las columnas categóricas para trabajar únicamente con variables numéricas.
   - Se verificó la existencia de valores nulos y se eliminaron o imputaron según fuera necesario.

2. **Modelos de regresión**:
   - Se implementaron tres modelos de regresión:
     - Regresión Múltiple.
     - Regresión Ridge.
     - Regresión Lasso.
   - Se ajustaron los modelos a los datos de entrenamiento y se evaluaron con métricas de desempeño.

3. **Evaluación de modelos**:
   - Se calcularon las métricas de bondad de ajuste para cada modelo:
     - R² (coeficiente de determinación).
     - MAE (error medio absoluto).
     - MSE (error cuadrático medio).
   - Se compararon los resultados de los modelos para determinar cuál ofrece el mejor desempeño.

4. **Pronóstico**:
   - Se utilizó cada modelo para predecir la primera observación del conjunto de prueba.
   - Se compararon los resultados obtenidos con los valores reales y con los resultados de la función `predict`.

## Conclusiones

- Se identificaron las diferencias en el desempeño de los modelos de regresión múltiple, Ridge y Lasso.
- El modelo con el mejor desempeño fue **[inserta aquí el modelo ganador]**, ya que presentó el mejor balance entre las métricas de evaluación y la capacidad de generalización.
- Este análisis demuestra la importancia de seleccionar el modelo adecuado y ajustar los hiperparámetros (como el valor de Alpha) para obtener mejores resultados en problemas de predicción.

## Requisitos

Para ejecutar este proyecto, se requiere tener instalado:

- Python 3.x
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Ejecución

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias necesarias utilizando `pip install -r requirements.txt`.
3. Abre el archivo Jupyter Notebook y ejecuta las celdas para realizar el análisis y generar los modelos.

## Autor

Este proyecto fue desarrollado por **Raúl Cortés Amador** como parte de las prácticas del Bootcamp de Machine Learning.

## Licencia

Este proyecto está bajo la licencia MIT. Puedes consultar más detalles en el archivo `LICENSE`.
