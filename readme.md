- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reset --hard HEAD~1

Porque para eliminar el working copy hay que hacerlo con --hard

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reset --hard f1adfa1

Porque quiero volver exactamente a lo que tenía en el paso commit del paso 10.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No se ha generado ningún conflicto, de hecho el mensaje es 'Already up to date.' 
porque es un merge por defecto ff.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Sí se ha generado un conflicto porque, al hacer el merge, se intentan combinar
las modificaciones markdown con las html, y ahora hay que decidir editando 
y quedándonos con las styled

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No se ha generado ningún conflicto después del merge ff porque se han cambiado todas
las líneas de texto plano a styled sólo en el working copy

- ¿Qué comando o comandos utilizaste en el paso 25?

git log --graph --pretty=oneline

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Realmente sí porque no hemos creado ramas hijas posteriores

- ¿Qué comando o comandos utilizaste en el paso 27?

git reset 8ed3de1

- ¿Qué comando o comandos utilizaste en el paso 28?

git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?

git reset 5d6f47d

- ¿Qué comando o comandos usaste en el paso 32?

git checkout HEAD@{19}

- ¿Qué comando o comandos usaste en el punto 33?

git checkout HEAD@{1}
