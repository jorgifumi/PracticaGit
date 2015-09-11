#Respuestas Ejercicio 1


**- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**
`$ git reset --hard HEAD~1`
Porque con el comando *git reset* muevo el puntero *HEAD* y la rama en la que me encuentro al paso anterior (Indicado con ~1) y con el parámetro *--hard* especifico que se pierdan los cambios que hubiera hecho en el *working copy*

**- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
Primero `$ git reflog` Para localizar el hash del commit al que quiero volver, la copio y vuelvo a ella con `$ git reset --hard`, seguido del hash, para que se quede el *working copy* como estaba antes del paso 11.

**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No, porque *htmlify* ya contenía toda la información de *master* con lo cual no se produjo ningún cambio.
 
**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí, porque el archivo poem.md tenía modificaciones en las líneas 1 y 2 en ambas ramas.

**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No, porque era fast-forward.

**- ¿Qué comando o comandos utilizaste en el paso 25?**

`$ git log --graph --decorate`

**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si, porque las ramas formaban una lista.

**- ¿Qué comando o comandos utilizaste en el paso 27?**

`$ git reset HEAD~1`

**- ¿Qué comando o comandos utilizaste en el paso 28?**

`$ git checkout -- poem.md`

**- ¿Qué comando o comandos utilizaste en el paso 29?**

`$ git branch -D title`

**- ¿Qué comando o comandos utilizaste en el paso 30?**

`$ git reflog`

`$ git reset --hard` seguido del hash del commit resultado del merge original.

**- ¿Qué comando o comandos usaste en el paso 32?**

`$ git reflog`

`$ git reset --hard` seguido del hash del commit inicial.


**- ¿Qué comando o comandos usaste en el punto 33?**

`$ git reflog`

`$ git reset --hard` seguido del hash del commit final.

