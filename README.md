# DAWExamen1Eval

1 -------------------

- Primero iniciamos con *git init.

- Conectamos con el repositorio remoto con  *git remote add origin https://github.com/nestorsb/DAWExamen1Eval.git

- Clonamos el remoto al local con *git clone https://github.com/nestorsb/DAWExamen1Eval.git

- Despues de modificar el Readme.txt, hacemos *git add . y *git commit -m "mensaje"

- Para subirlo al remoto (una vez ya lo hemos conectado con *git add remote) ejecutamos *git push -u origin main

- Creamos carpeta "privada" y el fichero "private.txt" dentro. Despues creamos el fichero .gitignore y añadimos "privada/*". Con esto git ignora los cambios de la carpeta y los archivos de dentro.

- Para crear el tag, aunque no es necesario primero vamos a hacer un commit. Tras esto *git tag v1.

-Para subir todo al repositorio remoto incluido los tags podemos hacer: *git push -u origin main y *git push --tags


2 -------------------------

- Para crear la rama *git branch v0.2 y para trabajar en ella *git checkout v0.2

- Para realizar un merge (fusionar) hacemos *git checkout main y *git merge v0.2. Con esto habriamos añadido los cambios hechos en la rama v0.2 en main.
- Para realizar un merge (fusionar) despues de hacer cambios en la segunda rama, primero add y commit, despues checkout main y por ultimo hacemos git merge v0.2. 

3 --------------------------
- Modificamos 1.txt y hacemos commit desde main:
*git add. y  *git commit -m "mensaje"

- *git checkout a v0.2 y modificamos 2.txt:
*git add. y  *git commit -m "mensaje"

- Volvemos a rama main con *checkout main y hacemos *merge v0.2. Los mensajes "hola" y "adios" estan ambos en sus respectivos ficheros. 

4 -----------------------------------
Los comandos para listar ramas con merge y sin merge son:
    - git branch --merged 
    - git branch --no-merged

- Creamos tag con git tag v0.2
- Borramos rama con git branch -d v0.2
Por ultimo hacemos un commit y un push. (y push --tags).
