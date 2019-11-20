### Instalación de Git
_sudo apt install git_
### ¿Cuál es la versión de Git instalada?
_git --version_
### Nombre y correo electrónico del usuario Git
_git config --global user.name "Alan Brito Delgado"_
_git config --global user.email "alan.brito.delgado.1972@gmail.com"_
### Cacheo de la contraseña durante la sesión
_git config --global credential.helper 'cache --timeout=36000_
## Cambio de directorio
## Clonación de repositorios //modificacion RRN
_git clone [url]
## Vista de archivos y directorios en forma de árbol
## Actualización de un repositorio en local
## Contenido de un directorio
 ls
## Contenido de un fichero
## Creación de un fichero vacío
_git touch
## Edición de un fichero
_git nano nombrefichero
## Estado de un repositorio
## Adición de ficheros y directorios al índice de elementos a tener en cuenta en el próximo commit
## Confirmación de cambios realizados
## Actualización en GitHub de los cambios realizados en local
## Adición de ficheros y directorios al índice de elementos a tener en cuenta en el próximo commit.
## Registro de cambios
## Etiquetado de versiones
## Listado de todas las etiquetas existentes con sus correspondientes descripciones
## Actualización de las etiquetas en el repositorio remoto
## Creación de la rama experimentocolores y cambio de contexto hacia esa rama
_git checkout -b experimentocolores
## Actualización del repositorio remoto indicando que los cambios se hacen desde una rama distinta a la principal
_git push --set-upstream origin experimentocolores 
## Cambio de contexto hacia la rama master
_git checkout master 
## Fusión de ramas
_git merge experimentocolores
_git push

