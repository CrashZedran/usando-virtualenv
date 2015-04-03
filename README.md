## Usando-virtualenv

Este es una breve explicacion de como instalar virtualenv, crear y activar un entorno virtual.

# Instalando virtualenv

primero instalamos la libreria de python virtualenv con el instalador 
de paquetes pip de la siguiente manera:

    $ sudo pip install virtualenv 

sino salio ningun error procedemos a crear nuestro entorno virtual.

# Crear entorno virtual con Virtualenv

Para crear nuestro entorno virtual con virtualenv procedemos a crear
el directorio donde queremos crear nuestros entornos viruales, a mi me gusta
crear un solo directorio llamado "Pruebas" o "Laboratorios" en el cual crear 
mis entornos virtuales de la siguiente manera:

    $ mkdir Pruebas
    $ cd Pruebas

Luego que estamos dentro de nuestro directorio "Pruebas" procedemos a crear
nuestro entorno virtual para trabajar con el comando virtualenv seguido del
nombre de nuestro entorno virtual asi:

    $ virtualenv Experimentos

Despues de esto seguimos con el siguiente paso.

# Activando nuestro entorno virtual

Cuando creamos un entorno virtual con virtualenv, este nos crea los siguientes 
directorios en nuestra en el directorio "Experimentos" que ess nuestro entorno
virtual:

    - bin 
    - include 
    - lib 
    - local

La que nos interesa saber es "bin" en esta se encuentran el comando de activacion
de nuestro entorno virtual para activar nuestro entorno tipiamos lo siguiente en 
nuestra terminal:

    $ source bin/activate

con eso nos deberia aparecer antes de nuestro simbolo $ el nombre de nuestr entorno
virtual dentro de () de la siguiente manera:

    (Experimentos) $ clear

si te aparece asi pues listo ya esta tu entorno virtual activado y puedes comenzar a 
desarrollar en python.