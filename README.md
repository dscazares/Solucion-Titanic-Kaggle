# Solución del Reto: Titanic - Machine Learning from Disaster

En este repositorio se encuentra una solución colaborativa a la competencia de Kaggle [Titanic - Machine Learning from Disaster](#https://www.kaggle.com/c/titanic)

**Equipo**
Ángel Corrales
Aralí Mata
Daniel Cázares
Izael Rascón
Yolanda Elizondo

## Contenido
<!-- no toc -->
- [Situación problema](#situación-problema)
- [Dataset](#dataset)

## Situación problema

El 15 de abril de 1912, durante su primer viaje, el RMS Titanic se hundió tras chocar con un iceberg. Desgraciadamente, no había suficientes botes salvavidas para todos, por lo que murieron 1,502 de los 2,224 pasajeros.

Aunque uno podría pensar que hubo cierto grado de suerte en la supervivencia,  parece que algunos grupos de personas tuvieron más probabilidades de sobrevivir que otros.

**Reto: Crear un modelo de Machine Learning que prediga ¿Qué personas tenían más probabilidades de sobrevivir?**

## Dataset

Los datos se dividen en dos grupos:
* Entrenamiento ([train.csv](#train.csv))
* Prueba ([test.csv](#test.csv))

**Diccionario**

Variable | Definición | Tipo
--- | --- | ---
survival | Supervivencia <br>(0 = No, 1 = Sí) | `Int` <br> Categórica Nominal
pclass | Clase de boleto | `Int` <br> Categórica Ordinal
sex | Sexo | `String` <br> Categórica Nominal
age | Edad en años | `Float` <br> Númerica Discreta
sibsp | # de hermanos/esposos a bordo | `Int` <br> Númerica Discreta 
parch | # de padres/hijos a bordo | `Int` <br> Númerica Discreta 
ticket | Numero de ticket | `String` <br> Categórica Nominal
fare | Tarifa | `Float` <br> Númerica Continua
cabin | Número de cabina | `String` <br> Categórica Nominal
embarked | Puerto de embarque <br> (C = Cherbourg, Q = Queenstown, S = Southampton) | `String` <br> Categórica Nominal