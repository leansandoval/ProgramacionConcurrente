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

<img width="700" alt="¿Qué es la Programación Concurrente?" src="https://github.com/user-attachments/assets/1209fdfa-5b58-4a62-9b4f-f818a1f7d708" />

<img width="700" alt="Concurrencia vs Paralelismo" src="https://github.com/user-attachments/assets/7b9bcb01-4cbb-4be1-84a8-88a75ca91051" />

<img width="700" alt="Multiproceso" src="https://github.com/user-attachments/assets/1660a756-d630-47df-b4e5-93dbe8306464" />

<img width="700" alt="Multitarea" src="https://github.com/user-attachments/assets/48dc162e-f872-4980-9987-8d67b4da2487" />

* Necesidad de la programación concurrente y paralela.
* Arquitecturas de hardware que soportan la programación concurrente y paralela.
* Concepto de proceso.
* Proceso pesado y Liviano.
* Concepto de Multitarea, multiprocesamiento.

## Unidad 2 - Estructura de Procesos y Threads.

<img width="700" alt="Diagrama PCB y TCB" src="https://github.com/user-attachments/assets/403a57d9-77f9-4110-a920-f87bbaa59d41" />

<img width="700" alt="Ciclo de Vida de un Proceso" src="https://github.com/user-attachments/assets/00d7ab82-7e64-43ce-bc0c-318f75a60744" />

<img width="700" alt="Hilos" src="https://github.com/user-attachments/assets/f5dbb5ab-e039-45f6-9444-da18c9c7efe4" />

<img width="700" alt="Thread Pool" src="https://github.com/user-attachments/assets/4deaab06-38a9-4697-b5e6-9a2da8bb053d" />

<img width="700" alt="Multithreading" src="https://github.com/user-attachments/assets/35915022-e5c4-4ee3-b076-89241b704033" />

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

<img width="700" alt="CPU vs GPU - Diferencias" src="https://github.com/user-attachments/assets/6095c29a-ce3d-4069-9a35-fac21e1b616e" />

<img width="700" alt="CPU vs GPU - Esquema" src="https://github.com/user-attachments/assets/4b0b60cd-66b7-4eb3-8278-9c6f6a62c3d8" />

<img width="700" alt="CUDA Core" src="https://github.com/user-attachments/assets/2f5f434d-5180-4109-bfdd-0722ccc12004" />

<img width="700" alt="Bloques CUDA" src="https://github.com/user-attachments/assets/095798ba-81ca-495a-abb4-7eabb8f67827" />

<img width="700" alt="Arquitectura OpenCL" src="https://github.com/user-attachments/assets/85d93e34-483d-4a40-a99f-1e6be726ef63" />

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
  <img width="700" alt="Compare & pull request" src="https://github.com/user-attachments/assets/9110bbb4-5e95-4af5-9db2-7b44d947ad37" />
</p>

8. Antes de crearlo, podes asignar los reviewers para que realicen comentarios sobre el código del PR

<p align="center">
  <img width="700" alt="Assign reviewers" src="https://github.com/user-attachments/assets/33fdfaba-0caf-4ca3-9eb6-27652ef52dfd" />
</p>

9. Luego creamos el PR con `Create pull request`

<p align="center">
  <img width="700" alt="Create pull request" src="https://github.com/user-attachments/assets/75ae0139-4a21-4aa1-a70b-e3504fa7069f" />
</p>

10. Después cuando se verifiquen los chequeos del Coding Standard debería habilitarse el botón `Merge pull request` y para finalizar ya podés eliminar la rama con `Delete branch`

<p align="center">
  <img width="700" alt="Merge pull request" src="https://github.com/user-attachments/assets/95b52100-2525-4585-9ff7-25053a70960a" />
</p>

10.1 En caso de que alguno de los chequeos del Coding Standard no se aprueben, se debe cerrar el PR, realizar los cambios en el código de correcciones, es decir, repetir los pasos de 4 al 6, y luego reabrir el PR.

<p align="center">
  <img width="700" alt="Close pull request" src="https://github.com/user-attachments/assets/bf7e3f76-6b76-4e7d-9f69-609954459fcd" />
</p>

<p align="center">
  <img width="700" alt="Reopen pull request" src="https://github.com/user-attachments/assets/f05f2051-75c3-4ed6-a75c-036bff7d093c" />
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
