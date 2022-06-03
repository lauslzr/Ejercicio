# Creando un repositorio local
Mediante el comando Git initit creo un repositorio local

Creamos un fichero llamado readme.md 

Hacemos Git init

Después hacemos un Git status para ver la situación de nuestros ficheros

Añadimos el fichero con el comando Git add y vuelvo a hacer Git status para ver el estado

El siguiente paso es enviar nuestro fichero del staging area al repositorio local. Para ello utilizo git committ -m "nombre que quiera"

Para el repositorio remoto utilizamos GitHub. Creo en él un repositorio que voy a llamar Ejercicio. Copio el enlace creado y los asocio con el comando git remote add origin https://github.com/lauslzr/Ejercicio.git, que es mi enlace, después hago git remote -v y git branch -M main. Por último hago git push -u origin main y ya lo tendría aosiciado. 
  
Utilizo el comando git remote -v para ver los repositorios que tenemos asociados (entre el local y el remoto)

Si escribo alguna actualización tengo que guardar el documento, realizar de nuevo git add ., miro el git status, vuelvo a hacer git commit y por último git push.