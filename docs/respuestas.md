1. Pensé en lo que quería lograr y lo relacioné con pasos anteriores de la práctica. También me ayudó lo que Git sugiere en git status, y si no, lo busqué en la documentación de Git o en GitHub.

2. Preparar (git add) elige qué cambios van a entrar. Commit (git commit) los guarda en el historial.

3. Con git branch (la actual lleva *) o git status.

4. Con git status, que lista los archivos modificados y nuevos.

5. Con git diff (o git diff --staged si ya los preparaste). Muestra línea por línea lo quitado y lo agregado.

6. Porque .venv no se sube a GitHub: es propio de cada computadora. Al clonar, lo creas de nuevo e instalas las dependencias.

7. .gitignore evita subir .venv. requirements.txt sí se sube, porque con él se recrea el entorno.

8. Para que main siempre quede estable. Trabajas en tu rama y entra a main solo tras revisarse.

9. Porque el PR está ligado a la rama. Haces nuevos commits y git push, y el mismo PR se actualiza solo.

10. Porque el merge solo ocurrió en GitHub. Tu main local sigue viejo, así que haces git checkout main y git pull.