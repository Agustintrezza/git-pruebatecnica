Hola es una prueba!

Para crear la rama DEV :
git branch < nombre de la rama >

Luego de creada la rama
git checkout < nombre de la rama >

Para crear una rama, y posicionarse, en un único paso
git checkout -b < nombre de la rama >

Para mostrar todas las ramas locales y verificar la posicion actual
git branch 

Para mostrar todas las ramas remotas
git branch -r

Para pushear los nuevos cambios al repositorio.
git add .
git commit -m"Descripción del commit"
git push


Parado en la rama main " git merge < nombre de la rama que queremos mergear > " (Se actualiza la rama en local, pero luego para subir los cambios al remoto)
git add . 
git commit -m"Descripción del commit"
git push


Respuesta 1, exáment técnico GCBA:

Para revertir la última funcionalidad pusheada el comando que se debe utilizar es "git revert < hash del commit > ". (Luego se deben comparar y elegir los cambios en las versiones).
Al utilizar revert, git, no elimina el commit revertido. Luego, cuando se genera un nuevo push, este se posicionara como último commit en el listado.

Por último para verificar, tanto el hash del commit que se quiere revertir y luego del revert, el commit "HEAD" se puede utilizar, el comando "git log".

Otra comando que se puede utilizar es "git rever HEAD~n < donde n representa la cantidad de commits que se desea revertir >".


Respuesta 2

Paso 1: Me muevo a la rama MAIN
Paso 2: Para crear el tag ingresamos el comando git tag -a < v1.2.0 > -m "Mensaje".
Paso 3: Para posicionarse en el tag v1.2.0, corremos el comando "git tag v1.2.0".
Paso 4: ng build --prod



