# Projeto Node.js com Docker

Este é um projeto Node.js configurado para desenvolvimento e testes usando Docker. Este guia explica como iniciar o container de desenvolvimento e executar os testes.

### Iniciando o projeto

Segue abaixo os comandos a executar:

```bash
git clone https://github.com/ricardo-souza-dev/node.git
cd node.git

npm install

docker-compose up --build
```
Para executar teste:

```bash
docker-compose run --rm app npm test
```

Para verificar logs:

```bash
docker-compose logs app
```

Para desativar os containers:

```bash
docker-compose down
```

