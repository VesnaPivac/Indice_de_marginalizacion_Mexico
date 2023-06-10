# El indice de marginalización de México

Este repositorio contiene el proyecto "Índice de Marginación en México", el cual se enfoca en analizar y visualizar el índice de marginación por municipio en México, utilizando datos del Consejo Nacional de Población (CONAPO).

## Descripción
El Consejo Nacional de Población (CONAPO) del gobierno mexicano realiza cada 5 años un análisis multidimensional de la pobreza y establece un índice de marginación. Este índice permite medir el grado de marginación de cada municipio en México, considerando diversos indicadores socioeconómicos.

Enlace al informe técnico para el cálculo del índice de marginación 2020: [Informe Técnico](https://www.gob.mx/cms/uploads/attachment/file/685354/Nota_te_cnica_IMEyM_2020.pdf)

El índice de marginación por municipio se puede consultar en el siguiente enlace: [Índices de Marginación 2020](https://www.gob.mx/conapo/documentos/indices-de-marginacion-2020-284372)

En este proyecto, se realizarán las siguientes tareas:
1. Descarga y lectura de los datos del índice de marginación por municipio 2020 en un DataFrame.
2. Análisis exploratorio de los datos, incluyendo estadísticas básicas y hallazgos interesantes.
3. Visualización del porcentaje de municipios por estado con distintos niveles de marginación.
4. Visualización del porcentaje de la población, respecto a la población total de cada estado, con distintos niveles de marginación.
5. Análisis de coincidencias entre las gráficas anteriores y hallazgos relevantes.
6. Graficar la relación entre el porcentaje de analfabetismo y el porcentaje de población en localidades de menos de 5,000 habitantes.
7. Determinar si existe una relación entre las variables mencionadas y analizar qué variable tiene una mayor correlación con el porcentaje de analfabetismo en personas mayores de 15 años.
8. Creación de un nuevo DataFrame con indicadores interesantes a nivel estatal, derivados de los datos municipales, con el objetivo de apoyar la definición de políticas públicas. Se valorará la originalidad de los indicadores seleccionados. El nuevo DataFrame será guardado en formato parquet.

## Instrucciones
1. Clona este repositorio en tu máquina local.
2. Descarga el archivo de la base de datos por municipio 2020 del índice de marginación desde la página de descargas del gobierno federal mexicano.
3. Coloca el archivo descargado en la carpeta "data".
4. Ejecuta el archivo Jupyter Notebook index_margination_analysis.ipynb para realizar el análisis y visualización de los datos.
5. Los resultados obtenidos se guardarán en la carpeta "output".

## Requisitos
Asegúrate de tener instalados los siguientes paquetes de Python:
- pandas
- matplotlib
- seaborn
Puedes instalarlos usando pip con el siguiente comando:
~~~
pip install pandas matplotlib seaborn
~~~

