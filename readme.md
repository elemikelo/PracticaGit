#¿Qué comando utilizaste en el paso 11? ¿Por qué?
Utilicé el comando "reset --hard HEAD~1" ya que la el metodo 'hard' pierde todos los cambios realizados
en el working copy y la sintaxis "HEAD~1" significa que iremos a un commit anterior al que estabamos.

#¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Utilicé el comando "reflog" para averiguar el "SHA" del commit que deshice y luego uticé un reset --hard
(SHA del commit)

#El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, porque styled ya contiene a master.

#El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si porque al hacer el merge las lineas de los archivos eran distintas.

#El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque ya contiene a master

#¿Qué comando o comandos utilizaste en el paso 25?
Usé el comando git graph porque previamente tengo una config global para todos
mis proyectos --> git config --global alias.grap "log --graph --decorate --pretty=oneline --abbrev-commit"

#El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si también, ya que no perdería ningun commit.

#¿Qué comando o comandos utilizaste en el paso 27?
 Usé el comando : git reset --hard HEAD~1

#¿Qué comando o comandos utilizaste en el paso 28?
git checkout -- git-nuestro.md

#¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

#¿Qué comando o comandos utilizaste en el paso 30?
git reset --hard SHA donde hicimos el merge

#¿Qué comando o comandos usaste en el paso 32?
git reflog / git checkout SHA (Commit inicial)

#¿Qué comando o comandos usaste en el punto 33?
git reflog / git checkout SHA (Commit final)
