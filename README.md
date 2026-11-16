# Programación Concurrente - UNLaM
Repositorio donde se encuentran los ejercicios correspondientes a los trabajos prácticos de la materia.

[Repositorio de la Catedra](https://github.com/UNLAM-PROG-C/2024-PROGC-Q2-M4)

## Información de la Asignatura
* **Carrera**: Ingeniería en Informática
* **Asignatura**: Programación Concurrente (3658)
* **Cuatrimestre**: Segundo Cuatrimestre
* **Año**: 2024
* **Grupo**: M4

## Trayecto - Infraestructura
* **Año académico**: Cuarto Año - Primer Cuatrimestre
* **Responsable / Jefe de catedra**: Volker, Mariano Leonardo
* **Carga horaria semanal**: 4 hs
* **Carga horaria total**: 64 hs
* **Modalidad**: Semipresencial
* **Correlativas anteriores**
  + Paradigmas de Programación (3646)
  + Sistemas Operativos (3649)

## Docentes
* Adagio, Matías Ezequiel
* Carnuccio, Esteban
* Hirschfeldt, Darío
* Palomo, Maximo Facundo
* Volker, Mariano Leonardo

## Integrantes
| DNI | Apellido/s | Nombre/s |
|--|--|--|
| 43.630.151 | Antonioli | Iván Oscar | 
| 43.664.669 | Di Nicco | Luis Demetrio |
| 41.548.235 | Sandoval Vasquez | Juan Leandro |

## Unidad 1 - Programación Secuencial vs Programación Concurrente vs Programación Paralela

![¿Qué es la Programación Concurrente?](https://website-assets.studocu.com/img/document_thumbnails/80acb00d35fa61ed568912a0df5d2d0a/thumb_1200_675.png)

![Concurrencia vs Paralelismo](https://instagram.faep28-2.fna.fbcdn.net/v/t39.30808-6/777867722_1334263052063702_8825343952451446648_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=105&_nc_map=urlgen_bucketless&ig_cache_key=Mzk2NTkwOTA1MDk1NDA1ODcyNQ%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTIzMy5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=VLJE1cCr0AYQ7kNvwGYTSQu&_nc_oc=Adq7yTGnNFr3I5E2GW5KQ5ddiG8VxztOd7yeTC7qvlA44HTJcfDy3qVbzMHrfDyIwAv2UMOks0x9Pau3cycCfftc&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-2.fna&_nc_gid=xjlPPLj6YjMs1ouJK05v7A&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQQj_DmccBA8xE5cdG_FtKXeqOgKTc87Nnix8sEBSJqRYw&oe=6B001523)

![Multiproceso](https://image.slidesharecdn.com/multiprocesoymultitarea-240614134322-8099b4c4/75/Multiproceso-Y-Multitarea-y-diferencia-entre-los-dos-pptx-2-2048.jpg)

![Multitarea](https://image.slidesharecdn.com/multiprocesoymultitarea-240614134322-8099b4c4/75/Multiproceso-Y-Multitarea-y-diferencia-entre-los-dos-pptx-4-2048.jpg)

* Necesidad de la programación concurrente y paralela.
* Arquitecturas de hardware que soportan la programación concurrente y paralela.
* Concepto de proceso.
* Proceso pesado y Liviano.
* Concepto de Multitarea, multiprocesamiento.

## Unidad 2 - Estructura de Procesos y Threads.

![Diagrama PCB y TCB](https://ducmanhphan.github.io/img/multithread/multithreading-python.png)

![Ciclo de Vida de un Proceso](https://instagram.fepa1-1.fna.fbcdn.net/v/t39.30808-6/757147237_1316215287201812_7311770153056244492_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=109&_nc_map=urlgen_bucketless&ig_cache_key=Mzk1MDUwNzc2MjM2MjY5MDUxMg%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTI0My5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=XSxIAb7zoqkQ7kNvwG9ZqUq&_nc_oc=Ado60KF8KFVKDDsjZ2xBPUEhIjHqovzIDf4A7cRjYXoHMwLBPcPLxn2V4tfbcZhJQm-iifatg4U7bj1hTIGwPmLk&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa1-1.fna&_nc_gid=BfwdSCjJgtr5S5Om8B9UJA&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQSCwjbV73Payqsl7kz4n63WBFfzxzFjHDLv36Q2iJGkcw&oe=6B002869)

![Hilos](https://instagram.fepa2-1.fna.fbcdn.net/v/t39.30808-6/714949254_122281541066189612_6530581940499800137_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=102&_nc_map=urlgen_bucketless&ig_cache_key=MzkxNjUzMzk4Mjc3NDY5NjQ2Nw%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTI1NC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=urFe4uZI4usQ7kNvwGRJfNo&_nc_oc=AdpOhlAVnjmclFAIaO-nIX0jWM_zPvD21PvmPhcZbEI6TpkH1ZrLMuOIxGNZzt1F9LKIyORrQ2tBbUw8dEUsBpn5&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa2-1.fna&_nc_gid=LLeFPff_NDP8vokhHN331w&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQSwh6r8-F5MeIkeQSqDx4JPRdBUYFGIhwoyx3J7BPjFgQ&oe=6B001BA2)

![Thread Pool](https://instagram.fepa1-1.fna.fbcdn.net/v/t39.30808-6/702326064_122278914482189612_5004793672014368232_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=109&_nc_map=urlgen_bucketless&ig_cache_key=MzkwMjgyMzQzNjcyNDc3NTI5MA%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTIwNy5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=KXL9vNOWFTMQ7kNvwHEX-T-&_nc_oc=AdoVKH8q06rFccNmJPXY5vavnc9AWOHK1pzFvXI2kJQn8D2EUUd0Q62ErR7wTyMHBexrBQ-RWPXkPQgE4BJw0rt_&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa1-1.fna&_nc_gid=u0uE_w1oRs4wgdwrr60x7g&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQRJRq52I5ZN0TJHIZYxhktkcwzqa91WxH4Vcg5aQ-0SzQ&oe=6B00431F)

![Multithreading](https://scontent.faep28-1.fna.fbcdn.net/v/t39.99422-6/861786314_29262922186678686_716351908631014262_n.png?stp=dst-jpg_tt6&cstp=mx1024x1536&ctp=s1024x1536&_nc_cat=108&_nc_map=urlgen_bucketless&ccb=1-7&_nc_sid=833d8c&_nc_eui2=AeFrgH9XMx9Lrj-RvNZQJwDP1zXAGtEStjDXNcAa0RK2MMp8rvI-q867wwfonellBp-t0eILQJAHm0sJCqt-pds7&_nc_ohc=KuWQLGxvAr4Q7kNvwGHr23H&_nc_oc=AdophSoZ_EQg3ko-wvXaXwFrbVM4-p2cvUQplW__P8vYS83rT4iejxOOpcLcvd8k5e9GkJIbRIHBbBEa14XsALt4&_nc_zt=14&_nc_ht=scontent.faep28-1.fna&_nc_gid=2b9-aCGiV5eynf8P4lDPMQ&_nc_ss=7b2a8&oh=00_AQSB2ypIyuaTuJbFRo7uTaossu_vExOUy9mJHkVu6M0vWw&oe=6B002AEB)

* PCB
    * Ciclo de vida de un proceso.
    * Cambios de Contexto/Atomicidad.
    * Grafos de precedencia.
    * Creación de proceso (Fork, Exec).
    * Terminación de procesos (Wait).
* TCB
    * Tipos de threads (Kernel y Usuario).
    * Estados de Threads.
    * Thread Pools.
    * Creación de Threads.
    * Aplicaciones Multithreading.

## Unidad 3 - Distintos tipos de implementaciones
* Cómputo paralelo y distribuido.
* Concurrencia y paralelismo.
* Concurrencia HW y SW.
* Relación con el sistema operativo.
* Requerimientos para el sistema operativo.
* Relación con el lenguaje.
* Requerimientos para el lenguaje.
* Lenguajes de programación concurrente.

## Unidad 4 - Interacción entre procesos
* IPC.
* Posix.
* Pipes.
* Colas de mensajes.
* Memoria Compartida.
* Sockets.
* Señales.
* Variables compartidas entre hilos.
* Conflictos en la comunicación entre procesos e hilos.
* Sincronización entre procesos/hilos.
* Región crítica.
* Tipos de Semáforos, monitores.
* Mutua Exclusión.
* Condición de carrera, inanición.
* Deadlock (Interbloqueo).
* Estrategias para tratar Deadlocks.
* Soluciones de concurrencia HW y SW.
* Espera activa.
* Solución de Peterson, Algoritmo de Dekker, Algoritmo de Lamport (panadería), Filósofos comensales.

## Unidad 5 - Arquitecturas Paralelas con Memoria y sin Memoria Compartida
* Arquitecturas multiprocesador, multicore, multithread.
* Historia.
* Computación de altas prestaciones (HPC).
* Modelo de FLYNN.
* Topologías de procesadores.
* Modelo de programación paralela.
* Modelo de paralelización de memoria compartida (OpenMP).
* Modelo de memoria distribuida con paso de mensajes (MPI).
* Modelo Híbrido.
* Análisis de prestaciones.
* Métricas, conceptos de speed up y eficiencia.
* Ley de Amdahl
* Ley de Moore.

## Unidad 6 - Introducción a GPU

![CPU vs GPU - Diferencias](https://instagram.faep28-2.fna.fbcdn.net/v/t51.82787-15/731058960_18127140988725919_7517522955686019274_n.webp?_nc_cat=103&_nc_map=urlgen_bucketless&ig_cache_key=MzkzMDk5NzQxMjkxMDQ1MTI0Mg%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTA4MC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=n3T1FyplLVgQ7kNvwHmPHQ4&_nc_oc=AdpofCRzN2f4ZJRchUZ387pzqdbxg88V5DhkYzXYWie2-6SGRr0D57lPhYEGwzZX7O2UtvQmGyFT8s5GY7_43CAt&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-2.fna&_nc_gid=iSC-2gksuAImntb1dTnyYA&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQR3iZCcuxk2C2jeGrxCjS-ZZjmw73A1PZIySUobsVR4zA&oe=6B0041E5)

![CPU vs GPU - Esquema](https://cvw.cac.cornell.edu/gpu-architecture/gpu-characteristics/ArchCPUGPUcores.png)

![CUDA Core](https://gbaike-image.cdn.bcebos.com/5366d0160924ab1899dd1a1436fae6cd7a890bcd/5366d0160924ab1899dd1a1436fae6cd7a890bcd_url?x-bce-process=image/format,f_auto/watermark,image_d2F0ZXJtYXJrL3dhdGVybWFyaw,t_60,g_7,xp_5,yp_2,P_20)

![Bloques CUDA](https://blog.damavis.com/wp-content/uploads/2026/01/threads_blocks_grids_cuda_architecture.webp)

![Arquitectura OpenCL](https://w2.mat.ucsb.edu/594cm/2010/benalunjones-rp1/sl_opencl_architecture.png)

* Concepto de GP-GPU.
* Filosofía CPU/GPU.
* Evolución de la GPU.
* Estructura interna, arquitectura.
* Interacción CPU-GPU.
* Modelo de programación (CUDA, OpenCL).
* Multidimensiones (Conceptos de grilla, bloques, warp).
* Jerarquía de memoria.
* Conceptos de divergencia, coalescencia, teselas.
* Análisis de prestaciones.

## Links a Google Colab
### Trabajo Práctico 1
* Parte 1: Procesos
  * [C](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%201/Procesos/C/Trabajo_Practico_1_1_Grupo_M4_Procesos_C.ipynb)
  * [Java](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%201/Procesos/Java/Trabajo_Practico_1_1_Grupo_M4_Procesos_Java.ipynb)
  * [Python](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%201/Procesos/Python/Trabajo_Practico_1_1_Grupo_M4_Procesos_Python.ipynb)
* Parte 2: Hilos
  * [C++](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%201/Hilos/C%2B%2B/Trabajo_Practico_1_2_Grupo_M4_Hilos_C%2B%2B.ipynb)
  * [Java](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%201/Hilos/Java/Trabajo_Practico_1_2_Grupo_M4_Hilos_Java.ipynb)
  * [Python](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%201/Hilos/Python/Trabajo_Practico_1_2_Grupo_M4_Hilos_Python.ipynb)
* Parte 3: Comunicación y Sincronismo
  * [C++](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%201/Comunicacion%20y%20Sincronizacion/C%2B%2B/Trabajo_Practico_1_3_Grupo_M4_Comunicacion_C%2B%2B.ipynb)
  * [Java](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%201/Comunicacion%20y%20Sincronizacion/Java/Trabajo_Practico_1_3_Grupo_M4_Comunicacion_Java.ipynb)
  * [Python](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%201/Comunicacion%20y%20Sincronizacion/Python/Trabajo_Practico_1_3_Grupo_M4_Comunicacion_Python.ipynb)

## Trabajo Práctico Integrador
  * [Manual de Usuario](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%20Integrador/TP1_Integrador_M4.pdf)

## Pasos para subir cambios al repositorio de la materia

Repositorio de la catedra: [CATEDRA de PROGRAMACION CONCURRENTE UNLAM](https://github.com/UNLAM-PROG-C)

1. Si no tenés bajado localmente el repositorio, tenés que abrirte la terminal, posicionarte en el directorio donde te lo querés bajar, y clonártelo con: `git clone https://github.com/UNLAM-PROG-C/2024-PROGC-Q2-M4.git`

2. Posicionarse en el repositorio: `cd 2024-PROGC-Q2-M4/`

3. Crear una nueva rama para subir los cambios: `git checkout -b nombreDeLaRama`

4. Luego de subir los archivos o las modificaciones: `git add .`

5. Commiteamos los archivos: `git commit -m "MensajeRelacionadoAlCommit"`

6. Pusheamos la rama: `git push` o `git push --set-upstream origin nombreDeLaRama`

7. En el repositorio de la catedra te va a aparecer un mensaje similar a este, y tenés que hacer clic en `Compare & pull request`

<p align="center">
  <img src="https://github.com/user-attachments/assets/84f13371-6ae0-4407-9df9-843e5f8cd827" alt="Compare & pull request"/>
</p>

8. Antes de crearlo, podes asignar los reviewers para que realicen comentarios sobre el código del PR

<p align="center">
  <img src="https://github.com/user-attachments/assets/4b24cb85-1f92-4169-bfe6-f412ae872203" alt="Assign reviewers"/>
</p>

9. Luego creamos el PR con `Create pull request`

<p align="center">
  <img src="https://github.com/user-attachments/assets/ad85a457-6d63-44ce-a4bd-375d89dc42dd" alt="Create pull request"/>
</p>

10. Después cuando se verifiquen los chequeos del Coding Standard debería habilitarse el botón `Merge pull request` y para finalizar ya podés eliminar la rama con `Delete branch`

<p align="center">
  <img src="https://user-images.githubusercontent.com/24505883/42899819-7c05a47a-8ac7-11e8-8be9-9e3888f1bedc.gif" alt="Merge pull request"/>
</p>

10.1 En caso de que alguno de los chequeos del Coding Standard no se aprueben, se debe cerrar el PR, realizar los cambios en el código de correcciones, es decir, repetir los pasos de 4 al 6, y luego reabrir el PR.

<p align="center">
  <img src="https://i.sstatic.net/IA4pH.png" alt="Close pull request"/>
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/35812641/192277071-e822eee6-e340-41a5-aafa-569f441bb65a.png" alt="Reopen pull request"/>
</p>

11. *(OPCIONAL)* Para finalizar, en la terminal, te podés posicionar nuevamente en la rama de develop, (`git checkout develop`) y bajarte los cambios del PR con `git pull`

12. *(OPCIONAL)* Si hiciste el paso 11 te habrás dado cuenta de que la rama que borraste todavía sigue apareciendo, eso es porque se eliminó remotamente, pero todavía se encuentra local, la podes ver con `git branch -a` y para eliminarla es con `git branch -d nombreDeLaRama`

### Aclaraciones
- Ante cualquier consulta de commits, cambios efectuados o saber la rama actual, se puede usar: `git status`
  
- Antes de hacer un commit es recomendable bajar los cambios que pudieron haberse producido con: `git pull`

- En caso de que estes trabajando en una rama y en este momento haya ocurrido algún PR en develop tenés que hacer lo siguiente (lo que estarías haciendo es bajarte los nuevos cambios aprobados del/los PR y tambien tenerlos en tu rama local que estás trabajando)
  - `git checkout develop`
  - `git pull`
  - `git checkout nombreDeLaRamaEnLaQueEstabasTrabajando`
  - `git merge develop`

- Si querés ver todas las ramas que se encuentran: `git branch -a`
  
- Te podés posicionar en una rama con: `git checkout nombreDeLaRama`
