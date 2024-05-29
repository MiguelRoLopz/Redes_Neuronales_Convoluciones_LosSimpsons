# Redes_Neuronales_Convoluciones_LosSimpsons
Uso de Convolutional Neural Networks para resolver un problema de clasificación de imágenes. En particular, vamos a clasificar imágenes de personajes de la conocida serie de los Simpsons.

Como las CNN profundas son un tipo de modelo bastante avanzado y computacionalmente costoso, se recomienda hacer la práctica en Google Colaboratory con soporte para GPUs. En este enlace se explica cómo activar un entorno con GPUs. Nota: para leer las imágenes y estandarizarlas al mismo tamaño se usa la librería opencv. Esta biblioteca está ya instalada en el entorno de Colab, pero si trabajáis de manera local tendréis que instalarla.

El dataset a utilizar consiste en imágenes de personajes de los Simpsons extraídas directamente de capítulos de la serie. Aparte de tener más clases (vamos a utilizar los 18 personajes con más imágenes), los personajes pueden aparecer en distintas poses, en distintas posiciones de la imagen o con otros personajes en pantalla (si bien el personaje a clasificar siempre aparece en la posición predominante).
