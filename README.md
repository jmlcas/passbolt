# passbolt
Passbolt - Administrador contraseñas - Docker compose

Ver en "localhost:8200"


Una vez que el contenedor se esté ejecutando, cree su primer usuario administrador:

$ docker exec passbolt su -m -c "bin/cake passbolt register_user -u your@email.com -f yourname -l surname -r admin" -s /bin/sh www-data

Este comando de registro devolverá una URL de un solo uso necesaria para continuar con la configuración del navegador web y finalizar el registro. 

Su instancia de passbolt debería estar disponible
