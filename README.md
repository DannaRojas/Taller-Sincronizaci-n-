# Taller Sincronización 

## Descripción 

Este taller contiene dos actividades con el objetivo de comprender y aplicar técnicas de concurrencia, procesos, hilos y sincronización utilizando la interfaz POSIX en C.

El taller se divide en dos actividades principales:

  1. Productor–Consumidor con semáforos POSIX con nombre y memoria compartida

  2. Sincronización entre hilos con pthreads, mutex y variables de condición

### Primera Actividad 

Implementación de funciones auxiliares para realizar multiplicación clásica de matrices, utilizando procesos creados con fork().
Cada proceso se encarga de partes específicas del cálculo, demostrando el uso de IPC y coordinación básica entre procesos.

Para esta actividad se tiene el Makefile, consumidor.c, header.h y productor.c

### Segunda Actividad 

En esta actividad se trabaja con subprocesos POSIX (pthreads) para crear múltiples hilos de ejecución dentro de un mismo proceso. 
Dado que los hilos comparten el mismo espacio de memoria, es necesario asegurar que no accedan simultáneamente a recursos críticos.
Por lo que esta se centra en aplicar mecanismos de exclusión mutua y sincronización, permitiendo que los hilos coordinen 
el acceso a variables compartidas y eviten condiciones de carrera, de esta manera garantizar un buen funcionamiento.

Para esta actividad se tiene el Makefile, concurrenciaPosix.c, concurrenciaPosix.h, posixSincro.c, posixSincro.h y la prueba txt.

## Integrantes 

Danna Rojas Bernal

María Fernanda Velandia Gracia

Christian Becerra Enciso

Giovanny Andrés Durán Rentería
