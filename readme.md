git init -> crea un nuevo repositorio local

# configurar el repositorio a que usuario pertenece
git config user.name "Dxsxsx"
git config user.email "Dxsx1226dev@gmail.com"

# comunitar repositorio local con github
git remote add origin "https://github.com/Dxsxsx/git_repository.git"

# añadir archivo al repositorio de manero provisoria
git add comandos.txt

# de forma definitiva
git commit -m "commit 1"

# pasar repositorio local a github
git push -u origin master

# clonar repositorio de github
git clone https://github.com/Dxsxsx/git_repository.git

# clonar archivos nuevos del repositorio de github
git pull origin master

# branches - Ramas -> 
git branch -> Rama actual

# crear rama1
git branch rama1

# Editar nombre de rama1
git branch -m <nombreActual> <nombreNuevo>

# cambia de rama (master-rama1)
git checkout ramita1

# eliminar rama
git branch -d ramita1

# crear archivos y guardar en la rama1
git add .
git commit -m "commit de la rama1"