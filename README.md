# PRÁCTICA 1 - LABORATORIO DE GIT

## 1. Crear un repositorio en local

He seguido los siguientes pasos:

- <b><i>cd Desktop/BootcampJS2</i></b> (para acceder a la carpeta de mi escritorio donde quiero crear el repositorio).

- <b><i>mkdir Practica1</i></b> (para crear una carpeta con el nombre <i>“Practica1”</i>).

- <b><i>cd Practica1</i></b> (para ingresar en la carpeta).

- <b><i>git init</i></b> (para inicializar el repositorio).


## 2. Subir el repositorio a GitHub

- He creado un nuevo repositorio en GitHub clicalndo en <i>"new"</i>, titulándolo como <i>"laboratoriodegit"</i>, añadiendo una descripción <i>"Este repositorio corresponde a la primera práctica del bootcamp."</i>, y selecionando la opción de <i>"private"</i>.

- He copiado la URL con protocolo ssh (la clave ssh la tenía creada con anterioridad).

- He conectado mi repositorio local con el remoto escribiendo los siguientes comandos en el terminal:

    - <b><i>git remote add origin</i></b> + URL

    - <b><i>git push -u origin master</i></b> para subirlo al repositorio de la nube.

    - He verificado que la conexión se ha establecido correctamente recargando la página de GitHub.


## 3. Hacer un commit y un push

- He creado un archivo en la carpeta del repositorio llamada <b><i>"archivoantonio"</i></b> desde la opción <i>"nuevo archivo"</i> de mi explorador de Visual Studio Code.

- He añadido el archivo al staging con <b><i>git add .</i></b>

- He creado un commit con el comando <b><i>git commit -m "laboratorio de git - práctica 1"</i></b> y seguidamente <b><i>git add .</i></b>

- He subido los cambios al repositorio de GitHub mediante <b><i>git push</i></b>

## 4. Crear una rama

- 