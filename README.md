# Comandos Git

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)

___

*Si te interesan mis alias de Git, puedes revisar mi `.bash_profile`, aquí: https://github.com/fernandomireles/bash_profile/blob/main/.bash_profile*

### Crear y obtener proyecto (online)

| Comando | Descripción |
| ------- | ----------- |
| `git clone [dirección-remota] [nombre-subcarpeta-local]` | Crea una __copia local__ de un repositorio remoto. |
| `git init` | Inicializa un __repositorio local__ de Git (para prepararlo para la conexión a un CodeCommit). |

### Comandos básicos

| Comando | Descripción |
| ------- | ----------- |
| `git status` | Muestra __lo que se ha añadido o no__ a la confirmación pendiente en el repositorio local. |
| `git status -sb` | Muestra lo que se ha añadido o no a la confirmación pendiente en el repositorio local __en un formato conciso__. (M = modificado, A = añadido, D = eliminado, etc.) |
| `git diff HEAD` | Muestra los cambios __entre la confirmación pendiente y la última confirmación__ en el repositorio local. |
| `git add [nombre-del-archivo]` | Añade __archivos específicos__ a la confirmación pendiente en el repositorio local. |
| `git add ` | Añade __todos los archivos nuevos__, modificados y eliminados a la confirmación pendiente en el repositorio local. |
| `git commit -m "[Mensaje descriptivo]"` | Finaliza la confirmación pendiente en el repositorio local e incluye la especificación de un __mensaje descriptivo__ de confirmación. |
| `git pull ` | Se descargan las modificaciones del repositorio remoto para __actualizar el repositorio local__. |
| `git push ` | Se publica del repositorio local __al repositorio remoto__ una vez que la información de seguimiento se ha establecido (con los _git add_ y el _git commit_ correspondiente. |
| `git rm -r [nombre-del-archivo.txt]` | Elimina un archivo (o carpeta). |

### Ramas y fusiones

| Comando | Descripción |
| ------- | ----------- |
| `git branch` | Muestra una lista de las ramas que existen en este proyecto (el asterisco señala la rama activa). |
| `git branch -a` | Muestra una lista de todas las ramas (locales y remotas). |
| `git branch [nombre de la rama]` | Crea una nueva rama. |
| `git branch -d [nombre de la rama]` | Elimina una rama local. |
| `git push origin --delete [nombre de la rama]` | Elimina una rama remota. |
| `git checkout -b [nombre de la rama]` | Crea una nueva rama y nos desplaza hasta ella. |
| `git checkout -b [nombre de la rama] origin/[nombre de la rama]` | Clona una rama remota y nos desplaza hasta ella. |
| `git branch -m [nombre de la rama antigua] [nombre de la rama nueva]` | Renombra una rama local. |
| `git checkout [nombre de la rama]` | Cambia a una rama concreta. |
| `git checkout -` | Cambia a la última rama activa. |
| `git checkout -- [nombre-del-archivo.txt]` | Descarta cambios en un archivo. |
| `git merge [nombre de la rama]` | Combina una rama concreta con la rama activa. |
| `git merge [nombre de la rama de origen] [nombre de la rama de destino]` | Combina una rama concreta (rama de origen) con una rama nueva (rama de destino). |
| `git stash` | Revierte los últimos cambios y errores en el directorio actual. |
| `git stash clear` | Revierte todos los cambios en el directorio actual. |

### Inspeccionar y comparar

| Comando | Descripción |
| ------- | ----------- |
| `git log` | Ver cambios. |
| `git log --summary` | Ver cambios (en detalle). |
| `git log --oneline` | Ver cambios (resumido). |
| `git diff [source branch] [target branch]` | Vista previa de los cambios antes de hacer un merge. |

## Registro de cambios

`2022-10`

Features:
- Creación de este archivo.

## License

[comandos-git](https://github.com/fernandomireles/comandos-git) are released under [MIT license](https://github.com/fernandomireles/comandos-git/blob/main/LICENSE) . Copyright (c) [Fernando Mireles](https://github.com/fernandomireles).