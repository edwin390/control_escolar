Presiona `ctrl + shift + V` o `ctrl + K V` para visusalizar el documento

* * * 
# Subir cambios (push)
`git add` **`"archivo"`**

### Agrega todos los archivos modificados a la rama (dejarlos preparados para el commit)
`git add .`

### Crear instancia de cambio (checkpoint)
`git commit -m` **`"commentario"`**

### Ingresa los ultimos cambios al origen
`git push -u origin`**`nombre`**

* * *
# Obtener cambios (pull)
### Traer repositorio remoto al local
`git pull (apodo repositorio remoto) (nombre de la rama)`
#### Normalmente es:
`git pull origin main`

* * *
# Utilidades
### Historial de cambios en repositorio remoto
`git log`

### Muestra las ramas disponibles
`git branch`

### Cambiar de rama
`git checkout` **`nombre de la rama`**

### Muestra los archivos nuevos o modificados que no tienen commit
`git status`

### Quita el archivo de la rama
`git reset` **`archivo`**

### Quita los archivos de la rama y el directorio.
`git rm`  **`archivo`**

### Revertir todo al ultimo commit
`git reset --hard`

### Clonar un repositorio ya creado de una URL
`git clone` `URL`

`git clone` `https://github.com/jhotwox/control_escolar`

### Crear una nueva rama:
`git branch cristian`

### Cambiar a la rama:
`git checkout cristian`
### Hacer push a tu rama específica:
`git push -u origin cristian`

### Crear una copia de main en tu rama(hacer siempre antes de comenzar a trabajar):
`git checkout cristian`
`git pull origin main`

### Hacer tus cambios en tu rama:
`Realiza tus cambios y commits en tu rama según sea necesario.`

### Hacer merge al main desde tu rama(cuando los cambios de la rama esten listos para integrarse al main):
#### Cambiar a la rama main
`git checkout main`

#### Actualizar la rama main con los últimos cambios
`git pull origin main`

#### Fusionar tus cambios desde tu rama a main
`git merge cristian`

#### Subir los cambios fusionados a la rama main en GitHub
`git push origin main`