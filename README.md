# Generador3DFreeCAD
Genera en FreeCAD un sólido 3D a partir de 2 o 3 vistas en 2D.



Instalación:
Copia el contenido completo de este script (todos los ficheros) en la carpeta "macros" de tu FreeCAD. Sin la carpeta "generador3D" la macro no funcionará.
Luego crea una macro con el contenido del archivo principal "Generador3D_0.0.9BETA.FCMacro" (el número corresponde a la versión), y asígnale el icono SVG proporcionado.

Funcionamiento:
Crea las vistas adecuadas con bocetos (sketch) para la generación de un objeto 3D. Pueden ser 2 o 3 vistas, que deben corresponderse a la Planta, Alzado y/o Lateral de la pieza. Los salientes no los interpreta por el momento, pero los agujeros sí. Un boceto puede contener varios contornos, siempre y cuando no se crucen o sean vaciados (agujeros).

Notas:
Si una vista en Planta se asigna a un frontal, aunque hace la operación, el resultado no será correcto. Esto, por el momento no está depurado.
Por el momento, esto es una versión BETA. No usar sin la pertinente copia de seguridad de los modelos a realizar.
