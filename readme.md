#Creacion del repositorio Repo01 

1. Primero el repositorio 'Repo01' ha sido creado en local accediendo desde el terminal de git bash a la carpeta indicada y ejecutando el comando 'git init'.
2. Para comprobar que el directorio se ha inicializado, se ejecuta en el mismo terminal de git el comando 'git status'.
3. Se ha agregado en el directorio el documento readme.md con el que se está trabajando en este momento.
4. Se ha agregado este fichero readme.md al área de Staging con el comando 'git add readme.md' y se ha agregado al repositorio local con el comando 'git commit -m "Primera snapshot ejercicio1'.
5. Se ha intentado subir el repositorio local al repositorio remoto mediante el comando "git push", pero al no haberse creado en Github ha retornado un error.
6. Se ha ejecutado el comando 'git remote -v' y no ha retornado nada por la línea de git bash. Lo que confirma la explicación anterior.
7. Un repositorio remoto llamado 'Repo01' ha sido creado en la página de Github y asociado a este repositorio local con el comando 'git remote add origin https://github.com/jancossio/Repo01.git'.
8. Se ejecuta el comando 'git remote -v' una vez más y se confirma que ahora está asociado a un repositorio remoto al aparecer estas líneas por el terminal: 'origin  https://github.com/jancossio/Repo01.git (fetch)
                        origin  https://github.com/jancossio/Repo01.git (push)'.
