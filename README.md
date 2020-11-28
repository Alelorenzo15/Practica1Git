# RESPUESTAS PRACTICA
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1 . Ya que si usas un reset normal no me borraria los cambios del WC !! solo desharia el commit 

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
al utilizar en el paso anterior git reset --hard HEAD~1 , he vuelto a hacer un commit de forma normal con todos sus pasos , mod el archivo.md + add + commit 

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
Consigo : Already up to date. 
Este mensaje significa que todos los cambios de la rama que intento fusionar ya se han fusionado con la rama en la que se encuentra actualmente.
Es decir,que la rama que está intentando fusionar es como el padre de su rama actual.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
SI ya que en dos ramas diferentes hemos modificado el mismo archivo en las mismas lineas . 

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No y hace un Merge Fast-forward.

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --oneline .

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
No ya que crearia un conflicto con la otra rama

- ¿Qué comando o comandos utilizaste en el paso 27?
Primero un git log para ver el nombre del commit al que quiero retroceder y luego git reset --hard 76a1a4e287a6310eb44ebc6f8927cc3d0e0b7765

- ¿Qué comando o comandos utilizaste en el paso 28?
Nose a que se refiere ... 

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D 

- ¿Qué comando o comandos utilizaste en el paso 30?
No se puede rehacer el merge ya que hemos borrado la ramma de title 
No se puede mergear con algo que ya hemos borrado

- ¿Qué comando o comandos usaste en el paso 32?
git log para vr los commits y luego un git checkout mas el nombre del commit 

- ¿Qué comando o comandos usaste en el punto 33?
git checkout mas en nombre del commit mirando en el git log anteorir ya que los commits nunca se borran . 
