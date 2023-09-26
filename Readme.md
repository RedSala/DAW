# Introduccion a GitHub

**GitHub** es una plataforma de alojamiento que ofrece a los desarrolladores la posibilidad de crear repositorios de código y guardarlos en la nube de forma segura, usando un sistema de control de versiones llamado Git.

Facilita la organización de proyectos y permite la colaboración de varios desarrolladores en tiempo real. 

### Ventajas de GitHub

* GitHub permite que alojemos proyectos en repositorios de forma gratuita
* Te brinda la posibilidad de personalizar tu perfil en la plataforma
* Los repositorios son públicos por defecto. Sin embargo, GitHub te permite también alojar tus proyectos de forma privada
* Puedes crear y compartir páginas web estáticas con GitHub Pages
* Facilita compartir tus proyectos de una forma mucho más fácil y crear un portafolio
* Te permite colaborar para mejorar los proyectos de otros y a otros mejorar o aportar a los tuyos
* Ayuda reducir significativamente los errores humanos y escribir tu código más rápido con GitHub Copilot

### ¿Cómo empezar a usar GitHub?

1. Crear un Repositorio de GitHub
Lo primero que debes tener es una cuenta creada en GitHub.
En la esquina superior derecha de cualquier página, encontrarás un signo de + que sirve para realizar las acciones de la página. Das clic en el símbolo y creas un nuevo repositorio (new repository).
Una vez realizado eso, debes llenar los datos que se solicitan a continuación. Darle un nombre, que de preferencia debe ser claro, definir si será público o privado y colocar una pequeña descripción sobre tu repositorio. Este campo es opcional, pero te recomiendo que lo llenes para organizarte mejor y que los demás usuarios tengan una idea sobre lo que trata el repositorio que estás creando.
Activa el checkbox que dice iniciar tu repositorio con un README, este será tu primer archivo, la presentación de tu proyecto.
Presiona el botón de “crear repositorio” y listo. Ya tienes tu primer repositorio creado.
1. Crear ramas (branches) en GitHub
Branch se puede ver como el mapa lineal de los commits que has realizado al archivo. Cuando empezamos un proyecto con GitHub, automáticamente nos crea una rama llamada master, a partir de la cual comenzaremos a crear nuestras propias ramas.
Entra en tu repositorio.
En la parte superior de la página da clic en Rama actual. En la lista de rama selecciona la rama llamada master, que será nuestra base para la que estamos creando.
Luego presiona New Branch (Nueva Rama)
Añade el nombre de tu nueva rama
Selecciona la rama actual (master) en la que se basara la nueva rama
Presiona Create Branch (Crear Rama)
Por acá encontrarás tips y trucos para GitHub que te harán ser un pro del control de versiones.
1. Entender los commits de GitHub
Commit es la denominación que se le da a los cambios guardados en Github. En otras palabras, commit es la acción de subir los archivos con los cambios realizados en tus repositorios y guardarlos.
Para realizar el commits de Github debes seguir los siguientes pasos:
1. Se debe verificar el estado de nuestro repositorio ejecutando el siguiente comando:
* git status
Una vez realizado el comando anterior, te aparecerá una lista con los archivos que fueron modificados y con los que están agregados al índice, listos para subir.
Si aún existen archivos sin agregar al índice, debes ejecutar el siguiente comando:
git add
De esta forma se añaden todos los cambios pendientes.
1. Ahora vamos a generar el commit ejecutando el siguiente comando:
git commit -m "Un comentario de los cambios realizados"
Es importante que en este paso agregues una descripción clara, esta se guardará en el historial y podremos entender mejor los cambios más adelante.




##### Bibliografia
https://platzi.com/blog/que-es-github-como-funciona/
