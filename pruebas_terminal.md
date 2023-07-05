# Pruebas terminal
##Cómo hacer que la terminal sea operativa 
Para poder empezar a trabajar con la shell es importante tener una terminal POSIX operativa. En GNU/Linux viene dado pero en el sistema operativo MacOSX es necesario activar el XCode. 
*POSIX* es un acronimo de Portable Operating System X UNIX y define una interfaz estándar del sistema operativo y el entorno, incluyendo un intérprete de comandos. 
### Cómo activar XCode
Para acceder a la terminal en Mac hay que acceder a Aplicaciones -> Utilidades -> Terminal y una vez en la línea de comandos escribir xcode-select `--install` y darle a enter para la instalación. Una vez hecho esto instalaremos el gestor de paquetes Homebrew.

## Què es Homebrew
Homebrew es un sistema de gestión de paquetes que simplifica la instalaciòn, actualización y eliminación de programas en los sistemas operativos de Mac OS de Apple. Homebrew instala todo aquello que necesitas que Apple no instala de serie. 

### Cómo instalar Homebrew
Para instalar este gestor tenemos que ir a la pàgina web de [Homebrew](https://brew.sh/index_es)y copiar el código y pegarlo en nuestra terminal ` $/bin/bash -c "$(curl -fsSL https://raw.githubsercontent.com/Homebrew/install/HEAD/install.sh)"`
Con Homebrew podemos instalar comandos como `wget`y `curl`
`wget`se usa para recuperar contenido y archivos de servidores web. El nombre es una combinación de Worl Wild Web y la palabra get. Admite descargas a través de FTP, SFTP, HTTP, y HTTPS. El comando wget se instala de la siguiente manera: `brew install wget`  
`curl` es un comando que se usa para comunicarse con protocolos URL y es una herramienta para transferir datos y es compatible con una gran lista de protocolos. El comando `curl`se instala de la siguiente manera `brew install curl` 

## Los comandos
Los comandos son palabras reservadas que usa el sistema operativo para ejecutar determinadas accions usando la terminal o línea de comandos. Para moverse por la terminal serà necesario conocer algunos comandos como:   
`pwd` de las siglas en inglés Print Working Directory.Si escribimos `pwd`en la terminal nos va a devolver el directorio en el que nos encontramos trabajando.   
`cd` de las siglas en inglés Change Directory sirve para movernos por el arbol de directorios en la termianl y es necesario para cambiar de directorio   
`ls`se utiliza para listar archivos o directorios del directorio donde te encuentras.  
 Con la variante `ls -la` se listaran también los directorios ocultos.  
`mv`este comando se usa para mover o renombrar archivos o directorios del sistema de archivos.

Para que el comando ejecute la funcion es importante escribir primero el comando y  luego el argumento. Por ejemplo si quisiera cambiar el nombre de este documento usaría: 
1. El comando `mv` 
2. El nombre actual del documento 
3. El nuevo nombre que quiero dar al documento  
`mv pruebas_terminal nuevo nombre` después enter  
Con ciertos comandos no es necesario dar los argumentos por ejemplo el comando si ejecutamos el comando `pwd`la terminal devuelve un mensaje  con el nombre de la carpeta  en este caso seria ** .../mpvd2223/fundamentos_tec/uah2223-nunoguera**
 

## Nos descargamos Oh My Bash 
Oh-My-Bash es un framework de código abierto impulsado por la comunidad para gestionar tu configuración BASH.Lo primero que hace es resaltar la sintaxis de la terminal y facilita la lectura.  Editamos el documento .bashrc con nano para configurarlo a nuestro gusto.
Elegimos un tema y lo cambiaos en la opción OSH_THEME="rr" 


## Herramientas curisoso en la línea de comandos 
### Comando 'sl'
1. Lo instalamos
2. brew install `sl`: al ejecutar el comando aparece un tren en arte ASCII que atraviesa la terminal.
### Comando 'figlet' crea banners de texto ASCII
1. Si no tenemos `figlet` hay que instalarlo
2. Instalamos el comando `figlet`s
3. para usarlo escribimos `figlet` y el texto que queremos que aparezca en figlet entre comillas `figlet` "Hola Mundo"
d
| | | | ___ | | __ _     _ __ ___  _   _ _ __   __| | ___  
| |_| |/ _ \| |/ _` |   | '_ ` _ \| | | | '_ \ / _` |/ _ \ 
|  _  | (_) | | (_| |_  | | | | | | |_| | | | | (_| | (_) |
|_| |_|\___/|_|\__,_( ) |_| |_| |_|\__,_|_| |_|\__,_|\___/ 


### Comando 'cowsay'
1. Instalamos el comando `cowsay`
2. La sintaxis es la misma que el comando `figlet` `cowsay` "Hola Mundo"
< Hola Mundo >
 ------------ 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||



Syntax error near unexpected token `('

`ls -la ../` para listar los documentos que tenemos en el ordenador

`rm`remove.  Para documentos
`rm-r`para eliminar los directorios  
`rm  -rf`
`file` preguntas que tipo de archivo es si está vacío sale empty  
`file *.md` te lista todos los documentos que dentro del directorio tienen formato markdown 
`git push -f`sube todo lo que tienes en el repositorio local. 

`grep -rn \# pruebas-github.md ` rn para que busque de manera recursiva y n para el número de línea
para guardar un resultado 
`source`

Emacs 
Instalo spaceemacs desde spaceemacs
como ya tenia un directorio con emacs descargado lo muevo de backup `mv` .emacs.d/ emacs.d.bak
y ahora instalo desde spaceemacs con `git clone` http...
