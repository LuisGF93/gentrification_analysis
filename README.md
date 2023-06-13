# gentrification_analysis

1. Datasets
    - Los datasets empleados inicialmente se encuentran en la ruta datasets/base_data, siendo la base houses_Madrid.csv y listings_detailed.csv.
    - En cuanto al dataset final, se encuentra en la ruta datasets/analyzed_data, siendo el conjunto final clean_after_null_and_outliers_with_boxcox.csv.

2. La carpeta geocoding contiene la información que se ha extraído de los procesos de geocodificación:
    - El código se encuentra en code/geocoding.ipynb.

3. Código:
    - Siguiendo la guía de la práctica, el código se ha dividido en 4 apartados (además del notebook de geocodificación).
    - code/selection_and_data_cleaning.ipynb hace referencia a las tareas del apartado 2.
    - code/null_and_outliers.ipynb hace referencia a las tareas de limpieza de valores nulos y outliers. Además se realiza un análisis de normalidad mediante Shapiro-Wilk antes y después de aplicar Box-Cox al conjunto.
    - code/analysis.ipynb contiene el código relacionado con el análisis estadístico realizado sobre el conjunto de datos final.
    - code/h3_visualization.ipynb contiene el código relacionado con la muestra de mapas y la distribución de un par de variables de muestra sobre los contornos de los distintos distritos de Madrid.

4. Modo de uso
    - Se recomienda crear un entorno virtual.
    - Tras ello, se puede ejecutar ´´´pip install -r requirements.txt´´´para instalar las librerías necesarias para la ejecución del código.

5. Los ficheros h3 hacen referencia al código html generado desde pydeck para la visualización de los mapas. Se trata de mapas mínimamente interactivos (permiten desplazamiento a lo largo y ancho del mapa y se puede modificar el ángulo de ataque para mostrar una imagen más o menos vertical).
