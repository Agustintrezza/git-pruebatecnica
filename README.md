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

Para pushear por primera vez una rama de local a remoto
git push -u origin < nombre de la rama >  == git push --set-upstream origin develop;


Para pushear los nuevos cambios al repositorio.
git add .
git commit -m "Descripción del commit"
git push


zzzzzzzzzzz