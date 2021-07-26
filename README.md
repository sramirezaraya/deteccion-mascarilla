# Clasificacion de imágenes de rostros de personas con mascarillas y sin mascarillas.

## Descripcion 

Debido a la pandemia de COVID 19 el uso de mascarillas se hace indispensable. El propósito de
esta tarea es clasificar imágenes de rostros de personas con mascarillas y sin mascarillas. Además,
el clasificador debe ser capaz de inferir si el rostro corresponde a una persona de sexo masculino o
femenino. La idea es utilizar redes neuronales convolucionales para clasificar 3 experimentos:
* A. Clasificación de personas usando mascarillas
* B. Clasificación del sexo de las personas (independiente si usan o no mascarillas).
* C. Unión de los experimentos A y B en un solo sistema.

## Base de Datos

La base de datos esta compuesta por 5000 imágenes de rostros de personas con y sin mascarillas (2500
imágenes por clase). Por tanto, el número de clases que se tiene en la base de datos es el siguiente:

* Hombre con Mascarilla (1012 imagenes 224x224)
* Hombre sin Mascarilla (1250 imagenes 224x224)
* Mujer con Mascarilla (1488 imagenes 224x224)
* Mujer sin Mascarilla (1250 imagenes 224x224)

Total de Imagenes= 5000 

## link de la base de datos: https://drive.google.com/drive/folders/199aiQ55hkxvrc1UvfNKck6Caf4FbRlIE?usp=sharing

##  Modelo de CNN

Se utiliza un modelo de red neuronal convolucional básico para el entrenamiento de los datos. 
<br>
<br>
<img src="https://github.com/sramirezaraya/deteccion-mascarilla/blob/main/modelo.PNG">

## Entrenamiento

<img src="https://github.com/sramirezaraya/deteccion-mascarilla/blob/main/accuracy.png">
<br>
<br>
<img src="https://github.com/sramirezaraya/deteccion-mascarilla/blob/main/loss.png">

## Resultados en el conjunto de test

<img src="https://github.com/sramirezaraya/deteccion-mascarilla/blob/main/confusion.PNG">
