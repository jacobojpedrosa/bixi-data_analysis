<<<<<<< HEAD
# README #

El enunciado de esta prueba se basa en trabajar un conjunto de datos de la empresa BIXI de Montreal que se encuentran en [https://www.kaggle.com/aubertsigouin/biximtl](https://www.kaggle.com/aubertsigouin/biximtl).

Al ser un proyecto orientado al análisis de datos (cerca de 1Gb), he optado trabajar con un notebook de Jupyter, ya que es un entorno rápido donde explorar la información, extraer conclusiones y si es necesario adaptar el código para producción.


### ¿Cómo ejecutarlo? ###
Al ser un notebook de Jupyter, se puede trabajar directamente desde Anaconda o desde un docker de Jupyter:
* [Anaconda](https://www.anaconda.com/products/individual)
* [Docker Jupyter](https://hub.docker.com/r/jupyter/all-spark-notebook)


### Dependencias ###

El listado completo de librerias necesarias se encuentra en el archivo botstrap.sh, que se puede ejecutar directamente en el arranque de un container o unas instancia EMR.

En caso de trabajar en un entorno en el que ya se encuentren las librerias más comunes instaladas, he resuelto además las dependencias más específicas dentro del propio notebook. Celdas qeu habria que eliminar al llevarlo a producción.
