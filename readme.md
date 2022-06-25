1 Utilice el comando "git reset --hard HEAD~1" debido a que necesitabaperder los cambios realizados en el "working copy"

2 El documento decia "Rehacer el último commit" entonces yo volvi a hacer los cambios en "git-nuestro.md" seguido de esto los comando "git add" y "git commit" para crear un nuevo commit.

3 El merge no creo ningun conflicto debido a que nos dice que el archivo esta actualizado o como dice la consola "already up-to-date", entiendo por esto que los cambios hechos en escritura como del tipo cursiva no se consideran cambios, espero tener
una aclaración de este punto cuando califiquen esta parte por favor.

4 Si genero conflicto, debido a cambios en el documento "git-nuestro.md"

5 No causo conflicto, se hizo merge fastfowrd.

6 Utilice el comando "git log --graph"

7 Si podria ser perfectamente un fast-fowar porque no se perderia información al hacerlo entonces git no tiene que aplicar la ley "CYA"

8 Utilice el comando "git reset HEAD~1" porque no tenia que realizar cambios al working copy

9 Utilice el comando "git restore git-nuestro.md"

10 Utilice el comando "git branch -D title" debido a que era una rama que no habia hecho merge por la ubicación actual no se podia usar "git branch -d title"

11 Utilice los comando "git reflog" para encontrar la identificación del commit donde hice el merge, para luego hacer "git reset e498deb (identificación del commit)"

12 Ya tenia las identificaciones por el "reflog" utilizado en la pregunta 11, entonces solamente utilice "git checkout" y el identificador de este para ponerme en este punto.

13 Utilice "git checkout main" para volver a la rama main.
