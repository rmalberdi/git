# Principal

Este es el fichero principal

Nos damos cuenta de que es buena idea empezar a trabajar con Git, pero de momento no queremos subir nada a la nube.

Pon aquí que comando usarias para crear el repositorio en local:

git init 

Queremos guardar lo que llevamos de proyecto (el fichero principal.md) en la base de datos de Git que tenemos en local ¿Qué comandos podemos ejecutar para hacer esto?

git add principal.md
git commit -m "Cambios Principal.md" 

#Ignorar
Antes de subir a staging los cambios queremos ver en que estado están los ficheros, para ello ejecutamos el comando:

git status

¡Anda! Queremos hacer commit del fichero detalle.md pero no queremos que se suban los ficheros con extension .bak, así que decidimos añadir una entrada al .gitignore ¿Qué contenido tendríamos que añadir?

Indica aquí tu .gitignore

*.bak

Pista: para la extensión te va a hacer falta usar un patrón, más info: https://www.atlassian.com/es/git/tutorials/saving-changes/gitignore

Ahora que lo tenemos vamos a meter los cambios en la base de datos de git (el fichero detalle.md), ¿Que comandos o comando te harían falta?

git add detalle.md
git commit -m ”Cambios del Detalle.md” detalle.md

#Subida a la nube

Crea un repositorio público en tu cuenta de Github, pon aquí el enlace al mismo:

https://github.com/rmalberdi/git.git

Enlace tu local a ese servidor, pon aquí el comando:

git remote add origin https://github.com/rmalberdi/git.git
git branch -M main

Sube el contenido al servidor, pon aquí el comando:

git push -u origin main