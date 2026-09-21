# Comandos

## Git

### `git add -A`

Te permite mover todos los ficheros al **staging area**.

### `git rm --cached <archivo>`

Elimina el fichero del control de Git, pero el fichero seguirá estando en tu ordenador y quedará como **untracked**.

### `git commit --amend`

Permite modificar el último commit, por ejemplo, añadiendo un fichero que se había quedado fuera.

### `git checkout -- <archivo>`

Permite quitar los cambios de un archivo del **Workspace**, devolviéndolo a la última versión confirmada.

## Python

### `deactivate`

Sirve para salir del entorno virtual de Python.

### `python -m pip`

Sirve para instalar y gestionar librerías de Python.

Por ejemplo:

```bash
python -m pip install nombre-libreria
