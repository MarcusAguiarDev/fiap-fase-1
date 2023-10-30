## Execução

Para executar o projeto, certifique-se que você possui Docker instalado e atualizado.

Para executar o projeto em modo de produção, execute:

```bash
docker compose up -d
```

Para executar o projeto em modo de desenvolvimento, permitindo a alteração em tempo real dos arquivos:

```bash
docker compose -f docker-compose.yaml -f docker-compose.override.dev.yaml up -d
```

Após executar a aplicação em qualquer um dos modos, acesse <http://localhost:3000/api-docs> para consultar a documentação da API
