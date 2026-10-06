Pregunta 1: ¿Cómo identificaste el comando necesario cuando la práctica no lo proporcionó?
Respuesta: Pensé en lo que quería lograr y lo relacioné con pasos anteriores de la práctica. También me ayudó lo que Git sugiere en git status, y si no, lo busqué en la documentación de Git o en GitHub.

Pregunta 2: ¿Qué diferencia existe entre preparar un archivo para un commit y crear el commit?
Respuesta: Preparar (git add) elige qué cambios van a entrar. Commit (git commit) los guarda en el historial.

Pregunta 3: ¿Cómo puedes comprobar en qué rama estás trabajando?
Respuesta: Con git branch (la actual lleva *) o git status.

Pregunta 4: ¿Cómo puedes determinar qué archivos fueron modificados antes de registrarlos?
Respuesta: Con git status, que lista los archivos modificados y nuevos.

Pregunta 5: ¿Cómo puedes observar exactamente qué cambió dentro de un archivo?
Respuesta: Con git diff (o git diff --staged si ya los preparaste). Muestra línea por línea lo quitado y lo agregado.

Pregunta 6: ¿Por qué debe reconstruirse .venv después de obtener un repositorio?
Respuesta: Porque .venv no se sube a GitHub: es propio de cada computadora. Al clonar, lo creas de nuevo e instalas las dependencias.

Pregunta 7: ¿Qué relación existe entre requirements.txt y .gitignore?
Respuesta: .gitignore evita subir .venv. requirements.txt sí se sube, porque con él se recrea el entorno.

Pregunta 8: ¿Por qué la colaboración se realiza desde una rama y no directamente desde main?
Respuesta: Para que main siempre quede estable. Trabajas en tu rama y entra a main solo tras revisarse.

Pregunta 9: ¿Por qué una solicitud de cambios no requiere crear un Pull Request nuevo?
Respuesta: Porque el PR está ligado a la rama. Haces nuevos commits y git push, y el mismo PR se actualiza solo.

Pregunta 10: Después de realizar el merge en GitHub, ¿por qué todavía es necesario actualizar el repositorio local?
Respuesta: Porque el merge solo ocurrió en GitHub. Tu main local sigue viejo, así que haces git checkout main y git pull.