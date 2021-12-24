# Resumen de los principales comandos en Git

## Links de interés
[Libro ProGit](https://git-scm.com/book/es/v2)

[Curso de Git de pildorasinformaticas.es](https://youtube.com/playlist?list=PLU8oAlHdN5BlyaPFiNQcV0xDqy0eR35aU)

[Curso de Git de Fazt](https://youtu.be/HiXLkL42tMU)

[Ramas **master** y **main**](https://jarv.is/notes/github-rename-master/)

## Principales comandos
|Comando|Descripción|
|-------|-----------|
|git config --list|Lista configuración de Git|
|git init|Inicializa un repositorio local|
|git add .|Agrega todos los archivos al área de intercambio (staging area)|
|git commit -m <descripción>| |
|git commit -am <descripción>|2 comamdos en uno: add + commit|
|git status -s| |
|git log --oneline| |
|git commit -- ammend|Abre el editor Vim|
|git push -u origin main|Sube del repositorio local a GitHub|

git pull                                              | Trae de GitHub al repositorio local
git tag <nombre> -m "<descripción>"                   |
git push --tags                                       |
git clone <url>                                       |
git remote add origin <url>                           |
git branch <nombre de la rama>                        |
git branch                                            | Muestra las ramas del proyecto y la rama en la que me encuentro
git checkout <nombre de la rama>                      | Para cambiar de rama
git merge <nombre de la rama>                         | El merge se debe hacer desde la rama master
git remote add origin <url del repositorio de GitHub> | Sube un repositorio local
git push -u origin master                             | Actualiza el repositorio remoto después de las modificaciones en el repositorio local
git branch -m master main                             | Mover la rama local de master a main
