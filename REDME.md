#gitnotes
Github es un sistema de control de versiones online
Se puede utilizar git, desde linux o Guindows para conectarse a la cuenta de github
Si requerimos conectarnos via html, debemos considerar la ruta como:
http://github.com/argenis2021/repositorio
Si requerimos conectarnos vía ssh debemos considerar la ruta como:
git@github.com:argenis2021/repositorio
en esta ultima opición olvidé donde guardé la llave pública (publicKey)
Para agregar un repositorio a la carpeta local, o conectar  la carpeta al repositorio es necesario configurarlo como sigue:
$ git remote add NombreCualquiera http://github.com/argenis2021/repositorio
Se puede verificar los nombres de los repositorios asignados a la carpeta local mediante:
$git remote -v
Se puede cambiar la dirección del repositorio remoto :
$git remote set-url NombreCualquiera http://nuevadirección
La publikey del ssh se encuentra en el siguiente directorio
~/.ssh
