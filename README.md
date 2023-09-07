# reposito-sgdc
git init  Inicializas  git 
git branch -m main
git checkout -b main

touch proceso1.jdk
touch proceso2.css

git config --global core.autocrlf  true
Elimina  el Mensaje:            warning: LF will be replaced by CRLF in 

Se encuentra en el estado LOCAL
git add proceso1.jdk proceso2.css
git  add . 
git  status


Agrega todos los elementos  pendientes por add
Consultas y deberán estar de color Verde
Se encuentra en el estado  STAGE
git commit -m "Carga Inicial sgdc"

git  status
Muestra que esta  limpio 
On branch main
nothing to commit, working tree clean
git reflog


• Se modifica el proceso1.jdk y se hace add, commit
• Se Modifican los dos procesos  proceso1.jdk   y  proceso2.css   y se hace add, commit

Fin de la carga inicial y modificaciones en la Rama Principal main
git remote add origin https://github.com/cantprueba/reposito-sgdc.git
