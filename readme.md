### En este archivo se registrarán los cursos que se estén llevando o que ya se hayan llevado para diferenciarlos de otros, así como el avance que se hace de los mismos.

Este repositorio siempre permanecerá en la carpeta 'Practicando' ubicada en el escritorio, y dentro de este repositorio se registrará el avance de cada curso según convenga.

La estructura de las carpetas dentro de 'Practicando' y cómo se están llevando los cursos es:

> Desktop
>   > Practicando
>     >\_GNRL
>       Plantilla-seguimiento-curso
>       (carpeta donde se guardará este archivo para el formateo general del seguimiento de los cursos)
>     > AutoCAD
>     > Cpp
>     > Excel
>     > Python
>     > WEB
>     > ... Otros temas
>     (estos temas no son los cursos en sí, los cursos están dentro de estas carpetas)

Dentro de la carpeta 'Practicando' se ubicarán carpetas por temas a practicar y dentro de estos temas los cursos propiamente dichos.
-TODOS- los cursos llevados deben tener un registro en estas carpetas dentro de su respectivo tema, sean cursos con origen en PC, Youtube, Udemy o le que sea, deben registrarse en esta carpeta para que quede como fuente de consulta a futuro y como verificación si un curso ya se llevo y no estar repitiendolo.

Al empezar un curso, dependiendo del origen del mismo se procederá de la siguiente manera:

1. Con origen en PC:
   1.1. En la ruta de los videos del curso (que no es la carpeta 'Practicando' sino en otra unidad de almacenamiento), se deberá incluir una carpeta llamada 'seguimiento-curso' en la que se deberá incluir un archivo 'nombre-de-curso.html' con unicamente el 'ENCABEZADO DEL CURSO' (desarrollado más abajo), esto para indicar si el curso está siendo llevado.
   1.2. Luego, en la carpeta 'Practicando', dentro de sus respectivas carpetas de tema y nombre de curso, se incluirá este archivo 'nombre-de-curso.html' en el que se incluirá todo el desarrollo del curso, incluyendo links a los videos, documentación, apuntes, etc.
2. Con origen Web (Youtube, Udemy, otros):
   de frente se incluirá el archivo 'nombre-de-curso.html' tal cual el punto 1.2.

|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
|||||||||||||||||||||||||||||||||||||||||||||||||||||||||| ENCABEZADO DE CURSO
|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||

-> CURSO:

-> IMAGEN(ES) MINIATURAS:
para rápida identificación.

-> WEB OFICIAL:

-> INICIO DEL CUROS:
dd mm yyyy

-> DESCRIPCIÓN:

-> AUTOR:

-> PROFESOR:

-> ORIGEN:
udemy/youtube/pc/otro(especificar)

-> TAGS / TEMAS:

-> REPOSITORIOS GITHUB:
https://github.com/*/*.git
https://github.com/*/*.git

-> CARPETA PRINCIPAL EN PC:
si el curso es WEB, esta ruta es de los archivos de trabajo

-> CARPETAS (CAPÍTULOS):
Capitulo 1 - nombre del tema\
Capitulo 2 - nombre del tema\
Capitulo 3 - nombre del tema\

-> CONTENIDO CUANTITATIVO:
si el curso es WEB, no es necesario poner este dato
18 archivos
13 carpetas

|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||| FIN DEL ENCABEZADO DE CURSO
|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||

ULTIMO VISIONADO:
C:\Users\LV\Downloads\modern-html-css-beginning\6 - Box Model Positioning\62 - Borders.mp4

\***\*\*\*\*\*\*\***\*\*\***\*\*\*\*\*\*\***\*\***\*\*\*\*\*\*\***\*\*\***\*\*\*\*\*\*\*** HISTORIAL DE COMMMITS

Para el seguimiento y avance del curso, aquí se va registrando los commits más importantes de acuerdo a las lecciones, por ejemplo el inicio de cada clase (video), un tema importante que resaltar, etc. Los videos o capítulos que no merezcan un commit o que teniendo commits no sean de trascendencia para el curso, no deberían registrarse.
Lo ideal es que al principio del curso se ponga todas las carpetas y archivos de video, luego con el seguimiento del curso, se va actualizando los commits para cada video si es necesario.
Sólo Se hará un commit cada vez que se inicie un tema que sea importante, de otra forma se dejará que avance el curso incluso si se va avanzando los capítulos y estos no son importantes, no se debe hacer commits.
Cuando se haga un commit de un capitulo (entiéndase por capítulo una carpera que contiene uno o varios videos del tema) y que necesite un commit, deberá hacerse inmediatamente un commit vacío de nombre 'registro', que nos permitirá incluir el hash del commit anterior (el del capítulo) en este registro.

nnnnnnn **_ PRIMER COMMIT _**
Capitulo 1 - nombre del tema\ # nombre de carpeta de capítulo
nnnnnnn 001. nombre del primer video
nnnnnnn 002. nmmbre del segundo video
nnnnnnn 003. nombre del tercer video
Capitulo 2 - nombre del tema\ # nombre de carpeta de capítulo
nnnnnnn 004. nombre del primer video
nnnnnnn 005. nmmbre del segundo video
nnnnnnn 006. nombre del tercer video
Capitulo 3 - nombre del tema\ # nombre de carpeta de capítulo
nnnnnnn 007. nombre del primer video
nnnnnnn 008. nmmbre del segundo video
nnnnnnn 009. nombre del tercer video

nnnnnnn = hash del commit

\***\*\*\*\*\***\*\*\*\*\***\*\*\*\*\***\*\*\*\*\***\*\*\*\*\***\*\*\*\*\***\*\*\*\*\*** PARA VIDEOS EN PC
En esta área irán los enlaces a los videos del curso.
Si es un curso en PC la ruta será del archivo local, si es en web la dirección de la página web.
La idea de esta área es que en cada video revisado se pueda escribir comentarios o apuntar lo que sea resaltante del video.
Además, de ser necesario, se pueden incluir tags de los temas tocados en cada video para rápida indentificación de los temas vistos.

<video class="videoClase" type="video/mp4" controls src="RUTA DEL VIDEO 1.mp4"></video>
<video class="videoClase" type="video/mp4" controls src="RUTA DEL VIDEO 2.mp4"></video>
<video class="videoClase" type="video/mp4" controls src="RUTA DEL VIDEO 3.mp4"></video>
