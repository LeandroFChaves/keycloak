# keycloak

docker-compose para subir keycloak localmente externalizando as configs, themes e bd (h2) para realização de testes.

Exemplo de chamada para a pagina de login:

http://localhost:8085/auth/realms/sample/protocol/openid-connect/auth?client_id=sample-ui&redirect_uri=http%3A%2F%2Flocalhost:4200&response_type=code&scope=openid