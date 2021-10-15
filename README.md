### Configurar usuario de git 

    $ git config --global user.name "Luis J. Rodriguez O."
    $ git config --global user.email "ljavierrodriguez@gmail.com"

### Iniciar proyecto de git

    $ git init

### Verficar estatus de mis documentos 

    $ git status

### Preparar archivos a guardar con git

    $ git add <filename>
    $ git add .
    $ git add -A
    $ git add *


### Guardar archivos en el repositorio local

    $ git commit 
    $ git commit -m "Mensaje descriptivo del cambio"

### Mostrar cambios guardados dentro del repositorio 

    $ git log


### Agregar repositorio remoto a mi proyecto

    $ git remote add origin https://....


### Remover repositorio remoto del proyecto (ejemplo: git remote rm origin)

    $ git remote rm <nombre-repositorio> 

### Modificar repositorio remote del proyecto (ejemplo: git remote set-url origin https://....)

    $ git remote set-url <nombre-repositorio> <url-repositorio>

### Enviar commits al repositorio remote (ejemplo: git push origin master)

    $ git push <nombre-respositorio> <nombre-rama>


### Listar ramas del proyecto (branch) 

    $ git branch


### crear una nueva rama (branch) (ejemplo: git branch dev)

    $ git branch <branch>

### Cambiar o activar rama (branch) (ejemplo: git checkout dev)

    $ git checkout <branch>