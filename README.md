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
    • git remote add origin https://github.com/RoRoVR/git-github.git
    • git branch -M main
    • git push -u origin main



