¿Qué ventaja tiene registrar las dependencias del proyecto en requirements.txt en lugar de compartir la carpeta .venv?
- Como .venv no será guardado en el repositorio, gracias a que está separado, las dependencias no se pierden.

¿Por qué el repositorio que tienes ahora en tu computadora no es el mismo concepto que el fork creado en GitHub?
-Por que es una copia de la maquina inicial, por lo que no viene con el entorno con el que se hizo


## Preguntas individuales

1. ¿Cómo identificaste el comando necesario cuando la práctica no lo proporcionó?
    - Siguiendo la estructura lógica de cada uno. Ejemplo: todos inician con git, seguidos de la acción principal como "add", "commit" o "branch", después va el acompañamiento de dicho comando como "-m 'Título'", "-u origin", "-c nombre".

2. ¿Qué diferencia existe entre preparar un archivo para un commit y crear el commit?
    - Preparar el archivo es añadir con add, todos los elementos alterados para que se encuentren listoas para formar una versión. Hacer el commit es dar un guardado a esa versión individual.

3. ¿Cómo puedes comprobar en qué rama estás trabajando?
    - git branch

4. ¿Cómo puedes determinar qué archivos fueron modificados antes de registrarlos?
    - git status

5. ¿Cómo puedes observar exactamente qué cambió dentro de un archivo?
    - Al hacer el pull, todos los archivos modificados aparecen de un color diferente, para así identificar cuales cambiaron.

6. ¿Por qué debe reconstruirse .venv después de obtener un repositorio?
    - Por que al este ser evitado por el .gitignore, no es almacenado dentro del repositorio, por lo que al hacer el fork, este prácticamente no existe.

7. ¿Qué relación existe entre requirements.txt y .gitignore?
    - Ambos son archivos que guardan información funcional del proyecto.

8. ¿Por qué la colaboración se realiza desde una rama y no directamente desde main?
    - Para no alterar la información de la rama principal y causar posibles problemas.

9. ¿Por qué una solicitud de cambios no requiere crear un Pull Request nuevo?
    - Porque el nuevo cambio se almacena dentro del mismo pull request activo.

10. Después de realizar el merge en GitHub, ¿por qué todavía es necesario actualizar el repositorio local?
    - Porque, si bien están conectados, funcionan independientemente, los cambios entre uno y otro se deben hacer de forma manual.
