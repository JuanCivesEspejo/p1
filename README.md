# Práctica 1 - Entorno de desarrollo

## Comandos Git y Github
_Toda la sección de comandos Git y Github se desarrolla en el [fichero](https://github.com/JuanCivesEspejo/p1/blob/main/git.pdf) aquí se incluye solo un resumen._

Para la realización de la primera práctica, hay que hacer uso de una serie de comandos Git y Github explicando para qué sirven y cómo se han empleado. En primer lugar, debe crear un fork de [este repositorio](https://github.com/gitt-3-pat/p1), no obstante como esto ya se había realizado previamente en clase, se busca un [repositorio de Microsoft](https://github.com/JuanCivesEspejo/Web-Dev-For-Beginners) para hacer uso de estos mismos comandos en un entorno distinto. 

Para comenzar, se emplea el comando `git clone https://github.com/JuanCivesEspejo/Web-Dev-For-Beginners` para copiar el repositorio completo en local. Seguidamente se emplea el comando `git status` para verificar el estado actual de mi repositorio y la rama en la que me ubico.

Seguidamente, se desea realizar los cambios en el repositorio original. Esto se realizará en tres pasos: add, commmit y push. El comando `git add .` agrega todos los archivos que han sido modificados con un mismo objetivo y los prepara para el commit. En este caso, se indica con la salida del comando que sería adecuado realizar un submódulo en lugar de un add, por lo que investigando se emplea el comando `git submodule add https://github.com/microsoft/Web-Dev-For-Beginners Web-Dev-For-Beginners` para añadir este repositorio como submódulo de mi proyecto. Este submódulo es un proyecto independiente con su propio repositorio, historial, ramas… A continuación, se integra este conjunto de cambios que ya han sido verificados mediante el comando `git commit -m "Adding Submodule"` para prepararlos para su push. Finalmente se completan las modificaciones con el comando `git push origin` que permite subir al repositorio los cambios realizados.

El último comando que se emplea es `git checkout -b feat/Add-Tittle-ReadMe` que permite crear y cambiar a la nueva rama feat/Add-Tittle-ReadMe para que los cambios realizados no afecten al main. En este caso, se modificará el título del ReadMe.md. 

## Entorno de desarrollo
_Toda la sección del entorno de desarrollo se desarrolla en el [fichero](https://github.com/JuanCivesEspejo/p1/blob/main/entorno.pdf) aquí se incluye solo un resumen._

![image](https://github.com/JuanCivesEspejo/p1/assets/123270221/1cbc0230-b3cf-4f65-a752-228bed65a17d)

