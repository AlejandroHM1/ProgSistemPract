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

## Bibliotecas
En esta actividad creamos unos archivos .cpp .h y el main, el archivo decia el nombre de la persona que creo el archivo.

Luego en el cmd escribimos un par de comandos que creaban el .obj y .exe y libfoo

Le pasamos el .exe a un compañero y luego comilamos, mostraba el nombre del creador del archivo.

Lugo con los primero archivos pusimos otros comandos que creaban el dll. Le compartimos otra vez el .exe y al compilar se mostrban ambos nombres, del creador del archivo y el de la persona al que se le mando.
