# abc-comunidade-database
# Sistema de Banco de Dados da ABC Comunidade

Este repositório contém o código-fonte do sistema de banco de dados desenvolvido para a "ABC Comunidade".

## Estrutura do Repositório

- `schema.sql`: Script SQL para criação das tabelas do banco de dados.
- `data.sql`: Script SQL para inserção de dados iniciais.
- `functions.sql`: Script SQL para criação de funções e procedimentos armazenados.
- `backup.sql`: Script SQL para backup do banco de dados.
- `README.md`: Este arquivo com instruções de uso.

## Requisitos

- MySQL 8.0 ou superior
- Git

## Instalação

1. Clone o repositório para o seu computador:

    ```bash
    git clone https://github.com/seu-usuario/abc-comunidade-database.git
    cd abc-comunidade-database
    ```

2. Crie um banco de dados no MySQL:

    ```sql
    CREATE DATABASE abc_comunidade;
    ```

3. Execute o script de criação de tabelas:

    ```bash
    mysql -u seu-usuario -p abc_comunidade < schema.sql
    ```

4. Execute o script de inserção de dados:

    ```bash
    mysql -u seu-usuario -p abc_comunidade < data.sql
    ```

5. Execute o script de funções e procedimentos:

    ```bash
    mysql -u seu-usuario -p abc_comunidade < functions.sql
    ```

6. Para restaurar o backup do banco de dados:

    ```bash
    mysql -u seu-usuario -p abc_comunidade < backup.sql
    ```

## Uso

Após a instalação, você pode acessar o banco de dados `abc_comunidade` no MySQL e utilizar as tabelas, funções e procedimentos conforme necessário.

## Contribuição

Se você deseja contribuir com este projeto, por favor, faça um fork do repositório, crie uma branch para suas alterações e envie um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
