# Análisis de Evaluaciones de Productos en Amazon

Este proyecto implementa un **Algoritmo de Clustering Jerárquico** para analizar los promedios de evaluación de 100 personas que adquirieron los mismos productos o productos similares en la tienda Amazon. A partir de este análisis, se busca realizar recomendaciones personalizadas para tres clientes: Salomé, Stephanía y Lydia, basándonos en las preferencias y evaluaciones de otros clientes.

## Descripción del Proyecto

El archivo de datos proporcionado, `Amazon.csv`, contiene información sobre las evaluaciones promedio de productos realizadas por 100 clientes. Utilizando un algoritmo de Clustering Jerárquico, se agrupan los clientes en clústeres basados en sus preferencias de productos, lo que permite identificar patrones y realizar recomendaciones personalizadas.

### Objetivos

1. Analizar los datos de evaluación de productos.
2. Implementar un Algoritmo de Clustering Jerárquico para agrupar clientes con preferencias similares.
3. Realizar recomendaciones personalizadas para:
   - **Salomé**: Basado en las preferencias de otros clientes con gustos similares.
   - **Stephanía**: Basado en las evaluaciones de productos similares.
   - **Lydia**: Basado en las compras y evaluaciones de otros clientes.

### Estructura del Proyecto

- **`Tarea M26-CD – RaulCortesAmador.ipynb`**: Contiene el análisis de datos, la implementación del algoritmo de Clustering Jerárquico y las recomendaciones personalizadas para los clientes.
- **`Amazon.csv`**: Archivo de datos con las evaluaciones promedio de 100 clientes sobre productos de Amazon.

### Herramientas Utilizadas

- **Python**: Lenguaje principal para el análisis de datos.
- **Pandas**: Para la manipulación y análisis de datos.
- **Scipy**: Para la implementación del Algoritmo de Clustering Jerárquico.
- **Matplotlib/Seaborn**: Para la visualización de los resultados del clustering.
- **Jupyter Notebook**: Para la ejecución interactiva del código y la visualización de resultados.

### Metodología

1. **Carga de Datos**: Se utiliza la librería `pandas` para cargar y explorar los datos del archivo `Amazon.csv`.
2. **Preprocesamiento**: Limpieza y normalización de los datos para garantizar la calidad del análisis.
3. **Clustering Jerárquico**:
   - Se calcula la matriz de distancias entre los clientes.
   - Se aplica el algoritmo de Clustering Jerárquico para agrupar a los clientes con preferencias similares.
   - Se visualizan los resultados mediante un dendrograma.
4. **Recomendaciones Personalizadas**: Basándonos en los clústeres generados, se realizan recomendaciones específicas para Salomé, Stephanía y Lydia.

### Resultados y Conclusiones

- **Salomé**: Se recomienda adquirir los mismos productos que compró el cliente XXXXX, quien pertenece al mismo clúster que Salomé.
- **Stephanía**: Se recomienda adquirir los productos evaluados positivamente por el cliente XXXXX, quien tiene gustos similares y pertenece al mismo clúster.
- **Lydia**: Se recomienda adquirir los productos comprados por el cliente XXXXX, ya que sus evaluaciones reflejan preferencias similares y están en el mismo clúster.

### Requisitos

- Python 3.8 o superior.
- Librerías necesarias:
  - `pandas`
  - `scipy`
  - `matplotlib`
  - `seaborn`

Instalación de dependencias:
```bash
pip install -r requirements.txt
