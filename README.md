# Convolutional Neural Networks

En el presente repositorio muestro algunos ejemplos sobre 

el entrenamiento de redes neuronales convolucionales aplicadas a la 

clasificación de imágenes a color correspondientes al datase "CIFAR10",

dicho dataset consta de un tensor 4D donde cada entrada representa una imagen 

a color en su descompocisión RGB (Red, Green, Blue).

Muestro dos versiones de código, una en donde se entrena la red usando la función de costo

`loss = 'categorical_crossentropy'` la cual requiere una codificación de las etiquetas; 

en la otra versión entrenamos la red usando la función de costo 

`loss = 'sparse_categorical_crossentropy'` la cual NO requiere una codificación de las etiquetas.

Debido a que el entrenamiento de redes convolucionales generalmente implica 

un alto costo computacional, hemos corrido los códigos sobre una tarjeta gráfica NVIDIA,

así que al inicio de los códigos muestro las versiones de los paquetes usados.
