# Ejercicio2-branch

## Clonacion del repositorio

``` code
bae2@jpexposito-VirtualBox:~/Documentos$ git clone https://github.com/materancode/Ejercicio2-branch.git
Clonando en 'Ejercicio2-branch'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Recibiendo objetos: 100% (3/3), listo.

```
## SE incluye el commit

``` code
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio2-branch$ git add .
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio2-branch$ git commit -m "Se incluye la descripcion inicial de la tarea"
[main f6e6c1d] Se incluye la descripcion inicial de la tarea
 1 file changed, 18 insertions(+), 1 deletion(-)
 rewrite README.md (100%)
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio2-branch$ ls
README.md

```
## Se ha subido con el comando "Push"

```code
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio2-branch$ git push --set-upstream origin ejercicio2-branch
Username for 'https://github.com': materancode
Password for 'https://materancode@github.com': 
Total 0 (delta 0), reusados 0 (delta 0), pack-reusados 0
remote: 
remote: Create a pull request for 'ejercicio2-branch' on GitHub by visiting:
remote:      https://github.com/materancode/Ejercicio2-branch/pull/new/ejercicio2-branch
remote: 
To https://github.com/materancode/Ejercicio2-branch.git
 * [new branch]      ejercicio2-branch -> ejercicio2-branch
Rama 'ejercicio2-branch' configurada para hacer seguimiento a la rama remota 'ejercicio2-branch' de 'origin'.
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio2-branch$ 


```
