# ControlFiles_IN_BASH

Esta práctica fue realizada en Bash de Linux, y tiene como objetivo realizar copias de seguridad
de aquellos ficheros del usuario que hayan sufrido un cambio de contenido o modificaciones en 
sus permisos o nombre. 

Para conseguir esto, se realizaron 2 scripts, uno que se ocupa de salvaguardar todos los ficheros
del usuario y comprimirlo adjuntandole una marca de agua con la fecha para que pueda ser reconocida
posteriormente, y el otro script que se ocupa de comparar los ficheros actuales con la copia de seguridad
anterior para especificar aquellos que hayan sufrido alteraciones.

Además, estas herramientas puede ser ajustada mediante el uso de Crontab.
