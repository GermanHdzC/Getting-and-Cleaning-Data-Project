# Getting-and-Cleaning-Data-Project
==========================================

*Este es el proyecto del curso Getting and Cleaning Data
*Incluye el script `run_analysis.R` que contiene:

1.Descarga el grupo de datos de la web
2. Lee el train y test del dataset y hace un merge entre x(measurements), y(activity) y subject, respectivamente.
3. Carga las caracteristicas de los datos (x's), informacion de actividad y extraccion de las columnas 'mean'(`-mean`) y 'standard'(`-std`). 
  Asi como modifica los nombres de las columnas (`-mean` a `Mean`, `-std` a `Std`, y elimina simbolos como: `-`, `(`, `)`)
4. Extrae los datos seleccionados en el paso 3, merge x, y(activity) y subject.
5. Genera el 'Tidy Dataset' que consiste en el promedio (mean) de cada variable para cada materia y actividad.
   Se muestra el resultado en `tidy_dataset.txt`.

