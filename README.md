# Trabajo-Integrador-Final

TEMA: Gestión de Estudiantes y Notas

              Integrantes:
Facundo Piedrabuena: Funciones de busqueda, ordenacion y archivos
Germán Romero: Lógica y funcionamiento del programa.

Los dos integrantes contribuimos a pulir los detalles y en la busqueda de errores. En algunas ocasiones trabajamos
conjuntamente por discord y tuvimos varios sitios por el que compartimos el codigo pero el que mas usamos fue google docs.
El trabajo que elegimos es basicamente un sistema de gestion de estudiantes y sus notas para cada materia.

    Instrucciones para compilar
Primero que nada necesitas un compilador de c, por mi parte uso TDM-GCC del cual adjunto link de descarga:
https://jmeubank.github.io/tdm-gcc/articles/2021-05/10.3.0-release
Luego tendrias que instalar algun editor de codigo fuente como ZinjaI o VSCODE
Luego de instalar todo eso simplemente copias el codigo y lo ejecutas

    Instrucciones para utilizar el programa correctamente
El programa requiere que se respete el orden de la carga de datos, de lo contrario no funcionara
o podria presentar algun error.
Lo primero que debemos hacer es cargar todas las materias que requeriremos, recien entonces podremos comenzar 
a cargar alumnos y luego de cargar los alumnos podremos cargar notas.

    El programa funciona de la siguiente forma:
Consta de un menu principal el cual te permite añadir/quitar materias,alumnos o notas.
Estas 3 opciones te redirigen a un submenu en el cual podes elegir si añadir o quitar materias
El menu principal tambien posee otras tres opciones las cuales son:
-Mostrar por pantalla (Muestra todos los datos cargados)
-Buscar un alumno especifico por DNI o Nombre
-Mostrar promedios ordenados por DNI o Nombre
Un alumno puede inscribirse en varias materias simultaneamente. Tambien puede tener varias notas para una misma
materia y cuando se requiera conocer el promedio el programa hara un promedio total para cada materia
El programa no identifica si hay alumnos que poseen el mismo nombre pero si identifica que cada alumno tenga
un unico e irrepetible DNI para cualquier materia.
Cada vez que se ejecuta el programa, este lee la ruta del archivo creado dentro de la carpeta output si es que lo
ejecutamos en vscode y cada vez que el programa se cierra hace una carga de los datos dentro de ese archivo
