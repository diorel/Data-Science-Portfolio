# Clasificación de Medicamentos con Árboles de Decisión

Este proyecto es una práctica de Machine Learning enfocada en la construcción de un modelo de clasificación utilizando árboles de decisión. El objetivo es predecir el medicamento más adecuado para un paciente con base en sus características clínicas.

<p align="center">
  <img src="https://github.com/diorel/Data-Science-Portfolio/blob/main/img/arbol.png?raw=true" width="450">
</p>

## Problema

Eres un investigador médico que ha recopilado datos sobre un conjunto de pacientes, todos ellos con la misma enfermedad. Durante su tratamiento, cada paciente ha respondido a uno de los cinco medicamentos disponibles: **fármaco A, fármaco B, fármaco C, fármaco X y fármaco Y**.

El objetivo principal de este proyecto es construir un modelo predictivo que permita determinar qué medicamento sería más adecuado para un futuro paciente con la misma enfermedad. Para ello, se utiliza un árbol de decisión como modelo de clasificación.

## Descripción de los Datos

El conjunto de datos utilizado en este proyecto contiene información sobre los pacientes y las siguientes características:

- **Age**: Edad del paciente.
- **Sex**: Sexo del paciente.
- **BP**: Nivel de presión arterial del paciente (bajo, normal, alto).
- **Cholesterol**: Nivel de colesterol del paciente (normal, alto).
- **Na_to_K**: Relación entre sodio y potasio en la sangre del paciente.
- **Drug**: Medicamento al que respondió el paciente (fármaco A, B, C, X o Y).

## Metodología

1. **Preparación de los Datos**:
   - Carga del conjunto de datos desde el archivo `drugs.csv` utilizando la biblioteca `pandas`.
   - Exploración inicial de los datos para entender su estructura y contenido.
   - Preprocesamiento de los datos, incluyendo la codificación de variables categóricas como `Sex`, `BP` y `Cholesterol`.

2. **Entrenamiento del Modelo**:
   - División del conjunto de datos en datos de entrenamiento y prueba.
   - Construcción de un modelo de árbol de decisión utilizando la biblioteca `scikit-learn`.
   - Entrenamiento del modelo con los datos de entrenamiento.

3. **Evaluación del Modelo**:
   - Evaluación del modelo utilizando los datos de prueba.
   - Generación de métricas de desempeño como precisión, recall y F1-score.
   - Visualización del árbol de decisión generado.

4. **Predicción**:
   - Uso del modelo entrenado para predecir el medicamento más adecuado para un nuevo paciente con características desconocidas.

## Resultados Esperados

El proyecto busca construir un modelo de árbol de decisión que permita clasificar correctamente el medicamento más adecuado para un paciente con base en sus características. Además, se espera interpretar el árbol de decisión generado y analizar su desempeño en términos de métricas de clasificación.

## Requisitos

- Python 3.7 o superior
- Bibliotecas necesarias: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `graphviz`, `pydotplus`, `jupyter`

## Instalación

1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Instala las dependencias necesarias:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn graphviz pydotplus jupyter
   ```

## Uso

1. Abre el cuaderno en Jupyter Notebook:
   ```bash
   jupyter notebook "Tarea M23-CD – RaulCortesAmador.ipynb"
   ```
2. Ejecuta las celdas en orden para realizar el análisis, construir el modelo y realizar predicciones.

## Autor

Raúl Cortés Amador
