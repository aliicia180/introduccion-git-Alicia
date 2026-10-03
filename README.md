# introduccion-git-Alicia
# Pasos para resolver el ejercicio

## 1. Crear el repositorio

Primero se creó un repositorio en GitHub para almacenar el proyecto y poder subir los archivos realizados.

## 2. Crear el repositorio local

Se creó una carpeta llamada `libro` en el ordenador, que se utilizó como repositorio local.

## 3. Inicializar Git

Desde Git Bash se accedió a la carpeta del proyecto y se inicializó Git mediante:


git init


## 4. Comprobar el estado del repositorio

Se comprobó el estado de los archivos utilizando:

git status


Esto permite saber qué archivos han sido modificados, añadidos o están pendientes de incluir en el siguiente commit.

## 5. Añadir los archivos

Se añadieron los archivos del proyecto al área de preparación mediante:


git add .


## 6. Crear el primer commit

Una vez añadidos los archivos, se creó un commit para guardar los cambios:


git commit -m "Primer commit"


## 7. Conectar el repositorio local con GitHub

Se vinculó el repositorio local con el repositorio creado en GitHub mediante el repositorio remoto `origin`.

## 8. Subir los archivos a GitHub

Finalmente, se subieron los archivos al repositorio remoto utilizando:


git push -u origin master


De esta forma, los archivos del repositorio local quedaron disponibles en GitHub.

## 9. Comprobar el resultado

Se accedió al repositorio de GitHub para comprobar que los archivos se habían subido correctamente.

## 10. Añadir el documento de pasos

Después se creó este documento `README.md` para explicar los pasos realizados para resolver el ejercicio.

Una vez guardado el documento, se añadieron los nuevos cambios:


git add .


Se creó un nuevo commit:

git commit -m "Añadir documento con los pasos"


Y finalmente se subieron los cambios a GitHub:


git push


## Repositorio

El ejercicio y el documento con los pasos se encuentran en el siguiente repositorio de GitHub:

https://github.com/aliicia180/introduccion-git-Alicia
