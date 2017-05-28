# instalardrawiolocal
A simple script to install a local (docker image) service of Draw.io on Ubuntu

## ./instalar_drawio_y_docker: Will 
 - install docker, 
 - execute ./instalar_drawio_dockerimage

## ./instalar_drawio_dockerimage: Will
 - download and start the docker image from ivonet/draw.io, 
 - create 2 commands (and 2 .desktop files in ~/.local/share/applications/):
   - "draw.io" in /usr/local/bin: is a shortcut to firefox (a new window with the path to the local draw.io)
   - "iniciarServicioDrawIo" in /usr/local/bin: is a shortcut to initiating the service throught docker
   
## ./desinstalar_drawio_dockerimage: Will
 - stop the draw.io service (if it is running)
 - remove the downloaded ivonet/draw.io docker images
 - remove the 2 commands and .desktop files
