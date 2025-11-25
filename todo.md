# Comandos:

```sh
//Abrir en windows el puerto:
netsh advfirewall firewall add rule name="SD API" dir=in action=allow protocol=TCP localport=7860


docker compose --profile download up --build

docker compose --profile auto up --build


// Abrir en el navegador web:
http://localhost:7860/


// API:
http://localhost:7860/v1/chat/completions

Postman esta el body



```
