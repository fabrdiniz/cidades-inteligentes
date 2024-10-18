
# Cidades Inteligentes

Este projeto foi desenvolvido para a disciplina de DevOps, integrando práticas de CI/CD e containerização.

## Como rodar o projeto

### CI/CD
O pipeline está configurado no arquivo `.github/workflows/ci.yml`. Ele compila o projeto Java utilizando Maven.

### Docker
Para rodar a aplicação em um container Docker, utilize o comando:
```bash
docker build -t meu-app .
docker run -p 8080:8080 meu-app
```
