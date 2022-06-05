# Resumen de los principales comandos en Git

Los cambios que haga aquí corresponden a los de la rama `prueba`. No se verán en la rama `main`.

## Links de interés
[Libro ProGit](https://git-scm.com/book/es/v2)

[Curso de Git de pildorasinformaticas.es](https://youtube.com/playlist?list=PLU8oAlHdN5BlyaPFiNQcV0xDqy0eR35aU)

[Curso de Git de Fazt](https://youtu.be/HiXLkL42tMU)

[Curso de Git de HolaMundo](https://www.youtube.com/watch?v=VdGzPZ31ts8&ab_channel=HolaMundo)

[Ramas **master** y **main**](https://jarv.is/notes/github-rename-master/)

## Principales comandos
|Comando|Descripción|
|-------|-----------|
|git --version|Devuelve la versión instalada de Git.|
|git config --global user.name "`nombre`"|Configura el nombre de usuario en forma global, no por proyecto. El nombre debe estar entre comillas.|
|git config --global user.email `dirección de correo electrónico`|Configura la dirección de correo electrónico del usuario en forma global, no por proyecto. La dirección de correo electrónico NO debe estar entre comillas.|
|git config --global core.editor "code --wait"|Configura a VS Code como el editor de texto por defecto.|
|git config --global -e|Abre el archivo de configuración global en el editor de texto por defecto.|
|git config --global core.autocrlf `true`|Configuración para Windows. En caso de SO Linux o Mac reemplazar `true` por `input`.|
|git config -h|Entrega un listado de todas las configuraciones.|
|git config --list|Lista la configuración de Git.|
|git init|Inicializa un repositorio local.|
|git add `nombre de archivo`|Agrega el archivo indicado en el área de intercambio (staging area). Por ejemplo, en caso de que ponga `*.txt` como nombre de archivo, va a agregar todos los archivos .txt al área de intercambio. En caso de querer agregar más de un archivo hay que separar sus nombres con un espacio.|
|git add .|Agrega todos los archivos al área de intercambio (staging area)|
|git commit -m "`mensaje`"|Se compromete el trabajo, es decir se envía al repositorio local. El mensaje debe estar entre comillas y debe tener sentido. El primer _commit_ debe decir "Commit inicial".|
|git commit|Abre el editor de texto por defecto para solicitar que agreguemos el mensaje. Después de guardar y cerrar el editor se envían los cambios al repositorio local.|
|git commit -am "`mensaje`"|2 comamdos en uno: add + commit|
|git rm `nombre de archivo`|Elimina el archivo cuyo nombre se indica y envía el cambio al área de intercambio.| 
|git mv `nombre de archivo` `nuevo nombre de archivo`|Renombra el archivo a su nuevo nombre.|
|git status -s|Muestra el estado actual del repositorio. El `-s` es opcional, depende de como quiera mostrar el estado.|
|git diff|Muestra las diferencias entre las versiones anteriores y alctuales. NOTA: Se sale de la pantalla presionando la letra u, luego q.|
|git diff --staged|Muestra los cambios de los archivos en la etapa de intercambio.|
|git log --oneline|Muestra el historial de cambios.|
|git commit -- ammend|Abre el editor Vim|
|git push -u origin main|Sube del repositorio local a GitHub|
|git pull|Trae de GitHub al repositorio local|
|git tag `nombre` -m "`descripción`"| |
|git push --tags| |
|git clone `url`|Clona el repositorio remoto en el directorio actual (`pwd` para ver el directorio actual). Al clonar se crea una carpeta cuyo nombre coincide con el del repositorio remoto.|
|git remote add origin `url`| |
|git branch `nombre de la rama`| |
|git branch|Muestra las ramas del proyecto y la rama en la que me encuentro.|
|git checkout -b `nombre de la rama`|Crea la rama cuyo nombre se indica.|
|git checkout `nombre de la rama`|Cambia a la rama cuyo nombre se indica.|
|git merge `nombre de la rama`|El merge se debe hacer desde la rama master|
|git remote add origin `url del repositorio de GitHub`|Sube un repositorio local|
|git push -u origin main|Actualiza el repositorio remoto después de las modificaciones en el repositorio local|
|git branch -m master main|Mover la rama local de master a main|

## Notas
La gran ventaja de Git Bash es que utiliza los mismos comandos que Linux.

|Comando|Descripción|
|-------|-----------|
|code .|Abre VS Code.|
|clear|Limpia la terminal.|
|cat `nombre de archivo`|Muestra el contenido del archivo.|

[Linux Command Line Cheat Sheet](./davechild_linux-command-line.pdf)
[Atajos](https://www.howtogeek.com/howto/ubuntu/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/)