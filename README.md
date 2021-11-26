# practica-1-git

- *¿Qué comando utilizaste en el paso 11? ¿Por qué?*
```
git reset --hard HEAD~1
```
Para deshacer el último commit borrando los cambios realizados en el working copy

- *¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?*

```
git reset --hard 18ff984
```
Hacemos Git reset --hard y añadimos el hash para recuperar el commit que hemos deshecho. (EL hash del commit lo encontramos con git reflog).

- *El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?*

No, porque está *Already up to date*
- 
- *El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?*

Si, porque hemos modificado la misma linea, en los mismos archivos, en dos ramas distintas y estamos intentando hacer un merge.

- *El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?*

No, se hace un merge Fast-forward sin conflictos. La rama está ahead of origin/main por 1 commit.

- *¿Qué comando o comandos utilizaste en el paso 25?*

```
git log --oneline --decorate --graph --all
```

- *El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?*

Sí, pero perderíamos información. Git merge --no-ff nos permite mantener los dos padres.

- *¿Qué comando o comandos utilizaste en el paso 27?*

```
git reset --hard f3901ff
```
 
- *¿Qué comando o comandos utilizaste en el paso 28?*

Para volver a la rama styled
```
git checkout title
```
Para descartar el cambio en el archivo git-nuestro.md
```
git restore git-nuestro.md
```

- *¿Qué comando o comandos utilizaste en el paso 29?*

```
git branch -d title
```

- *¿Qué comando o comandos utilizaste en el paso 30?*

```
git reset --hard 0b474bd
```
 
- *¿Qué comando o comandos usaste en el paso 32?*

```
git log
```

```
git reset --hard 3fa30dddb366556c808671a5401d4b0a8bfab33c
```
- *¿Qué comando o comandos usaste en el punto 33?*
```
git reflog
```

```
git reset --hard 
```
