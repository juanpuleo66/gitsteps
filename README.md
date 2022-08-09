# youtube.com

# 12 comandos de git que debes usar

# Fernando Herrera

# Comandos utiles de git

1.  git init
2.  git add . --> sube archivos al escenario stage
3.  git reset . --> revierte lo que hace el git add .
4.  git commit -m 'mensaje' -->
5.  git checkout -- . --> reconstruye todo al ultimo commit
6.  git log --> muestra todos los commit realizados
7.  git commit --amend --> permite editar el ultimo commit teclas i:insertar w:guardar q:salir !:inmediato
8.  git checkout -b rama-heroes --> crea y se cambia a la rama rama-heroes
9.  git checkout master --> se cambia a la rama master
10. git merge rama-heroes --> merge lo que esta en rama-heroes en la rama actual
    git branch -d rama-heroes --> elimina la rama rama-heroes
11. git push --> sube los cambios a github
12. git commit -am 'mensaje' --> ejecuta git add . y git commit -m en una linea

# desde github

1. git remote add origin https://github.com/juanpuleo66/gitsteps.git
2. git branch -M main
3. git push -u origin main
