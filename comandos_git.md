# Comandos de git

## Comando para ver la versión de git
 
- git -v
- git --version

## Comandos para conifguración inicial de git

- git config --global user.name "Your name"
- git config --global user.email "Your email"

# Comandos para editar o ver la configuracion de git
Para salir del edit ctrl + O y Ctrl +X
y si es VIM esc :wq

- git config --global --edit
- git config --global --list

## Como iniciar git en un directorio

- git init


## Comando para saber el estado de nuestros archivos

- git status

## Comando para listar las versiones de mi proyecto
- git log
- git log --oneline 

## Comando para cambiar de versión

- git checkout <Id del commit o nombre de la ramacle>

## Pasos para crear una  versión de nuestro código

1. gregar todos los archivos al commit

añadir todos los archivos independiente de la extensión
- git add .

agregar extensión en especifico
- git add *.js

Subir un archivo en especifico
- git add index.js

2. Tomar la foto del código(crear una nueva versión) -m message, agragar mensaje de lo que se modificó
- git commit -m "Nombre del commit"



