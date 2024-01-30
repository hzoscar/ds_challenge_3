# Desafío de Clustering en Ciencia de Datos de Alura LATAM - Parte 1

Este desafío corresponde a la tercera parte del Bootcamp de Ciencia de Datos de Alura LATAM, específicamente la primera parte del tercer desafío. En este proyecto, exploramos el comportamiento de los clientes de una cadena de supermercados con el objetivo de mejorar su experiencia de compra. A través de diversos análisis, buscamos identificar patrones de compra, preferencias y hábitos, utilizando esta información para ofrecer un servicio personalizado y adaptado a las necesidades de cada cliente. El método K-Means se utiliza para llevar a cabo la clusterización de los clientes.

## Desafío Dividido en 6 Partes:

### 1. Preparación del Ambiente:
   En esta etapa, preparamos el ambiente de trabajo e importamos la base de datos con la que trabajaremos.

### 2. Exploración de Datos:
   Se realiza una exploración de datos dividiendo las variables del dataset en cuatro grupos: variables del consumidor (consumer_columns), variables de los productos (products_columns), variables de las tiendas (stores_columns) y variables geográficas (geographic_columns), aunque estas últimas no se consideren en el análisis.

### 3. Preprocesamiento y Obtención de Features:
   Creamos funciones para análisis posteriores y seleccionamos y transformamos, si es necesario, las variables más relevantes para el modelo de clusterización.

### 4. Clasificación y Validación:
   Utilizando el método K-Means y siguiendo los criterios establecidos, determinamos que el número óptimo de clusters es 7. Se lleva a cabo una validación de la estructura y estabilidad de los clusters.

### 5. Descripción de los Clusters:
   Generamos recomendaciones estratégicas para personalizar la experiencia de los clientes en cada uno de los clusters identificados.

### 6. Bonus - KPrototypes:
   Realizamos la clusterización del dataset objetivo "X" mediante el método KPrototypes y graficamos el codo.

El dataset utilizado se encuentra disponible en Kaggle: [Medias Cost Prediction in FoodMart](https://www.kaggle.com/datasets/ramjasmaurya/medias-cost-prediction-in-foodmart)

