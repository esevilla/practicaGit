## Estefanía Sevilla Sanchís

1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?

    He utilizado el comando `git reset --hard HEAD~1`. Según la documentación de git, `--hard` restablece el índice y el árbol de trabajo. Cualquier cambio en los archivos de seguimiento en el árbol de trabajo desde el commit se descarta.

2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

    He utilizado `git reflog` para poder ver el id, y después `git reset --hard 7a70c9c` para ir al commit.
    
3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

    No hay ningún conflicto porque no hay nada que copiar de master, git nos avisa diciendo *Already up-to-date*. 
    
4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

    Hay un conflicto porque el mismo archivo está en ambas ramas con un contenido diferente. 
    
5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

    No ocasiona ningún conflicto ya que el único cambio en el archivo era la cursiva.
    
6. ¿Qué comando o comandos utilizaste en el paso 25?

    He utilizado el comando `git log --graph` ya que muestra muy clara la información de cada commit.

7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

    No, porque se ha de mantener el trabajo de master y adquirir el de la rama title.

8. ¿Qué comando o comandos utilizaste en el paso 27?

    He utilizado el comando `git reset HEAD~1`.

9. ¿Qué comando o comandos utilizaste en el paso 28?

    He utilizado el comando `git checkout -- git-nuestro.md`.

10. ¿Qué comando o comandos utilizaste en el paso 29?

    He utilizado el comando `git branch -D title`.

11. ¿Qué comando o comandos utilizaste en el paso 30?

    He usado el comando `git reflog` para buscar la id y luego he utilizado `git reset --hard 63bff72`.

12. ¿Qué comando o comandos usaste en el paso 32?

    He usado el comando `git reflog` para buscar la id y luego he utilizado `git reset --hard e9c4116`

13. ¿Qué comando o comandos usaste en el punto 33?

    He usado el comando `git reflog` para buscar la id y luego he utilizado `git reset --hard 63bff72`