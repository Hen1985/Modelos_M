
Estimado estudiante, por este medio usted podra descargar el Software R y RStudio https://www.dropbox.com/sh/0rsy1lc4kimhsbl/AADxo3tu7yDvbLewlOYGSYt1a?dl=0

Recodificar variables en el mi primer  modelo  de regresión lineal multiple

** Recodificación de las variables 

DATASET ACTIVATE ConjuntoDatos1. 
COMPUTE edad_años=edad/12.
EXECUTE.

DATASET ACTIVATE ConjuntoDatos1.
COMPUTE estatura_cm=Height*2.54.
EXECUTE.


DATASET ACTIVATE CONJUNTODatos1.
COMPUTE peso_kg=Weight*0.45.
EXECUTE.
