# Cliente SIGAA Javascript

Este repositório implementa a integração com o SIGAA, tendo 2 principais funcionalidades:

- Logar com SIGAA via OAuth2
- Consumir API obtendo recursos em nome do usuário

## Quickstart

### Crie sua Aplicação no Bifrost

TBA.

Altere o arquivo `index.html` com o `client_id` da sua aplicação.

```
<a
      href="https://api.info.ufrn.br/authz-server/oauth/authorize?client_id=<<CLIENT_ID_DO_SEU_PROJETO>>&response_type=code&redirect_uri=http://127.0.0.1:5500/index.html"
    "
      >Clique aqui para acessar o SIGAA</a
    >
```

### Rodando o projeto

No VSCode, instale a extensão `Live Server` e clique em `Go Live` no arquivo `index.html`.

Abra o seu browser em `http://127.0.0.1:5500/index.html` e clique no link para acessar o SIGAA.
