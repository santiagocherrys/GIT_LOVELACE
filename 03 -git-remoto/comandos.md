# Comando para conectar mi git local con git en la nube

git remote add nombre_conexion url_conexion

# Comando para clonar o traer un repositorio de git remoto

git clone url_conexion

# Comando para listar las conexiones remotas

git remote -v

# Comando para eliminar una conexion remota

git remote remove nombre_conexion

# Comando para enviar informacion al git remoto

git push //lo manda a la rama main o la manda a la rama que estoy actualmente
git push nombre_conexion nombre_rama //lo agrega a la rama nombre_rama
git push -u nombre_conexion nombre_rama // con el -u hace que en caso que la rama no existe, la crea
git push --all //sube todas las ramas que habia creado

# Comando para obtener cambios o la informacion que hay en el git remoto

git pull
git pull nombre_conexion nombre_rama

## Titulo 2
