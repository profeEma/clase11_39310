Comandos git

Descargamos git de la pagina oficial
Instalamos el ejecutable (tildar la opción de: git bash here)
Corroboramos en la consola si se instalo git usando el comando: git -v
Configuramos nuestro perfil de git con los siguientes comandos:
git config --global user.name "nombre de usuario"
git config --global user.email email@tuemail.com 
Luego corroboramos si la configuración impacto correctamente:
git config user.name
git config user.email
Abrimos nuestro root en el VSC
Tocamos sobre "Terminal" -> nueva terminal
Tocamos sobre el select que esta al lado del " + " y seleccionamos git bash
A continuación se nos abre el bash posicionado en el root y usamos el comando: git init por primera y unica vez
Gracias a este comando, nos encontramos en el working directory (1er estado) Acá es donde generamos las lineas de codigo y cuando terminamos de trabajar completamos el pasaje de estados con:
git add . (pasaje por lote)
git add nombreArchivo (pasaje individual)
Esto hace que pasemos todo del working directory al staging area (2do estado)
Instantaneamente recomendamos pasar todo al repo (3er estado). Para eso usamos el comando:
git commit -m "comentario alusivo al trabajo que realizamos en codigo". 
Al ejecutar este ultimo comando, se nos genera una version y nos posiciona automaticamente en el working directory para volver a empezar.