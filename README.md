# Github

## Introducción
GitHub es una plataforma en la nube donde puedes almacenar y compartir ficheros de texto o código par colaborar con otros usuarios. Almacenar estos ficheros en un repositorio de GitHub te permite: mostrar o compartir tu trabajo, y hacer seguimiento y gestionar los cambios que se vayan produciendo en su contenido a lo largo del tiempo.

## Tareas basadas en repositorios para trabajo en clase

GitHub ofrece funcionalidades muy interesantes para trabajar con prácticas relacionadas con código o archivos de texto. 
Comparado con la gestión tradicional de tareas (creación de un fichero comprimido y subida de dicho fichero a una plataforma de tipo Moodle o entrega por correo) tenemos las siguientes ventajas:

- Posibilidad de ver el contenido de los ficheros a través de un nvegador web sin necesidad de descargarlo.
- Podemos crear conversaciones para realizar comentarios sobre la tarea.
- Posibilidad de hacer comentarios haciendo referencia a líneas concretas del contenido, a otros comentarios, archivos, etc.
- Colaboración entre distintas personas para tareas en grupo. Visibilización de las aportaciones de cada persona al trabajo común.

En los repositorios de GitHub se pueden subir y editar ficheros de texto plano o en formato de lenguajes de marcas como [Markdown](https://markdownlivepreview.com/). , que se pueden enriquecer con referencias a otros contenidos como imágenes, enlaces a recursos internos (otros ficheros del repositorio) o externos (direcciones url). 

## Creación de cuentas en Github
Para poder usar Github, tienes que registrarte [creando una cuenta de Github](https://docs.github.com/es/get-started/start-your-journey/creating-an-account-on-github) con el usuario y la contraseña que quieras, y proporcionando una cuenta de correo real (por ejemplo, una cuenta de google, puedes crear las que quieras).

## El flujo de trabajo de Github
A continuación se describen los principales componentes del [workflow estándar de gestión de cambios](https://docs.github.com/es/get-started/start-your-journey/hello-world) de los contenidos de los repositorios.
### Repositorios
En Github lod contenidos se organizan en Repositorios. Un repositorio es una elemento de agrupación de elementos relacionados, como archivos, imágenes, vídeos o incluso otras carpetas. Los repositorios incluyen por defecto un archivo LÉAME o README con información sobre el proyecto. Los archivos LÉAME están escritos en Markdown. 

### Ramas
Github permite mantener de forma simultánea varias versiones del contenido de un repositorio, que son cocnocidas como ramas. Cada repositorio se crea por defecto con la rama main o principal, que tendría el contenido definitivo. Para poder probar cambios (añadir o modificar contenidos) antes de hacerlos "definitivos", podemos crear una nueva rama del repositorio a partir de la rama principal. Esa nueva rama tendrá una copia de los contenidos de la rama principal. En esa nueva rama podemos implementar y probar los cambios que queramos sin afectar al contenido de la rama principal. Cuando estemos seguros de que los cambios en la nueva rama están correctos, confirmaremos los cambios en la nueva rama y solicitaremos entonces la incorporación de esos cambios en la rama principal, que pasarán así a ser "definitivos".

### Commits o confirmaciones
En GitHub, los cambios guardados dentro de una rama se llaman confirmaciones o commits. Cada uno tiene un mensaje de confirmación asociado, que sirve para describir el motivo del cambio. Los mensajes de confirmación capturan la historia de tus cambios que sirven para que otros usuarios puedan entender lo que hiciste y por qué (o a ti mismo para recordarlo).

### Pull requests o solicitudes de cambio
Para que los cambios confirmados en una rama se puedan incorporar o fusionar con otra rama, hay que abrir una solicitud de cambio. Cuando abres una solicitud de cambios, estás proponiendo tus cambios y solicitando que alguien revise e integre tu contribución y la fusione en su rama.
En nuestro ejemplo, la solicitud de cambio se envía desde la nueva rama a la rama principal y serás tú quien tenga que confirmar la solicitud por ser dos ramans de tu repositorio. Lo normal es que haya en el repositorio otros _colaboradores_ a los que les pedirías su revisión, que podrían comentar o proponer cambios en la solicitud de cambios antes de combinar los cambios en la rama principal.
### Merge o fusión de ramas
Una vez aceptadas todas las propuestas de cambio, el paso final consistirá en fusionar la segunda rama en la rama principal. Así, los cambios en la segunda rama se incorporarán a la principal.

[Tarea 1: flujo de trabajo de solicitud de cambios de GitHub.](Tarea1.md)

## Github como herramienta de Colaboración

Hay que ser colaborador para poder solicitar cambios en el contenido de un repositorio? No necesariamente.

GitHub ofrece dos mecanismos básicos para la colaboración en un determinado repositorio:

- Permisos de colaboradores - Se pueden agregar colaboradores a un repositorio para que puedan realizar cambios. Este método es útil si tenemos clara la identidad de todas las personas que van a colaborar en el repositorio.
- Forks y Pull Requests: Mecanismo utilizado por defecto. Permite que personas que no tienen acceso de escritura al repositorio puedan hacer una copia del mismo en su propia cuenta y enviar los cambios para que la persona dueña del repositorio original decida si quiere o no integrarlos. Muy útil en proyectos de Código Abierto, donde las personas colaboradoras no se conocen entre sí.
   

Tarea 2 ->  Trabajo con repositorios, issues, forks y pull requests

- Haz un fork del repositorio localizado en la siguiente url: https://github.com/curso-github-cefire/sesion3-practica. A partir de este momento todas las tareas que se indican se deben realizar en tu repositorio (el que has clonado mediante el fork).
- Realiza un primer commit para poner tu nombre y apellidos en el fichero README.md
- Crea 3 issues con los siguientes títulos. Si no ves la pestaña de issues, actívala desde los ajustes (settings) del repositorio.
            Añadir 3 libros
            Añadir 3 películas
            Añadir 3 discos
- Crea una milestone denominada Tareas sesión 3-2 que contenga los 3 issues creados.
- Modifica los ficheros correspondientes y realiza 3 commits para realizar cada una de las tareas que se indican en los issues. El mensaje del commit debe hacer que se cierren los issues correspondientes de manera automática.
- Haz una captura de pantalla de los comandos que has utilizado para hacer los commits y subir los cambios a GitHub.
- Incluye las capturas de pantalla en el repositorio dentro de la carpeta capturas. Añádelas también al repositorio de manera que queden guardadas en tu repositorio en GitHub.
- Realiza una pull request indicando en el mensaje que has completado la tarea.


![Tarea Website](Website.md)

Tareas basadas en repositorios para trabajo en clase 
![Utilidades dos repo para traballar nas aulas](Traballo_aulas_repos.md)   

