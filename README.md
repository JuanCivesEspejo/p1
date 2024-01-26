# Práctica 1 - Entorno de desarrollo

## Comandos Git y Github
_Toda la sección de comandos Git y Github se desarrolla en el [fichero](https://github.com/JuanCivesEspejo/p1/blob/main/git.pdf) aquí se incluye solo un resumen._

Para la realización de la primera práctica, hay que hacer uso de una serie de comandos Git y Github explicando para qué sirven y cómo se han empleado. En primer lugar, debe crear un fork de [este repositorio](https://github.com/gitt-3-pat/p1), no obstante como esto ya se había realizado previamente en clase, se busca un [repositorio de Microsoft](https://github.com/JuanCivesEspejo/Web-Dev-For-Beginners) para hacer uso de estos mismos comandos en un entorno distinto. 

Para comenzar, se emplea el comando `git clone https://github.com/JuanCivesEspejo/Web-Dev-For-Beginners` para copiar el repositorio completo en local. Seguidamente se emplea el comando `git status` para verificar el estado actual de mi repositorio y la rama en la que me ubico.

Seguidamente, se desea realizar los cambios en el repositorio original. Esto se realizará en tres pasos: add, commmit y push. El comando `git add .` agrega todos los archivos que han sido modificados con un mismo objetivo y los prepara para el commit. En este caso, se indica con la salida del comando que sería adecuado realizar un submódulo en lugar de un add, por lo que investigando se emplea el comando `git submodule add https://github.com/microsoft/Web-Dev-For-Beginners Web-Dev-For-Beginners` para añadir este repositorio como submódulo de mi proyecto. Este submódulo es un proyecto independiente con su propio repositorio, historial, ramas… A continuación, se integra este conjunto de cambios que ya han sido verificados mediante el comando `git commit -m "Adding Submodule"` para prepararlos para su push. Finalmente se completan las modificaciones con el comando `git push origin` que permite subir al repositorio los cambios realizados.

El último comando que se emplea es `git checkout -b feat/Add-Tittle-ReadMe` que permite crear y cambiar a la nueva rama feat/Add-Tittle-ReadMe para que los cambios realizados no afecten al main. En este caso, se modificará el título del ReadMe.md. 

## Entorno de desarrollo
_Toda la sección del entorno de desarrollo se desarrolla en el [fichero](https://github.com/JuanCivesEspejo/p1/blob/main/entorno.pdf) aquí se incluye solo un resumen._

## Entorno de desarrollo
_Toda la sección del entorno de desarrollo se desarrolla en el [fichero](https://github.com/JuanCivesEspejo/p1/blob/main/entorno.pdf) aquí se incluye solo un resumen._

A continuación se muestran imágenes que evidencian la instalación de *Java*:
![image](https://github.com/JuanCivesEspejo/p1/assets/123270221/86892214-38e7-424a-8fe6-3310ac45bcc0)
![image](https://github.com/JuanCivesEspejo/p1/assets/123270221/d46d5fc8-b3c6-4484-aafb-4362b1030ad6)

Seguidamente, estas son las imágenes que verifican la instalación de *Maven*:
![image](https://github.com/JuanCivesEspejo/p1/assets/123270221/7eaced78-edb6-4f8e-9f46-49778cabe458)
![image](https://github.com/JuanCivesEspejo/p1/assets/123270221/8988b563-d3d0-4c34-9e43-5d33f6c2ade4)

Por último, las imágenes que muestran la instalación de VSCode e IntelliJ con las siguientes:
![image](https://github.com/JuanCivesEspejo/p1/assets/123270221/1f321550-b1c1-4ff9-9277-72bdf4338511)
![image](https://github.com/JuanCivesEspejo/p1/assets/123270221/5a8a75fd-248d-44c1-8435-08b03b41439a)
![image](https://github.com/JuanCivesEspejo/p1/assets/123270221/7984dc1b-2c71-4300-8a16-3cad7db2939b)


