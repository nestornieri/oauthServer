El proyecto OAUTH2.0 server y recurso se ejecutan en conjunto.
Para realizar pruebas en postman usar estas credenciales.


POST http://localhost:9000/oauth2/token
Basic Auth: user: postman-client  password:secret
Body: grant_type=client_credentials  &  scope=read write


GET http://localhost:8080/api/test
Bearer Token: <token-obtenido>
