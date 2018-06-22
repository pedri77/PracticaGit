## PracticaGit

### Preguntas:

#### ¿Qué comando utilizaste en el paso 11? 
`$ git reset --hard HEAD~1`

#### ¿Por qué? 
Deshacemos los cambios como dice la pregunta y colocamos el puntero HEAD donde nos interesa. 
La acción que realiza es retroceder al commit anterior y modificar el working copy.

#### ¿Qué comando o comandos utilizaste en el paso 12? 
`$ git reset --hard HEAD~1`
'$git reflog`
`$ git reset hash` 

#### ¿Por qué? 
Volvemos al punto de partida, miramos el hash del commit al que queremos llegar y con git reset regresamos a él.

#### El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No, ya estabamos en la rama que queríamos absorber.
El resultado que nos arroja el comando es Already up to date

#### El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Si, hay conflicto con las lineas de los archivos a fusionar

#### El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, no hay duplicidad en las lineas que se fusionan.

#### ¿Qué comando o comandos utilizaste en el paso 25? 
`$ git log graph`
Podemos añadir los comandos --decorate --pretty=online para que sea más explícito.

#### El merge del paso 26, ¿Podría ser fast forward? 
Si.

#### ¿Por qué? 

Puesto que sigue siendo una lista de commits y no perdemos acceso a los commits anteriores, igual que en el paso 21. Solo avanzaria el puntero master al commit donde esta el puntero title.

#### ¿Qué comando o comandos utilizaste en el paso 27? 
`$ git reflog` 
`$git reset (hash)`

#### ¿Qué comando o comandos utilizaste en el paso 28? 
`$ git reset (hash)`

#### ¿Qué comando o comandos utilizaste en el paso 29? 
`$ git branch -d title`

#### ¿Qué comando o comandos utilizaste en el paso 30?
`$git reset hash`

#### ¿Qué comando o comandos usaste en el paso 32? 
`$ git checkout 06431e5`

#### ¿Qué comando o comandos usaste en el punto 33? 
`$ git checkout bbdbeca`


![Terminado](https://media.giphy.com/media/26uf46Qn9snLBDfwc/giphy.gif)
