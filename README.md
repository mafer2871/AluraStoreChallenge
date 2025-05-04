# Análisis de Datos Ventas en Tiendas Alura Store

Este repositorio contiene un análisis de datos de ventas de cuatro tiendas, realizado utilizando Python y las bibliotecas Pandas y Matplotlib en Google Colab.

## Objetivo

El objetivo principal de este ejercicio es aplicar técnicaas de análisis de datos sobre las ventas de las 4 tiendas de Alura Store, para ayudar al Señor Juan, propietario de las mismas, a decidir cuál de ellas podría ser susceptible de venta de acuerdo a diversos aspectos como el rendimiento de cada tienda, incluyendo ventas, calificaciones de clientes y costos de envío. El análisis termina con la identificación de una tienda que podría ser candidata para la venta.

## Metodología

El análisis se llevó a cabo siguiendo los siguientes pasos:

1.  **Carga y Exploración de Datos:** Los datos de cada tienda se cargaron en DataFrames de Pandas dentro de un entorno de Google Colab. Se realizó una exploración inicial para comprender la estructura y el contenido de los datos.
2.  **Análisis de Ventas:** Se calcularon las ventas totales por tienda para determinar el volumen de ventas de cada una.
3.  **Análisis de Volumen de Ventas por Categorias de productos:** Se observó el patrón de ventas para cada tienda
4.  **Análisis de Calificaciones:** Se calculó el promedio de calificaciones de los clientes por tienda para evaluar la satisfacción general.
5.  **Análisis de Costos de Envío:** Se determinó el costo promedio de envío por transacción para cada tienda.
7.  **Análisis de Volumen de Ventas por Producto:** Se identificaron los 5 productos más y menos vendidos en cada tienda.
8.  **Análisis Ventas por Ciudad:** A partir del lugar de venta, se realizó una visualización de ventas por ciudad.
9.  **Visualización de Datos:** Se utilizaron gráficos de barras (horizontales y verticales) de Matplotlib para visualizar las comparativas entre tiendas en términos de ventas, calificaciones y costos de envío. También se generaron gráficos para el volumen de ventas por producto y categoría y ventas por ciudad.
10.  **Informe de Conclusiones:** Se elaboró un informe basado en los resultados del análisis para identificar tendencias y proporcionar recomendaciones, incluyendo la posible identificación de una tienda para la venta.

## Contenido del Repositorio :file_folder:

* **`challenge1_DA1.ipynb`:** El archivo de Google Colab que contiene el código Python completo para realizar el análisis. 
* **`README.md`:** Este archivo, que proporciona una descripción general del proyecto.
* **`InformeAluraStore.pdf` Documentos que presenta los resultados y las conclusiones del análisis.
* **`Base de datos`:** Carpta con los archivos de datos de las ventas de las 4 tiendas.

## Cómo Ejecutar el Código :zap:

1.  **Acceder al Notebook de Google Colab:** Abre el archivo `challenge1_DA1.ipynb` en Google Colab.
2.  **Cargar los Datos:** Asegúrate de que los archivos de datos CSV estén accesibles para el notebook (ya sea cargándolos directamente en Colab o accediendo a ellos desde Google Drive). **Modifica la sección de carga de datos en el notebook para que coincida con la ubicación de tus archivos.**
3.  **Ejecutar las Celdas:** Ejecuta las celdas de código secuencialmente en el notebook. Los resultados del análisis y las visualizaciones se mostrarán directamente en el notebook.

:mag_right:## Hallazgos Clave (Resumen):mag:

Basado en el análisis realizado:

* **Ventas:** La Tienda 1 y la Tienda 2 son las líderes en ventas, mientras que la Tienda 4 presenta el volumen más bajo.
* **Calificaciones:** Los promedios de calificación son similares entre las tiendas, con la Tienda 3 ligeramente superior y la Tienda 1 ligeramente inferior.
* **Costos de Envío:** La Tienda 1 tiene el costo promedio de envío más alto, y la Tienda 4 el más bajo.
* **Ventas por categoria:** Se identifica que las categorías más lucrativas son Electrónicos, Electrodomésticos, Muebles y las menos lucrativas las de Juguetes, Artículos para el hogar y Libros para todas las tiendas.
* **Recomendación Principal:** Se sugiere una revisión exhaustiva de la Tienda 4 debido a su bajo rendimiento en ventas, considerando la posible venta.

**Nota:** Este es un resumen de los hallazgos. El informe completo en el archivo adjunto proporciona un análisis más detallado.

## Autor

- [Mafer2871.](https://github.com/mafer2871)
