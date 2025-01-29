# Para crear un repositorio remoto...

Necesitamos claramente una cuenta de GitHub o alguna plataforma que relice la misma función, para este caso emplearemos **GitHub** la plataforma con la que trabajamos.

Estando en la página de GitHub en el icono de laprte superior derecha ``+``, escogemos la opción ``New Repository``, en este espacio puedes darle carcterísticas propias al repositorio como: **Nombre, lenguaje y privacidad**. 

<img src= "Captura de pantalla 2025-01-29 a la(s) 14.18.38.png">

Una vez estemos dentro del repositorio que queremos enlazar con el directorio local, en la página de GitHub encontraremos un link propio del repositorio, debemos copiarlo y codificar en la consola de la siguiente manera:
``git remote add origin https://github.com/usuario_personal/simulacion.git``. De este modo se conectará el repositorio con el directorio ya escogido.

Dentro del repositorio al realizar cualquier cambio debemos hacer las debidas confirmaciones mediante el paso de los cambios por el **Stage** mediante ``git add`` y ``git commit -m "Mensaje explicatorio"` para sincronizar la información.`

## La importancia de sincronizar los commits locales con el repositorio remoto.

Si se desea sincronizar remoto debemos utilizar el comando ``push`` que se encarga de enlazar los repositorios: local y remoto, podemos usarlo mediante el comando:

``git push origin main``

Para finalizar, ``git status`` nos permite asegurarnos de que ambos repositorios estan hilados a el mismo commit.
De este modo todos los repositorios estarían sincronizados en la plataforma GitHub.  