# Proyecto de Ciencia de Datos
El objetivo de este proyecto es utilizar las tablas de UCI para aplicar técnicas de aprendizaje supervisado y no supervisado vistos en el curso de Minería de Datos. Se busca estimar los niveles de obesidad en individuos de los países de México, Perú y Colombia, con base en sus hábitos alimenticios y condición física. Los datos contienen 17 atributos y 2111 registros, con una variable `NObesidad` (Nivel de obesidad), que permite clasificar los datos utilizando los valores de Peso Insuficiente, Peso Normal, Nivel de Sobrepeso I, Nivel de Sobrepeso II, Obesidad Tipo I , Obesidad tipo II y Obesidad tipo III. El 77% de los datos se generaron sintéticamente utilizando la herramienta Weka y el filtro SMOTE y el otro 23% de los datos se recopilaron directamente de los usuarios a través de una plataforma web. La información acerca de los datos y los paper relevantes que se han creado a partir de este ejercicio lo pueden encontrar en: [ Estimation of obesity levels based on eating habits and physical condition Data Set ](https://archive.ics.uci.edu/ml/datasets/Estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition+)

## Descripción
En este ejercicio se hará en primer lugar un análisis exploratorio de la base de datos y posteriormente se desarrollarán modelos que permitan determinar el nivel de obesidad para cualquier individuo.

## Estructura del proyecto
El proyecto está organizado de la siguiente manera: 

- `README`: Archivo con la descripción general del proyecto.

- `requirements`: Listado de las librerias y versiones utilizadas.

- `Datos`: Carpeta con las bases de datos utilizadas, original y transformada.

- `Codigo`: Cuadernos con el código en sus dos etapas:

  *`1_Análisis_Exploratorio.ipynb`: Cuaderno del análisis exploratorio. Incluye:
        - 1. Cargar las librerias
        - 2. Cargar los datos
        - 3. Descripción de las variables numéricas continuas
        - 4. Descripción de las variables categóricas
        - 5. Transformación de los Datos
        - 6. Reducción de dimensiones - Análisis de Componentes Principales
        - 7. Reducción de dimensiones - Método de Clusters K-MEANS

    * `2_Modelos_Aprendizaje.ipynb`: Cuaderno con el código de los dos modelos.
        - 1. Random Forest
        - 2. Naive Bayes
        - 3. Regresión Logística
        - 4. Árboles de Clasificación
        - 5. Redes Neuronales 

## Presentado por:
ALEANDRO MORENO FONSECA 
