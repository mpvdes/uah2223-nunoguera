# Pruebas Github

## Pasos básicos en Github 

1. Crear una cuenta: para poder usar Github primero tenemos que crear una cuenta [aquí](https://www.github.com/login)
2. Una vez ya tenemos cuenta creamos un repositiorio dentro del espacio [mpvdes](https://www.github.com/mpvdes) con nuestro nombre de usuario

### Como crear un repositorio

1. Entramos en el perfil de [mpvdes](https://www.github.com/mpvdes)

2. Vamos a la pestaña [repositories](https://www.github.com/mpvdes/repositories)

3. Pinchamos sobre el icono verde *New repository* 

4. Se abre una nueva ventana donde tenemos que elegir el nombre de nuestro repositorio en este caso el nombre de usuario que utilizemos

5. Podemos poner una descripción de nuestro repositorio

6. Elegimos si nuestro repositori será público(cualquier persona puede ver nuestro repositorio. Pero nosotros elegimos quien puede hacer *commit*, és decir, hacer cambios) o privado (podemos elegir quien ve nuestro repositorio y quien puede hacer *commit*)

7. Después seleccionamos la opción de inicializar nuestro repositorio con un *README* que contendrá la informaicón básica de nuestro proyecto. 

8. Por último hacemos clic en la opción *create repository*
 

<!--
    
     

### Documentos en Github

### github.io 

### github desde la terminal

--->

## Github en la terminal

### Clonar un repositorio de github 

1. Accedemos a nuestra terminal 
2. Con el comando `pwd` comprobamos donde nos encontramos. En mi caso estoy en la HOME. Para moverme en el directorio que me interesa uso el comando `cd` seguido del nombre de la carpeta. 
3. Una vez estoy en el directorio correcto uso el comando `git clonoe` seguido de la dirección web https://github.com/mpvdes/uah2223-nunoguera para descargar el repositorio de github en local.
4. Una vez se ha completado la descarga comprobamos con el comando `ls` que se han descargado correctamente los aarchivos. 
5. Ya podemos empezar a modificar los docuemntos. 

### Subir los cambios en Github 

1. Primero tenemos que hacer el repositorio local "gitable" para poder subir las modificaciones en la [web](https://github.com) con el comando `git init`. 
2. Hecho esto con `git status` comprobamos que archivos se han modificado y éstos apareceran en rojo. 
3. Con el comando 'git add' añadimos los documentos que queremos subir al repositorio web 
4. Después con el comnado `git commit -m` "Explicamos porque hacemos el commit"
5. Por último con el comando `git push origin main` publicamos los archivos en [github](https://github.com)

 
