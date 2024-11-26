
# API LIXOJETO

Este repositório contém a implementação de uma API desenvolvida com **Node.js** e **PostgreSQL**. A API serve como backend para um aplicativo com o objetivo de conscientizar os cidadãos sobre o descarte correto do lixo e recompensá-los por meio de gamificação. O front-end está planejado para desenvolvimento futuro.

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/opedrogouveia/API_LIXOJETO.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd API_LIXOJETO
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```

## Configuração do Banco de Dados

A API utiliza o PostgreSQL. Para configurar:
1. Crie um banco de dados PostgreSQL.
2. Atualize as variáveis de ambiente no arquivo `.env`.

## Uso

Inicie o servidor com:
```bash
npm start
```

A API estará disponível em `http://localhost:3000`.

## Endpoints

- **GET** `/api/exemplo` - Retorna um exemplo de dados.
- **POST** `/api/exemplo` - Cria um novo exemplo.

## Contribuição

Contribuições são bem-vindas. Faça um fork, crie uma branch e envie um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
