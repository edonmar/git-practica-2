# git practica 1
Taller GIT. Práctica 1.


## Trabajar con un proyecto HTML y un repositorio local.
- Crea una carpeta practica-taller-git en tu pc.
- Inicializa el repositorio. 
 ```bash
 git init
 ```
- Crea el fichero index.html con un html simple.
- Comprueba que el repositorio a detectado el cambio. 
```bash
git status
```
- Añade el fichero al stage. 
```bash
git add index.html.
```
- Confirma los cambios. 
```bash
git commit -m “added index file”
```
- Añade un fichero description.html y edita index.html.
- Comprueba que ha detectado el nuevo fichero y la modificación de index.
```bash
git status
git diff
```
- Crea un fichero TODO.txt de tareas pendientes.
- Comprueba que git ha detectado el nuevo fichero. 
```bash
git status
```
- Ignora el fichero TODO.txt ya que es donde anotaremos nuestras tareas personales y no debe formar parte del proyecto. Para ello crea un fichero .gitignore con la linea TODO.txt.
- Comprueba que ya no detecta el nuevo fichero TODO.txt (si que detectara el .gitignore claro). 
```bash
git status
```
- Añade y confirma el .gitignore.
- Puedes continuar añadiendo ficheros html, css e imágenes para probar el repositorio.


## Haz un fork del repositorio creado para la práctica del taller:
- Entra en https://github.com/
- Accede a tu cuenta.
- Accede al repositorio https://github.com/josefranciscomunozespinosa/git-practica-1/
- Pulsa el botón fork (parte superior derecha) para crearte una copia del mismo en tu cuenta.
- Clona el repositorio en tu equipo. 
```bash
git clone https://github.com/[tu-nombre-de-usuario]/git-practica-1.git
```
- Crea un nuevo fichero en el proyecto que se llame [tu-nombre-de-usuario].html
- Edita el fichero añadiendo como título tu nombre, algún texto y lo que desees en el.
- Añade el fichero al repositorio.
- Súbelo al repositorio remoto (github). 
```bash
git push
```
- Crea una rama develop y cámbiate a ella.
```bash
git checkout -b develop
```
- Realiza cambios en el proyecto, confírmalos y súbelos al repositorio remoto.
```bash
git status
git add *
git commit -m "Mensaje del commit..."
git push origin
```
- Desde github crea un pull request de la rama develop a main.
- Fusiona la rama develop con en main. No deberías de tener ningún conflicto (los veremos en la [practica 2](https://github.com/josefranciscomunozespinosa/git-practica-2)).
- Haz nuevos cambios en el proyecto siguiendo el flujo de trabajo git flow.


## Preguntas

- ¿Qué sucede cuando hacemos un git add?
- ¿Qué sucede cuando hacemos un git commit? ¿Dónde está ese commit? 
- ¿Por qué al hacer git commit todavía no está disponible ese commit en el repositorio remoto?
- ¿Qué hay que hacer para que veamos este commit en nuestro repositorio remoto de github?
- ¿Qué diferencia hay entre hacer un fork o crear una nueva rama?
