
## Trabajo colaborativo con forks y pull requests

Por si no te has dado cuenta, tú sólo tienes permisos de lectura sobre los contenidos de este repositorio https://github.com/jbardals/dixitalizacion-git

Qué sucede si intentas crear o editar un fichero en el repositorio y guardar los cambios? Te indica que tienes que realizar un fork:
![](imgs/fork_message.png)

Yo ahora, como profesor, quiero que realices en este repositorio la entrega de las tareas propuestas en el mismo pero sin que puedas modificar o editar los contenidos del repositorio. Para ello te voy a pedir que realices los siguientes pasos de entrega:
## Entrega 1.3
- Haz un fork de este repositorio.
  ![](imgs/create_fork.png)
  A partir de este momento todas las tareas que se indican a continuación se realizarán en tu repositorio (el que has clonado mediante el fork), que tendrá una url .....https://github.com/TUCUENTADEUSUARIO/dixitalizacion-git
- Ya en tu repositorio clonado: Edita el fichero Entrega.md y añade los siguientes datos:
    - tu nombre y apellidos
    -  url del repositorio que creaste en la Tarea 1.
- Realiza un commit de los cambios del fichero en tu repositorio.
- Realiza una pull request indicando en el mensaje que has completado la tarea.
  ![](imgs/create_pull_request.png)
- A mí me llega un aviso de solicitud de entrega como éste:
 ![](imgs/chegada_pull_request.png)

![](imgs/Solicitud_entrega.png)
- Accedo al fork correspondiente y visualizo la entrega:
![](imgs/check_fork.png)
![](imgs/listado_forks.png)

## IMPORTANTE: 
### Para finalizar, debes realizar la entrega de la tarea en Moodle. Para ello, copia en la tarea de Moodle la url de tu  repositorio https://github.com/TUCUENTADEUSUARIO/dixitalizacion-git, como puedes leer en las instrucciones de entrega de la misma.



## Flujo de trabajo para entrega de prácticas individuales
El flujo de trabajo anterior es adecuado para la entrega de tareas individuales. Este es el resumen de todos los pasos:
- O/a docente crea del repositorio con el código base de la tarea
- Incluye un archivo README con enunciado o descripción de la tarea
- Cada alumno realiza un fork del repositorio
- El alumno trabaja en su copia del repositorio
- Cuando quiera solicitar ayuda o revisión del profesor, el alumno genera una pull request
- El profesor proporciona retroalimentación mediante comentarios en la pull request o en un determinado commit individual
- Opcionalmente se pueden utilizar los issues y las citas de usuario para solicitar la intervención del profesor
- Los comentarios se pueden realizar a nivel de línea de código
- Cuando el alumno finaliza la tarea, genera una pull request
- El profesor revisa la pull request y opcionalmente hace comentarios sobre la misma
- Al finalizar, el profesor cierra la pull request

### Ventajas

- Sencillez
- Flujo de trabajo parecido al funcionamiento normal de GitHub

### Desventajas

- Los repositorios de las tareas de los alumnos son públicos
- Es difícil determinar el nombre del alumno a partir del usuario de GitHub
- Cada alumno es dueño de su repositorio
- En caso de tener integración con Travis, cada alumno deberá activarla en su repositorio

Otra opción sería el uso de Organizaciones y [Classrooms](https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom)
