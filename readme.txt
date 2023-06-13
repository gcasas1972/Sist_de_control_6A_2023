pasos para solucionar el accesos a github
-----------------------------------------.

1- bajar el repositorio con
  git clone https://github.com/gcasas1972/Sist_de_control_6A_2023.git
2- generar un archivo
3- git status 
	se vera el archivo nuevo

4 - git add .
	para agregar todos los nuevos archivos
5- git status
	se vera el archivo de verde
6- git commit -m "primer archivo subido por git"
	agrega el archivo al repositorio local
7- git pusu -uf origin main
	sube el archivo a la nube pero al solicitar usuario y password se da


fatal: Authentication failed for 'https://github.com/gcasas1972/Sist_de_control_6A_2023.git/'

para solucionar este problema debemos crear un personal access token (classic)
para lo cual debemos seguir los siguientes pasos

1- en el menu desblegable de arriba a laredecha seleccionar settings
2- acceder a developer settings
3- En la barra lateral izquierda, en Personal access token , haz clic en Tokens (clásicos) . 1. Selecciona Generar nuevo token y, luego, haz clic en Generar nuevo token (clásico) 
4- En el campo "Nota", asigna un nombre descriptivo al token.
coloque la nota 
Este token es parra acceder a mi repositorio
5- Para conceder una expiración al token, selecciona Expiración y, a continuación, elige una opción predeterminada o haz clic en Personalizado para especificar una fecha.
y en la opcion de tiempo de expiración seleccione 
sin tiempo de expiracion
6-Selecciona los ámbitos que quieres concederle a este token. A fin de usar el token para acceder a repositorios desde la línea de comandos, seleccione repo. Un token sin alcances asignados solo puede acceder a información pública. Para más información, consulta "Alcances para las Apps de OAuth
7-Haga clic en Generar token.
ya se podra ver el token generado

