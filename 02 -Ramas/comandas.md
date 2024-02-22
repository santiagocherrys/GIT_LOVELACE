# Comando para listar las ramas de mi repositiorio

git branch
git branch -v

# Comando para crear una rama

git branch nombre_rama

# Comando para cambiar de ramas

git checkout nombre_rama
git switch nombre_rama
git checkout -b nombre_rama (Crea la rama y hace el cambio)

# Comando para eliminar una rama

git branch -D nombre_rama

# Comando para cambiar el nombre de una rama

git branch  -M nuevo_nombre

# Comando para remover un archivo de git pero no del proyecto

git rm --cached nombrerchivo.extension

# Comando para hacer shortcuts personalizados alias. despues del punto se pone el shortcut, en este caso es lg

git config --global alias.lg 'log --oneline'

# Comando para unir 2 ramas
git merge rama_auxiliar
