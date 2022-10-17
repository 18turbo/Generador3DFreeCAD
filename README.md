# Generador3DFreeCAD
Genera en FreeCAD un sólido 3D a partir de 2 o 3 vistas en 2D.

IMPORTANTE: Ya se puede descargar la el G3D desde el administrador de complementos de FreeCAD.

# Versión 0.1.0

## Instalación:
Copia el contenido completo de este script (todos los ficheros) en la carpeta "macros" de tu FreeCAD. Sin la carpeta "g3d" la macro no funcionará.
Luego crea una macro con el contenido del archivo principal "g3d.FCMacro", y asígnale el icono SVG proporcionado en la carpeta "g3d/icons".

## Funcionamiento:
Crea las vistas adecuadas con bocetos (sketch) para la generación de un objeto 3D. Pueden ser 2 o 3 vistas, que deben corresponderse a la Planta, Alzado y/o Lateral de la pieza. Los salientes no los interpreta por el momento, pero los agujeros sí. Un boceto puede contener varios contornos, siempre y cuando no se crucen o sean vaciados (agujeros).

## Notas:
Si una vista se asigna de forma equivocada (por ejemplo, una vista en Planta se asigna a un frontal), aunque hace la operación, el resultado no será correcto, aunque no significa que el script no funcione correctamente.
Por el momento, esto es una versión BETA y, aunque no parece dar problemas, es importante NO usar sin la pertinente copia de seguridad de los modelos a realizar.

## Más información

[Wiki del proyecto](https://github.com/18turbo/Generador3DFreeCAD/wiki)


## Vídeo de funcionamiento:


[![Vídeo de Youtube](https://i9.ytimg.com/vi/wODulASYc_s/maxresdefault.jpg?time=1659626400000&sqp=CKDHr5cG&rs=AOn4CLB4iP9ExX4EKld1cP8v3efhnbHfhg)](https://www.youtube.com/watch?v=wODulASYc_s )

[![Vídeo de Youtube](https://i9.ytimg.com/vi/wODulASYc_s/maxresdefault.jpg?time=1659626400000&sqp=CKDHr5cG&rs=AOn4CLB4iP9ExX4EKld1cP8v3efhnbHfhg)](https://youtu.be/-Xknx1jLCm8 )


## Tutoriales (en español):

[[Lista de reproducción en Youtube]](https://www.youtube.com/watch?v=BJaT2DC7gPE&list=PL1EMxydRwgw9b-WHB-rLqvz3fTtA4LQt9 )


## Agradecimientos

* A mi mujer: el pilar básico de mi vida.
* A Rafael García: por la información y ayuda valiosa para desarrollar el script, además de hacer de betatester en las primeras versiones.
* A Rocco Vicedomini: por la traducción al inglés e italiano.

