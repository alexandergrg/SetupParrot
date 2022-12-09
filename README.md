# SetupParrot

## Step 1
### Instalando Bspwm y Sxhkd
1. En resumen, primeramente ejecutaremos el siguiente comando:

    - apt install build-essential git vim xcb libxcb-util0-dev libxcb-ewmh-dev libxcb-randr0-dev libxcb-icccm4-dev libxcb-keysyms1-dev libxcb-xinerama0-dev libasound2-dev libxcb-xtest0-dev libxcb-shape0-dev


2. Posteriormente, aplicaremos una actualización del sistema con el comando ‘apt update‘. Acto seguido, tenéis que dirigiros a la carpeta de descargas de vuestro equipo y descargar los proyectos ‘bswpm‘ y ‘sxhkd‘ con los siguientes comandos:

    - git clone https://github.com/baskerville/bspwm.git
    - git clone https://github.com/baskerville/sxhkd.git

3. Para instalar cada uno de estos, lo que debéis hacer es meteros en ambos directorios por separado y ejecutar los comandos ‘make‘ y ‘sudo make install‘.

4. Finalmente, instalaremos ‘bspwm‘ con el comando ‘sudo apt install bspwm‘.
