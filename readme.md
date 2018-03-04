# Práctica GIT - Respuestas

### Navarro Hernández, Sandra

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Porqué?**

`git reset --hard HEAD~1` 

Porque utilizando este comando deshacemos el último commit y también lo que se encuentra en el working copy.

--

**2. El merge del paso 13, ¿causó algún conflicto? ¿Porqué?**
 
Sí, causó conflicto ("already up to date"), ya que estamos intentando unir dos ramas que tienen los mismos commits.

--

**3. El merge del paso 19,¿causó algún conflicto? ¿Porqué?**

Si, causó conflicto, ya que en cada archivo hay una información diferente, por tanto no se pueden unir las ramas. La solución que le he dado ha sido editar uno de los dos archivos con la información que prefiero conservar,en este caso la de la rama "styled". Después, añado el archivo al staging area y posteriormente al repositorio, para poder mergear las ramas sin problema.

--

**4. El merge del paso 21, ¿causó algún conflicto? ¿Porqué?**

No causó ningún conflicto, ya que se puede "absorber" toda la información de la rama mergeada.

--

**5. El merge del paso 26, ¿podría ser fast forward? ¿Porqué?**

Sí, podría serlo, ya que sólo haría falta mover el puntero de la rama master al lugar donde está el de la rama title para acceder a todos los commits. 

--

**6. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` o `git reset HEAD don-quijote.md`

--

**7. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout -- don-quijote.md`

--

**8. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`

--

**9. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reset --hard <código del commit>`

--

**10. ¿Qué comando o comandos usaste en el paso 32?**

`git checkout <código del commit>` 

--

**11. ¿Qué comando o comandos usaste en el paso 33?**

`git checkout <código del commit>`  


