# dixitalizacion-git

GitHub es una plataforma en la nube donde puedes almacenar, compartir y colaborar con otros para escribir código. Almacenar tu código en un repositorio de GitHub te permite: mostrar o compartir tu trabajo, y hacer seguimiento y gestionar los cambios en tu código a lo largo del tiempo.

![](Website.md)

## 1. Creación de sitios web en GitHub

GitHub es un servicio muy interesante porque ofrece alojamiento gratuito para sitios estáticos. Tenemos a nuestra disposición varias opciones para publicar documentación:

- Utilizar directamente GitHub. Es la opción más sencilla. Se pueden crear una serie de archivos en formato markdown u orgmode con enlaces relativos entre ellos. Al acceder a través de GitHub los archivos se visualizarán con el formato correcto (negrita, cursiva, encabezados, código,…). Un ejemplo es el repositorio de este curso. Los archivos estarán accesibles a través de https://github.com.
- Utilizar GitHub Pages con el tema por defecto de Jekyll. La segunda opción consiste en activar GitHub Pages en el repositorio que estemos utilizando y añadir archivos en formato HTML o markdown. Los archivos se publicarán en la ruta correspondiente al repositorio utilizado y el nombre de archivo usado. Los archivos con nombre index serán accesibles a través de la carpeta contenedora: así, un archivo index.html dentro de la carpeta pagina1 estará accesible a través de la URL https://MINOMBREDEUSUARIO.github.io/nombrerepositorio/pagina1/; un archivo con nombre a1.html dentro de la misma carpeta será visible en https://MINOMBREDEUSUARIO.github.io/nombrerepositorio/pagina1/a1.html. Si utilizamos enlaces relativos podremos construir un sitio estático formado por todos los archivos.

Características de GitHub Pages
- Servicio de alojamiento web estático (sin lógica de servidor ni base de datos).
- Hasta 1 GB de alojamiento (ver límites de uso).
- Tecnologías que se pueden utilizar: HTML, CSS y JavaScript. También se puede publicar cualquier otro tipo de archivos para su descarga vía web (PDF, DOC, ZIP,…)

Se puede crear un sitio web asociado a cualquier repositorio. Algunos ejemplos de uso:

- Documentación relacionada con el código del repositorio
- Trabajos o presentaciones de alumnos
-  ...

Para crear el sitio web seguir los siguientes pasos,   
- Crear repositorio -> tal y como se indica en el aptdo Crear un repositorio en la url https://docs.github.com/es/pages/getting-started-with-github-pages/creating-a-github-pages-site#creating-your-site:
- Crear sitio -> vamos a publicar desde una rama. Sigue los pasos del aptdo Publicacion desde una rama en https://docs.github.com/es/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-from-a-branch
  
  En la pagina principal del repositorio, busca abajo a la derecha la sección Deployments y pulsa en github-pages.
  https://TUNOMBREDEUSUARIO.github.io/nombrerepositorio.
  
![](imgs/deploy_github-pages.png)

Incluye un fichero index.html con tu nombre y tus apellidos. Comprueba que puedes acceder vía web al sitio publicado.

## 2. Tareas basadas en repositorios para trabajo en clase

GitHub ofrece funcionalidades muy interesantes para trabajar con prácticas relacionadas con código o archivos de texto. Comparado con la gestión tradicional de tareas (creación de un fichero comprimido y subida de dicho fichero a una plataforma de tipo Moodle o entrega por correo) tenemos las siguientes ventajas:

    Posibilidad de ver el código en el explorador web sin necesidad de descargarlo
    Podemos crear conversaciones para realizar comentarios sobre la tarea
    Posibilidad de hacer comentarios directamente sobre el código, haciendo referencia a líneas concretas, otros comentarios, commits, archivos, etc.
    Opción de realizar tests automáticos para corrección de tareas o autoevaluación del alumnado
    Colaboración entre distintas personas para tareas en grupo. Visibilización de las aportaciones de cada persona al trabajo común.


## Entrega

crearse el fork del mio, añadir un fichero url_GithubPages y hacer push
