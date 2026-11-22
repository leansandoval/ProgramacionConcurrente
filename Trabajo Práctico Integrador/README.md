# Trabajo Práctico Integrador

[Manual de Usuario](https://github.com/leandrojsandoval/ProgramacionConcurrente/blob/main/Trabajo%20Practico%20Integrador/TP1_Integrador_M4.pdf)

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

## Aclaraciones
- Ante cualquier consulta de commits, cambios efectuados o saber la rama actual, se puede usar: `git status`
  
- Antes de hacer un commit es recomendable bajar los cambios que pudieron haberse producido con: `git pull`

- En caso de que estes trabajando en una rama y en este momento haya ocurrido algún PR en develop tenés que hacer lo siguiente (lo que estarías haciendo es bajarte los nuevos cambios aprobados del/los PR y tambien tenerlos en tu rama local que estás trabajando)
  - `git checkout develop`
  - `git pull`
  - `git checkout nombreDeLaRamaEnLaQueEstabasTrabajando`
  - `git merge develop`

- Si querés ver todas las ramas que se encuentran: `git branch -a`
  
- Te podés posicionar en una rama con: `git checkout nombreDeLaRama`
