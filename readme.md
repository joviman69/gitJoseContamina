## **Práctica del curso de git, gitHub y Sourcetree.**
*Jose Contamina 06/12/2017.*
#### *Respuestas ejercicio 1.*
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
```sh
git reset --hard HEAD~1
git reset HEAD~1 mueve el HEAD al commit padre (en este caso coincide con el commit anterior HEAD@{1}) y el modificador --hard devuelve el working copy al estado en el que se encontraba en aquel commit.
```
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
```sh
git reset --hard d240345
Es el id del commit anterior. También habría sido válido HEAD@{1}
```
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
```sh
git merge master no causó ningún conflicto
Las dos ramas estaban en la misma lista.
```
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
```sh
git merge htmlify causó confictos porque las dos ramas no estaban en la misma lista
```
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
```sh
git merge styled no causó conflictos porque las dos ramas estaban en la misma lista.
```
- ¿Qué comando o comandos utilizaste en el paso 25?
```sh
git grafo, que es un alias que he creado con git config --global alias.grafo "log --graph --decorate --pretty=oneline"
```
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
```sh
Sí porque ambas ramas están en la misma lista.
```
- ¿Qué comando o comandos utilizaste en el paso 27?
```sh
git reset HEAD@{1}
```
- ¿Qué comando o comandos utilizaste en el paso 28?
```sh
git checkout -- git-nuestro.md
```
- ¿Qué comando o comandos utilizaste en el paso 29?
```sh
git branch -D title
```
- ¿Qué comando o comandos utilizaste en el paso 30?
```sh
git reset --hard HEAD@{1}
```
- ¿Qué comando o comandos usaste en el paso 32?
```sh
git reset --hard 862ac5 (Que es el id correspondiente al commit inicial)

```
- ¿Qué comando o comandos usaste en el punto 33?
```sh
git reset --hard a0ef0d4 (Que es el id correspondiente al commit donde pusimos título al poema)
```
