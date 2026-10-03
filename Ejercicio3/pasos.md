# Pasos para resolver el Ejercicio 3

1. Crear la carpeta `libro` y convertirla en un repositorio Git.

2. Crear el archivo `indice_libros.txt`.

3. Añadir el archivo al área de preparación:

```bash
git add indice_libros.txt
```

4. Crear el commit correspondiente.

5. Crear la carpeta `capitulos` y añadir los capítulos indicados.

6. Añadir los archivos y crear los commits correspondientes.

7. Crear el archivo `.gitignore` para indicar qué archivos no deben ser controlados por Git.

8. Configurar `.gitignore` con:

```text
_*
!_ayuda.txt
```

9. De esta forma, los archivos cuyo nombre empieza por `_` quedan ignorados, excepto `_ayuda.txt`.

10. Comprobar el funcionamiento de `.gitignore`. El archivo `_logs.txt` queda ignorado, mientras que `_ayuda.txt` sí puede añadirse.

11. Añadir los archivos que no están ignorados:

```bash
git add *
```

12. Comprobar el estado del repositorio:

```bash
git status
```

13. Realizar los cambios posteriores indicados en los archivos y crear los commits correspondientes.

14. Eliminar los archivos indicados utilizando:

```bash
git rm
```

15. Cambiar el nombre o mover los archivos indicados mediante:

```bash
git mv
```

16. Modificar el último commit cuando fue necesario utilizando:

```bash
git commit --amend
```

17. Consultar el historial para comprobar los commits realizados:

```bash
git log
```

18. Finalmente, conectar el repositorio local con GitHub y subir el repositorio:

```bash
git push -u origin master
```

