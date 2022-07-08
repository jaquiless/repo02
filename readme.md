``git init`` 
# Crea un nuevo repositorio local GIT.
``git clone``
# Copia un repositorio, si el repositorio esta en un servidor remoto, se añade el URL.
📌EJEMPLO: git clone nombredeusuario@host:/path/to/repository
# A la inversa, para copiar un repositorio local.
📌EJEMPLO: git clone /path/to/repository  
``git add``
# Se usa para agregar archivos al área de preparacion.
EJEMPLO: git add <temp.txt>  
``git commit``
# Creara una instantanea de los cambios y la guardara en el directorio git.
📌EJEMPLO: git commit -m "El mensaje que acompaña al commit va aqui"  
``git config``
# Puede ser usado para establecer una configuración específica de usuario, como el email, nombre de usuario y tipo de formato, etc, por ejemplo, el siguiente comando se usa para establecer un email.
📌EJEMPLO: git config --global user.email "tuemail@ejemplo.com"  
``git status``
# Muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados.
``git log``
# Se usa para ver el historial del repositorio listando ciertos detalles de la confirmación. Al ejecutar el comando se obtiene una salida como ésta.
📌EJEMPLO: commit 15f4b6c44b3c8344caasdac9e4be13246e21sadw  
Author: Alex Hunter <alexh@gmail.com>  
Date:   Mon Oct 1 12:56:29 2016 -0600>  
``git push``
# Se usa para enviar confirmaciones locales a la rama maestra del repositorio remoto. Aquí está la estructura básica del código.
📌EJEMPLO: git push  origin <master>