# microserviciosDocker
En el archivo submit.php, modificar el arn que figura por el creado en el paso anterior.
  - Crear un rol en la EC2 y le añadimos la política "SNSFullAccess".
  - Teclear sudo docker-compose up.
  - Acceder al formulario y rellenarlo.

## Requisitos técnicos
  -Crear un rol en la EC2 y le añadimos la política "SNSFullAccess".
  - Teclear sudo docker-compose up.s 22, 8080, 80, 3036.
  - Crear un tópico SNS. Suscribirse a ese tópico.
  - En el archivo submit.php, modificar el arn que figura por el creado en el paso anterior.
  - 
  - Acceder al formulario y rellenarlo.
Proyecto que levanta un contenedor docker con microservicios de php y mysql para a través de un servicio SNS de aws, al rellenar el formulario inserte un registro en la tabla.