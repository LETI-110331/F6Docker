# F6Docker - Ficha 6 (Engenharia de Software)

Projeto base para a Ficha 6 de Docker.

## 📦 Estrutura
- `docker-compose.yml`: Configuração para WordPress + MySQL
- `.devcontainer/`: Configuração do Dev Container
- `Docker/`: Prints e evidências

---

## 🐳 Imagens Docker Utilizadas por Aluno

> ⚠️ **ATENÇÃO**: Cada aluno deve usar uma imagem **diferente**. Consulta a tabela abaixo antes de escolher a tua!

| Aluno | Imagem Docker | Porta(s) | Estado |
|-------|---------------|----------|:------:|
| **110331** | `postgres:latest` | 5432 | ✅ Reservada |
| *(próximo)* | — | — | ⬜ Livre |
| *(próximo)* | — | — | ⬜ Livre |
| *(próximo)* | — | — | ⬜ Livre |

### Sugestões de imagens disponíveis:
- `redis:latest` (porta 6379)
- `mysql:8` (porta 3306)
- `rabbitmq:management` (portas 5672, 15672)
- `nginx:alpine` (porta 80)
- `mariadb:latest` (porta 3306)
- `elasticsearch:8.5.0` (portas 9200, 9300)

---

## 🚀 Dev Container (DEV-05)

O Dev Container foi configurado utilizando a imagem base `mcr.microsoft.com/devcontainers/base:ubuntu` com suporte a Docker-in-Docker.

**Status Final:**
- O contentor foi criado com sucesso via CLI (`devcontainer up`).
- O repositório local está montado em `/workspaces/F6Docker` dentro do contentor.
- O IntelliJ (host) monitoriza o contentor, garantindo um ambiente de desenvolvimento isolado e consistente.
