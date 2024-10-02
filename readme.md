# clase 05
## para crear un repositorio git
``` sh
git init
```
## ver el estado de los archivos los archivos y en que area.
```sh
git status
```
## para que git controle los cambios de los archivos.(area de confirmacion = staging area)
### (este paso se tiene que hacer cada vez que medificas un archivo y lo queres guardar.)
```sh
git add readme.md
git add <nombre-archivo> <nombre-archivo> (varios archivos)
```
## para pasarlo a local repo
```sh
git commit -m "introduccion a git, primeros comandos"
```
## para ver lo que modificamos 
```sh
git diff
```
## si se bloquea
```sh
se apreta la Q y salis.

```
## Resumen
```sh
1. se modifica el archivo
2. se hace un git status
3. se hace un git add <nombre del archivo>
4. se hace un git status.
5. se hace un git commit -m "explicacion del cambio"
6. se hace un git status.
7. el git diff (se ve lo que se modifico en comparaciongit)