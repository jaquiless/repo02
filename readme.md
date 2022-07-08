git init <crea un nuevo repositorio local GIT>
git clone <copia un repositorio, si el repositorio esta en un servidor remoto, se añade el URL. EJEMPLO: git clone nombredeusuario@host:/path/to/repository>
<a la inversa, para copiar un repositorio local:  git clone /path/to/repository>
git add <se usa para agregar archivos al área de preparacion. EJEMPLO: git add <temp.txt>>
git commit <creara una instantanea de los cambios y la guardara en el directorio git: EJEMPLO: git commit -m "El mensaje que acompaña al commit va aqui">
git config <puede ser usado para establecer una configuración específica de usuario, como el email, nombre de usuario y tipo de formato, etc. Por ejemplo, el siguiente comando se usa para establecer un email: EJEMPLO: git config --global user.email "tuemail@ejemplo.com">
git status <muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados>
git push <se usa para enviar confirmaciones locales a la rama maestra del repositorio remoto. Aquí está la estructura básica del código: EJEMPLO: git push  origin <master> >