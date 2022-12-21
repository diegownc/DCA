Como he utilizado git bisect:

- He provocado un fallo en el commit:
    a7162f1b1e65e9c31e3f0190a8031dd547ffcf13
    tag: error

- He hecho 4 commits haciendo pequeños cambios y arrastrando el problema

- He hecho el siguiente commando para empezar:
git bisect start

- He marcado el actual commit como erroneo
git bisect bad

- He marcado como good a partir del commit 
    2599f474c08677dd2d35f5341d391f22b6a658e2
    tag: Ok
git bisect good Ok

- Me ha salido la siguiente salida en Terminal:

usuario@ASUS:~/Escritorio/DCA/Practica 9/Usuario1$ git bisect good Ok
Bisectando: faltan 3 revisiones por probar después de esto (aproximadamente 2 pasos)
[a7162f1b1e65e9c31e3f0190a8031dd547ffcf13] README para explicar git bisect



