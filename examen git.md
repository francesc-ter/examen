# Examen GIT.

1. Inicializamos el repositorio.Para ello seleccionamos donde se va a iniciar el git. Luego se introduce el comando git init.

2. Creamos un archivo llamado index.html con el contenido, tambien creamos una carpeta llamada unidades y dentro de esta carpeta dos ficheros llamados unidad1.txt y unidad2.txt.
Luego pasamos los ficheros y directorios a preparado. Para ello entroducimos el comando git add --all y despues metemos el comando git status para ver si se han preparado bien los archivos.

3. Confirmamos los ficheros con un commit “Index”. Para ello introducimos el comando git commit -m "Index". 

4. git commit --amend

5. Modificamos el fichero unidad2.txt eliminando todo su contenido y lo pasamos a preparado de nuevo el fichero unidad2.txt con el comando git add --all.

6. Miramos el estado del proyecto con el comando git status.

7. Realizamos otra confirmación con comentario “Eliminado texto de unidad 2”, para ello utilizamos git commit -m "Eliminado texto de unidad 2".

8. Visualiza el log de todo el proyectos con el comando git log --oneline.

9. Vuelve atrás al commit inicial de Index y unidades 1 y 2. Para ello utilizamos el git checkout y poniendo el codigo del commit al que quieres ir. en mi caso seria git checkout 3aaa09c

10. Volvemos al estado final del proyecto y creamos un repositorio en GITHUB. 
