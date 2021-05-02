#como usar git completo.

git clone para clonar proyecto 

git status para ver el estado en que estado los archivos

git add para agregar los archivos al area de staging


git reset para volver antes del git add no agragar

git commit -m  ¨nombre¨ te permite realizar un checkpoint al que puede volver en caso de un error 

git log te permite ver todo los commmit que tengas de ta detalles de la hora y quien lo hizo 

git push origin (rama) al  hacer push estamos subiendo los cambios de nuestra rama, en este caso master 

git diff para ver las diferencias  hechas  en los  archivos

.gitignore se crea un archivo para describir los archivos a ignorar

head -n 3 ~/.gitconfig para ver la configuracion de los usuarios y correo que esta git.

git remote add origin "Link del repositorio" para indicar a que repositorio nos vamos a conectar



git pull origin (rama) permite sincronizar nuestra local (master en este caso ) con la nube

git reset head^ te permite devolver antes de que usaramosel commit 

git reset (codigo del commit) te permite volver al commit que  hasta eligido

git branch Te dira que ramas a creados y en cual estas 

git branch (nombre de la  rama) esto  crea una rama con el nombre que indentifiques, siempre quevallas a crear una rama muevete a master

git checkout (nombre de la rama) esto nos llevara a la rama elegida  (movernos entre ramas)

git push origin (nomnbre de la rama) para sincronizarlo con la rama en la nube

git merge (nombre de la rama a juntar)  esto junta 2 ramas en una sola 


...................................

para inicar sesion en git  


git config --gobal user.email ""

git config --global user.name ""

------------------------------------------


