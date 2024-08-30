# Projeto Node.js com Docker

Este é um projeto Node.js configurado para desenvolvimento e testes usando Docker. Este guia explica como iniciar o container de desenvolvimento e executar os testes.

## Requisitos

Antes de começar, certifique-se de que você tem os seguintes requisitos instalados:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Estrutura do Projeto

- **Dockerfile**: Define o ambiente de desenvolvimento e a configuração do container.
- **docker-compose.yml**: Configuração para orquestrar os containers de desenvolvimento e serviços adicionais como MongoDB e Redis.
- **package.json**: Define as dependências e scripts de desenvolvimento e teste.

## Configuração

### Clone o Repositório

Clone este repositório para sua máquina local:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
