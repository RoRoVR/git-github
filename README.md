**GIT**

# Inicia el repositorio en la carpeta seleccionada
    • git init
# Hace un seguimiento al archivo seleccionado
    • git add <NOMBREARCHIBO.JS>
# Muestra el los archivos que no tienen seguimiento por Git
    • git status -s
# Lleva los archivos seleccionados al repositorio local
    • git commit -m ""
    • git commit -am "" --> Agrega y hace el commit a la ves
    • git commit --amend --> Abre VIN para modificar
# Verificar los commits que hicimos (--oneline --> para que nos muestre de forma resumida)
    • git log --oneline
# Restaura los archivos hasta el commit seleccionado, eliminando los commit q esten despues de ese
    • git reset --hard <ID del commit>

**GITHUB**

# Subir el repositorio local a GitHub
    • git remote add origin https://github.com/RoRoVR/git-github.git --> Indica el lugar del repositorio online
    • git branch -M main --> Indica la rama a la que se va a subir
    • git push -u origin main --> Sube los archivo al repositorio en GitHub
# Clonar repositorio de GitHub a Local
    • git pull --> Realiza los cambios hechos en GitHub en Local
    • git clone <url>
# Agregar etiquetas
    • git tag <version> -m "descripcion"
    • git push --tag --> sube la las TAG creadas

**RAMAS O BRANCH**

# Crear rama nueva
    • git branch <nombre>
# Lista de Ramas y rama activa
    • git branch
# Cambiar de rama
    • git checkout <nombre>
# Unir 2 Ramas
    • git merge <rama a unir>
# Eliminar Rama
    • git branch -d <nombreRama>





