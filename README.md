# Programación de sistemas
Actividades
## Ensambladores
En esta actividad descargamos dos programas "nasm" y "minGW", los configuramos e instalamos las extenciones que requerian.

Luego agregamos las variables de las aplicaciones.

Creamos un archivo en notepad++, el cual nos paso la maestra.

Creamos una carpeta en la cual guardamos el archivo y luego abrimos el cmd y escribimos los sieguientes comandos.

nasm -fwin32 .\hola.asm que nos creo el archivo objeto

gcc .\hola.obj -o holamundo.exe, que nos creo el .exe 

luego arrastramos el .exe a la terminal y le dimos enter. Nos imprimió:

"Hola mundo"
