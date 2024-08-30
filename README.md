# Projeto Node.js com Docker

Este é um projeto Node.js configurado para desenvolvimento e testes usando Docker. Este guia explica como iniciar o container de desenvolvimento e executar os testes.

### Baixar Repositório
```bash
git clone https://github.com/ricardo-souza-dev/node.git
cd node.git
```
### Iniciar Node Modules
```bash
npm install
```

### Iniciar Ambiente de Desenvolvimento
```bash
docker-compose up --build
```

### Executar teste
```bash
docker-compose run --rm app npm test
```

### Verificar Logs
```bash
docker-compose logs app
```

### Encerrar Ambiente de Desenvolvimento
```bash
docker-compose down
```

