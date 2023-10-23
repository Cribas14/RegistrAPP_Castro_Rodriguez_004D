Primero en la maquina local desinstalamos e instalamos nuevamente ionic
desintalamos --> npm uninstall -g ionic
instalamos --> npm install -g @ionic/cli@6
para luego instalar json -->  npm install -g json-server
dentro de DATA corremos el json ---> json-server --watch usuarios.json --host 0.0.0.0 --port 3300
abrimos servidor ---> ionic lab
