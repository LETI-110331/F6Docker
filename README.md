# F6Docker - Ficha 6 (Engenharia de Software)

Projeto base para a Ficha 6 de Docker.

## 📦 Estrutura
- `docker-compose.yml`: Configuração para WordPress + MySQL
- `.devcontainer/`: Configuração do Dev Container
- `Docker/`: Prints e evidências

## 🚀 Dev Container (DEV-05)

O Dev Container foi configurado utilizando a imagem base `mcr.microsoft.com/devcontainers/base:ubuntu` com suporte a Docker-in-Docker.

**Status Final:**
- O contentor foi criado com sucesso via CLI (`devcontainer up`).
- O repositório local está montado em `/workspaces/F6Docker` dentro do contentor.
- O IntelliJ (host) monitoriza o contentor, garantindo um ambiente de desenvolvimento isolado e consistente.
