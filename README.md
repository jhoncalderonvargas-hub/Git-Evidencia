# Git-Evidencia
Proyecto para actividad de aprendizaje y primeros pasos con git y github
Versión de git
git version
git config --global user.email "myemail@example.com"
// Iniciar un nuevo repositorio
// Crear la carpeta oculta .git
git init
// Ver que archivos no han sido registrados
git status
// Agregar todos los archivos para que esté pendiente de los cambios
git add .
// Crear commit (fotografía del proyecto en ese momento)
git commit -m "primer commit"
// Muestra la lista de commit del mas reciente al más antigüo
git log
git remote add origin https://github.com/bluuweb/tutorial-github.git
git push -u origin master
Al ejecutar estas líneas de comando te pedirá el usuario y contraseña de tu cuenta de github.

// Nos muestra en que repositorio estamos enlazados remotamente.
git remote -v
#Push
Al ejecutar el comando git push estaremos subiendo todos los cambios locales al servidor remoto de github, ten en cuenta que tienes que estar enlazado con tu repositorio, para eso puedes utilizar git remote -v luego ejecuta:

git push
#Pull
Cuando realizamos cambios directamente en github pero no de forma local, es esencial realizar un pull, donde descargaremos los cambios realizados para seguir trabajando normalmente.
Es importante estar enlazados remotamente, puedes verificar con: git remote -v, luego ejecuta:

git pull
