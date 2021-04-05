# Este es el primer proyecto del curso

## Creacion de repo
git init

## Añadir un fichero
git add <nombre_fichero>    #Añadir un fichero
git add *                   #Añadir todos los ficheros del directorio. NO AÑADE OCULTOS
git add .                   #Añadir todos los ficheros del directorio. SI AÑADE OCULTOS
Empezar a controlar el fichero...
Pasar el fichero al area de STAGING


# Qué guarda GIT?
Git solo guarda ficheros
NO GUARDA DIRECTORIOS!!

#OBJETOS EN GIT:
## Workspace
La carpeta en la que tengo mi proyecto, en la que trabajo
## Staging
Es un fichero que se guarda dentro de la carpeta .git, que va anotando los cambios
que se van a mandar al REPO desde el área de STAGING
## Repo
La carpeta .git

## Información del estado del proyecto
git status

## Qué es un commit?
Un paquete de cambios que se registra en el repo

## Sacar un fichero del área de STAGING
git rm --cached <NOMBRE_FICHERO>

## Borra el fichero
De donde? De todos los sitios
- del WORKSPACE
- En el stagging se le dice que en el proximo paquete de cambios, se elimine el fichero
- (Se sigue quedando en el repo)
git rm <NOMBRE_FICHERO>

