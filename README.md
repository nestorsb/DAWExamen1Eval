# DAWExamen1Eval

- Primero iniciamos con *git init.
- Conectamos con el repositorio remoto con  *git remote add origin https://github.com/nestorsb/DAWExamen1Eval.git
- Clonamos el remoto al local con *git clone https://github.com/nestorsb/DAWExamen1Eval.git


- Despues de modificar el Readme.txt, hacemos *git add . y *git commit -m "mensaje"
- Para subirlo al remoto (una vez ya lo hemos conectado con *git add remote) ejecutamos *git push -u origin main

- Creamos carpeta "privada" y el fichero "private.txt" dentro. Despues creamos el fichero .gitignore y añadimos "privada/*". Con esto git ignora los cambios de la carpeta y los archivos de dentro.