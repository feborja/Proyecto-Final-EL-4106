# Proyecto Final EL-4106

 Style Transfer
 
Desarrollado por Ammi Beltrán y Fernanda Borja

Tutor  : Giovanni Castiglioni



Este repositorio contiene el proyecto de transferencia de estilos en base a la red VGG-16, inspirado en el trabajo hecho en el paper "Universal Style Transfer via Feature Transforms", la que trabaja con VGG-19. 
Este proyecto contiene un .ipynb comentado que realiza reconstrucciones, transferencias de estilo  de una y múltiples capas tanto con VGG-16 y 19, donde los parámetros de la VGG-16 fueron entrenados por nosotros, mientras que los de la otra red fueron importados desde el GitHub de los autores de la red. En el .ipynb se encuentra además una comparativa de las recontrucciones de imágenes de ambos modelos en base a una función de pérdidas. Todo lo requerido para ejecutar el código se encuentra dentro de este repositorio, pero si se desea probar resultados con otras imágenes es cosa de agregarlas a la carpeta que corresponda.

Se encuentra además adjunto el código utilizado para entrenar las capas de la red VGG-16, el cual está diseñado para ser ejecutado en Google Colab y tiene como requisito previo poseer las bases de dato de COCO test2017 y val2017.
