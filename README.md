<div align="center">
  <h1>⚡ Programación Concurrente</h1>
  <p><em>Trabajos prácticos y ejercicios de la materia Programación Concurrente (3658) - 2C 2024 - UNLaM.</em></p>

  <!-- Badges -->
  <img src="https://img.shields.io/badge/Universidad-UNLaM-1F4F90?style=for-the-badge&logo=google-scholar&logoColor=white" alt="UNLaM" />
  <img src="https://img.shields.io/badge/Año-2024-2EA043?style=for-the-badge" alt="2024" />
  <img src="https://img.shields.io/badge/Lenguaje-C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" alt="C" /><img src="https://img.shields.io/badge/-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" /><img src="https://img.shields.io/badge/-OpenMP-5391FE?style=for-the-badge" alt="OpenMP" /><img src="https://img.shields.io/badge/-CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/Grupo-M4-7057D2?style=for-the-badge" alt="Grupo M4" />
  <img src="https://img.shields.io/badge/Estado-Completado-blue?style=for-the-badge" alt="Completado" />
</div>

<br>

## 📑 Índice
- [Información de la Asignatura](#informacion-de-la-asignatura)
- [Trayecto - Infraestructura](#trayecto)
- [Docentes](#docentes)
- [Integrantes](#integrantes)
- [Unidad 1 - Programación Secuencial vs Programación Concurrente vs Programación Paralela](#unidad-1)
- [Unidad 2 - Estructura de Procesos y Threads](#unidad-2)
- [Unidad 3 - Distintos tipos de implementaciones](#unidad-3)
- [Unidad 4 - Interacción entre procesos](#unidad-4)
- [Unidad 5 - Arquitecturas Paralelas con Memoria y sin Memoria Compartida](#unidad-5)
- [Unidad 6 - Introducción a GPU](#unidad-6)
- [Herramientas Utilizadas](#herramientas-utilizadas)
- [Estructura del Proyecto](#estructura-del-proyecto)

---

<div align="center">
  <a href="https://github.com/UNLAM-PROG-C/2024-PROGC-Q2-M4" target="_blank">🔗 <strong>Repositorio de la Cátedra</strong></a>
</div>

---

<a id="informacion-de-la-asignatura"></a>
## ℹ️ Información de la Asignatura
* **Carrera**: Ingeniería en Informática
* **Asignatura**: Programación Concurrente (3658)
* **Cuatrimestre**: Segundo Cuatrimestre
* **Año**: 2024
* **Grupo**: M4

<a id="trayecto"></a>
## 🛤️ Trayecto - Infraestructura
* **Año académico**: Cuarto Año - Primer Cuatrimestre
* **Responsable / Jefe de cátedra**: Volker, Mariano Leonardo
* **Carga horaria semanal**: 4 hs
* **Carga horaria total**: 64 hs
* **Modalidad**: Semipresencial
* **Correlativas anteriores**:
  * Paradigmas de Programación (3646)
  * Sistemas Operativos (3649)

<a id="docentes"></a>
## 👨‍🏫 Docentes
* Adagio, Matías Ezequiel
* Carnuccio, Esteban
* Hirschfeldt, Darío
* Palomo, Maximo Facundo
* Volker, Mariano Leonardo

<a id="integrantes"></a>
## 👥 Integrantes
<div align="center">

| DNI | Apellido/s | Nombre/s |
| :--: | :--: | :--: |
| **43.630.151** | Antonioli | Iván Oscar |
| **43.664.669** | Di Nicco | Luis Demetrio |
| **41.548.235** | Sandoval Vasquez | Juan Leandro |

</div>

---

<a id="unidad-1"></a>
## Unidad 1 - Programación Secuencial vs Programación Concurrente vs Programación Paralela

<div align="center">
  <img src="https://github.com/user-attachments/assets/1209fdfa-5b58-4a62-9b4f-f818a1f7d708" alt="¿Qué es la Programación Concurrente?" width="700" />
  <br>
  <sup><em>Conceptos fundamentales y definición de Programación Concurrente</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/7b9bcb01-4cbb-4be1-84a8-88a75ca91051" alt="Concurrencia vs Paralelismo" width="700" />
  <br>
  <sup><em>Diferencias entre Concurrencia y Paralelismo en ejecución de tareas</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/1660a756-d630-47df-b4e5-93dbe8306464" alt="Multiproceso" width="700" />
  <br>
  <sup><em>Arquitectura y ejecución de múltiples procesos en hardware</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/48dc162e-f872-4980-9987-8d67b4da2487" alt="Multitarea" width="700" />
  <br>
  <sup><em>Estrategias de multitarea y compartición de tiempo de CPU</em></sup>
</div>
<br>

* Necesidad de la programación concurrente y paralela.
* Arquitecturas de hardware que soportan la programación concurrente y paralela.
* Concepto de proceso.
* Proceso pesado y Liviano.
* Concepto de Multitarea, multiprocesamiento.

---

<a id="unidad-2"></a>
## Unidad 2 - Estructura de Procesos y Threads

<div align="center">
  <img src="https://github.com/user-attachments/assets/403a57d9-77f9-4110-a920-f87bbcb59d41" alt="Diagrama PCB y TCB" width="700" />
  <br>
  <sup><em>Estructura de bloques de control: PCB (Procesos) y TCB (Hilos)</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/00d7ab82-7e64-43ce-bc0c-318f75a60744" alt="Ciclo de Vida de un Proceso" width="700" />
  <br>
  <sup><em>Transiciones de estado en el ciclo de vida de un proceso</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/f5dbb5ab-e039-45f6-9444-da18c9c7efe4" alt="Hilos" width="700" />
  <br>
  <sup><em>Modelo de ejecución multihilo y compartición de espacio de direcciones</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/4deaab06-38a9-4697-b5e6-9a2da8bb053d" alt="Thread Pool" width="700" />
  <br>
  <sup><em>Administración y reutilización de hilos mediante Thread Pools</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/35915022-e5c4-4ee3-b076-89241b704033" alt="Multithreading" width="700" />
  <br>
  <sup><em>Patrones y arquitecturas de aplicaciones multihilo</em></sup>
</div>
<br>

* PCB:
  * Ciclo de vida de un proceso.
  * Cambios de Contexto/Atomicidad.
  * Grafos de precedencia.
  * Creación de proceso (`fork`, `exec`).
  * Terminación de procesos (`wait`).
* TCB:
  * Tipos de threads (Kernel y Usuario).
  * Estados de Threads.
  * Thread Pools.
  * Creación de Threads.
  * Aplicaciones Multithreading.

---

<a id="unidad-3"></a>
## Unidad 3 - Distintos tipos de implementaciones

<div align="center">
  <img src="https://github.com/user-attachments/assets/a51f8c73-9a26-41e7-abae-f2966e7f85fd" alt="Concurrencia y Paralelismo" width="700" />
  <br>
  <sup><em>Integración de concurrencia en software con paralelismo en hardware</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/cf01e4b5-712b-4c88-95d9-0d72d00e9725" alt="Erlang - Lenguaje de Programación Concurrente" width="700" />
  <br>
  <sup><em>Modelo de actores y concurrencia sin estado en Erlang</em></sup>
</div>
<br>

* Cómputo paralelo y distribuido.
* Concurrencia y paralelismo.
* Concurrencia HW y SW.
* Relación con el sistema operativo.
* Requerimientos para el sistema operativo.
* Relación con el lenguaje.
* Requerimientos para el lenguaje.
* Lenguajes de programación concurrente.

---

<a id="unidad-4"></a>
## Unidad 4 - Interacción entre procesos

<div align="center">
  <img src="https://github.com/user-attachments/assets/fccf963d-7574-494f-8087-5b658b1b8684" alt="POSIX" width="700" />
  <br>
  <sup><em>Estándar POSIX e interfaces de comunicación interproceso (IPC)</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/46fc18d0-5848-4740-8f9a-239454b7927b" alt="Deadlock" width="700" />
  <br>
  <sup><em>Condiciones y prevención de interbloqueos (Deadlocks)</em></sup>
</div>
<br>

* IPC.
* POSIX.
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

---

<a id="unidad-5"></a>
## Unidad 5 - Arquitecturas Paralelas con Memoria y sin Memoria Compartida

<div align="center">
  <img src="https://github.com/user-attachments/assets/dbacef8a-f948-4143-89e1-b75d0c0fec96" alt="Taxonomía de Flynn" width="700" />
  <br>
  <sup><em>Clasificación de arquitecturas paralelas según la Taxonomía de Flynn</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/7b732e6c-f070-4eea-a154-4caf22e60537" alt="OpenMP" width="700" />
  <br>
  <sup><em>Paralelización de bucles y regiones críticas mediante OpenMP</em></sup>
</div>
<br>

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
* Ley de Amdahl.
* Ley de Moore.

---

<a id="unidad-6"></a>
## Unidad 6 - Introducción a GPU

<div align="center">
  <img src="https://github.com/user-attachments/assets/6095c29a-ce3d-4069-9a35-fac21e1b616e" alt="CPU vs GPU - Diferencias" width="700" />
  <br>
  <sup><em>Comparativa arquitectónica entre procesadores (CPU) y aceleradores (GPU)</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/4b0b60cd-66b7-4eb3-8278-9c6f6a62c3d8" alt="CPU vs GPU - Esquema" width="700" />
  <br>
  <sup><em>Esquema de núcleos masivos y ancho de banda en GPU vs CPU</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/2f5f434d-5180-4109-bfdd-0722ccc12004" alt="CUDA Core" width="700" />
  <br>
  <sup><em>Estructura y ejecución de unidades de cómputo CUDA Cores</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/095798ba-81ca-495a-abb4-7eabb8f67827" alt="Bloques CUDA" width="700" />
  <br>
  <sup><em>Organización jerárquica de grillas, bloques e hilos en CUDA</em></sup>
  <br><br>
  <img src="https://github.com/user-attachments/assets/85d93e34-483d-4a40-a99f-1e6be726ef63" alt="Arquitectura OpenCL" width="700" />
  <br>
  <sup><em>Modelo de plataforma y ejecución heterogénea en OpenCL</em></sup>
</div>
<br>

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

---

<a id="herramientas-utilizadas"></a>
## 🛠️ Herramientas Utilizadas
* **C / C++**: Lenguajes principales de programación empleados para el desarrollo de aplicaciones concurrentes y paralelas.
* **POSIX Threads (pthreads)**: Biblioteca estándar para la gestión de hilos, sincronización y exclusión mutua en entornos UNIX/Linux.
* **OpenMP**: API para la paralelización basada en directivas de compilador sobre arquitecturas de memoria compartida.
* **MPI (Message Passing Interface)**: Estándar de paso de mensajes utilizado para computación distribuida y arquitecturas sin memoria compartida.
* **NVIDIA CUDA / OpenCL**: Frameworks y plataformas de computación masiva en GPU (GP-GPU).
* **GCC / G++ / Make**: Herramientas de compilación y automatización de builds.

---

<a id="estructura-del-proyecto"></a>
## 📁 Estructura del Proyecto
```text
📦 ProgramacionConcurrente
 ┣ 📂 Unidad_01_Introduccion
 ┣ 📂 Unidad_02_Procesos_y_Threads
 ┣ 📂 Unidad_03_Implementaciones
 ┣ 📂 Unidad_04_IPC_y_Sincronizacion
 ┣ 📂 Unidad_05_Arquitecturas_Paralelas_OpenMP_MPI
 ┣ 📂 Unidad_06_GPU_CUDA_OpenCL
 ┗ 📜 README.md
```
