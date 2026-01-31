
# Análisis Predictivo de Rotación de Empleados con Máquinas de Soporte Vectorial (SVM)

Este proyecto es una práctica de Máquinas de Soporte Vectorial (SVM) desarrollada como parte del Bootcamp. El objetivo principal es analizar las razones por las cuales los empleados deciden dejar una empresa para unirse a la competencia. Este problema representa un desafío importante para los departamentos de recursos humanos, y se aborda mediante la creación de modelos predictivos de Machine Learning.

## Objetivo del Proyecto

El objetivo es construir un modelo predictivo utilizando el método de Máquinas de Soporte Vectorial (SVM) para predecir si un empleado dejará la empresa o no, basándose en diversas características relacionadas con su desempeño, satisfacción y condiciones laborales. Además, se busca identificar el modelo más adecuado entre los diferentes tipos de kernel disponibles en SVM.

## Descripción de los Datos

La base de datos utilizada contiene información sobre empleados y las siguientes variables:

- **satisfaction_level**: Nivel de satisfacción del empleado.
- **last_evaluation**: Puntaje obtenido en la última evaluación.
- **average_monthly_hours**: Promedio de horas trabajadas al mes.
- **time_spend_company**: Tiempo que el empleado ha trabajado en la empresa.
- **work_accident**: Indica si el empleado ha tenido algún accidente laboral (1 = Sí, 0 = No).
- **promotion_last_5years**: Indica si el empleado ha sido promovido en los últimos 5 años (1 = Sí, 0 = No).
- **sales**: Departamento en el que trabaja el empleado.
- **salary**: Categoría del salario del empleado (bajo, medio, alto).
- **left**: Variable objetivo que indica si el empleado dejó la empresa (1 = Sí, 0 = No).

## Metodología

1. **Preparación de los Datos**:
   - Carga de la base de datos en Python utilizando la biblioteca `pandas`.
   - Recodificación de las variables categóricas mediante la técnica de codificación `pd.get_dummies`.

2. **Entrenamiento del Modelo**:
   - Implementación del método de Máquinas de Soporte Vectorial (SVM) para generar un modelo predictivo.
   - Prueba de los cuatro tipos de kernel discutidos en la lección:
     - Lineal
     - Polinómico
     - RBF (Radial Basis Function)
     - Sigmoide

3. **Evaluación del Modelo**:
   - Generación de mapas de calor para las matrices de confusión.
   - Elaboración de reportes de clasificación detallados.
   - Interpretación de los indicadores de desempeño del modelo.

4. **Selección del Mejor Modelo**:
   - Comparación de los resultados obtenidos con cada kernel.
   - Selección del modelo más adecuado basado en métricas de evaluación como precisión, recall, F1-score, entre otros.

5. **Predicción**:
   - Uso del modelo seleccionado para realizar predicciones sobre nuevos datos. Por ejemplo, se analiza el caso de un empleado con los siguientes indicadores:
     - **satisfaction_level**: Por definir.
     - **last_evaluation**: Por definir.
     - **average_monthly_hours**: Por definir.
     - **time_spend_company**: Por definir.
     - **work_accident**: Por definir.
     - **promotion_last_5years**: Por definir.
     - **sales**: Por definir.
     - **salary**: Por definir.

## Resultados Esperados

El proyecto busca determinar cuál de los cuatro kernels de SVM genera el modelo más adecuado para predecir la rotación de empleados. Además, se espera interpretar los resultados obtenidos y proporcionar recomendaciones basadas en los hallazgos.

## Requisitos

- Python 3.7 o superior
- Bibliotecas necesarias: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `jupyter`

## Instalación

1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Instala las dependencias necesarias:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

## Uso

1. Abre el cuaderno en Jupyter Notebook:
   ```bash
   jupyter notebook "Tarea M22-CD – RaulCortesAmador.ipynb"
   ```
2. Ejecuta las celdas en orden para realizar el análisis y generar los modelos predictivos.

## Autor

Raúl Cortés Amador
