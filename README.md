Monitor de Sensores

Este proyecto implementa un sistema de monitorización de sensores utilizando múltiples hilos en C. El sistema recibe mediciones de pH y temperatura desde un pipe nominal, los clasifica y almacena en un archivo de texto junto con la hora actual.

Compilación y Ejecución
 - Requisitos
 - Compilador GCC
Compilación

gcc -o monitor monitor.c -lpthread

./monitor -b <tam_buffer> -t <file_temp> -p <pipe_nominal>

gcc sensores.c -o sensores

./sensores -s 2 -t 3 -f datosPh.txt -p pipe1
