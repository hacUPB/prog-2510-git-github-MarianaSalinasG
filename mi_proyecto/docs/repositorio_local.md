# Creación de repositorios.

Es importante que Git esté enlazado con la cuenta de la persona que se encuentra codificando, mediante el comando: `git config --list`.
- `user.name nombre` y `user.email correo@upb.edu.co`.

Con ayuda de los commits y esos comandos se permite asociar a quien pertenece esos cambios.


Se puede usar tambien el comando `git config --global` en caso tal de que la configuración no sea la deseada; se utiliza ese y alguno de los comandos mencionados anteriormente para enlazarlo a una identidad nueva.
Ahora bien, con el comando `git config --list` para corroborar los cambios de la información, y siempre se toma en cuenta la última configuración realizada.

Luego, se crea con ayuda de `mkdir` un directorio nuevo y luego nos dirigimos a el con ayuda del comando `cd`.

Se inicia el repositorio con ayuda del comando `git init`; allí se crea un directorio oculto `.git` que contiene todos los archivos necesarios para el buen funcionamiento del repositorio.

Es importante siempre conocer el status del repositorio mediante el comando `git status`.
- Este comando `git status` si todo se encuentra en óptimas condiciones debe entregarnos una respuesta del siguiente tipo:

```
$ git status
On branch main

No commits yet

Nothing to commit (create/copy files and use "git add" to track)
```
En el repositorio se puede hacer uso de todos los comandos explicados previamente como: ``touch``. Es importante agregar todos los archivos con cambios al **staging area**, con ayuda del comando `git add` si se escribe `git add .` se llevan a esa área todos los archivos del directorio donde se ubica.  

Es muy importante el uso de las confirmaciones o los commits, que permite guardar los cambios realizados al repositorio mediante el comando `git commit -m "Descripciópn de la accion realizada"`, guardando en el repositorio la versión de todos los archivos que tenemos en la zona de **Stage**. 