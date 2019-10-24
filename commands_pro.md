# COMANDOS DE GIT
Todos los comandos empiezan por git

# Mostrar los commits resumidos con sus comentarios
git log --oneline

# Retroceder al pasado
git reset --hard HASH_COMMIT_A_RECUPERAR

# Después del git reset --hard esto regresa a la normalidad
git pull 

# Regresar al último commit
git checkout --NOMBRE_DEL_ARCHIVO

# Sacar una copia de un evento pasado
git show HASH_DEL COMMIT

# Sacar una copia de un evento pasado y respaldar
git shw HASH_DEL_COMMIT:Ruta/archivo > nombre_respaldar