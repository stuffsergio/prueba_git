## Documentación Ejercicio Entornos de Desarrollo

- Paso 1 - crear el proyecto en el equipo
  `mkdir prueba_git`

- Paso 2 - abrir el proyecto en un IDE (VS Code)
  `cd prueba_git` && `code .`

- Paso 3 - crear los archivos dentro del proyecto

- Paso 4 - una vez terminado el proyecto, es necesario crear el repositorio en GitHub donde vamos a subir nuestro proyecto.
  Dentro de GitHub, creamos un repositorio (nombre, descripción, público/privado, etc.)

- Paso 5 - iniciamos el control de versiones de Git dentro de nuestro proyecto (local)
  `git init`

- Paso 6 - añadimos los archivos que queremos subir al repositorio
  `git add index.html`
  Realizamos un commit para guardar los cambios de los archivos añadidos
  `git commit -m "initial commit"`
  Renombramos la rama actual a "main"
  `git branch -M main`
  Vinculamos el proyecto al repositorio en GitHub
  `git remote add origin https://github.com/stuffsergio/prueba_git.git`
  Y subimos el commit (cambios guardados) al repositorio
  `git push -u origin main`

- Paso 7 - si es necesario modificar algo o guardas cambios nuevos haremos
  `git add .` - para preparar todos los archivos sin guardar a un mismo commit
  Realizar el commit con los cambios guardados
  `git commit -m "nuevos cambios"`
  Pusheamos el commit al repo de GitHub
  `git push`

Extra:

- Para comprobar el estado del repositorio (si hay cambios por añadir, los archivos ya añadidos, commit por pushear, etc.), usamos:
  `git status`
- Para ver el registro de commits realizados
  `git log`
