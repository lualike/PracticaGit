> ¿Qué comando utilizaste en el paso 11? ¿Por qué?

Git reset --hard HEAD~1 sirve para deshacer tanto el stage area como el working area, ya que se nos pide que lo borremos todo.

> ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Primero git reflog para ver el número identificador de commit y después git reset HEAD~1 ya que este comando deshace el paso anterior, para rehacer el commit.
>  
>  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No.

>  El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Causa un conflicto ya que las ramas están en diferentes ramas a la misma altura. Para solucionarlo, editamos el archivo don-quijote.md y hacemos un commit.
>  
>  El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No encontramos ningún conflicto ya que está en una rama distinta a una altura distinta, también.

>  ¿Qué comando o comandos utilizaste en el paso 25?

Git log --graph
>  El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

No porque mi gráfico no va en línea recta, tiene ramas salientes y por lo tanto no se podría hacer un fast-forward.
>  ¿Qué comando o comandos utilizaste en el paso 27?

 Git reset HEAD~1
> 
>  ¿Qué comando o comandos utilizaste en el paso 28?

Git reset --hard HEAD~1
> 
>  ¿Qué comando o comandos utilizaste en el paso 29?

Git branch -D title
>  ¿Qué comando o comandos utilizaste en el paso 30?

Git reset --hard
> 
>  ¿Qué comando o comandos usaste en el paso 32?

Git checkout + número identificador del commit inicial
>
>  ¿Qué comando o comandos usaste en el punto 33?

Git reset 