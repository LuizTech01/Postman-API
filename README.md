# Projeto Serverest - Testes de API com Postman

Este projeto contém uma coleção de requisições para a API do Serverest, criadas e testadas no Postman. A API Serverest é utilizada para simular operações em um ambiente de e-commerce.


## Funcionalidades
- **Carrinho**:
  - Listar todos os carrinhos.
  - Consultar carrinho por ID.
  - Criar, atualizar e excluir carrinhos.
- **Produtos**:
  - Listar todos os produtos.
  - Consultar produto por ID.
  - Criar, atualizar e excluir produtos.
- **Usuários**:
  - Listar todos os usuários.
  - Consultar usuário por ID.
  - Criar, atualizar e excluir usuários.
- **Login**:
  - Autenticação para acessar endpoints protegidos.


## Como usar este projeto

### Pré-requisitos
- Postman instalado ([Download aqui](https://www.postman.com/downloads/)).
- Acesso à API Serverest ([Documentação oficial](https://serverest.dev)).

### Passos para Importar a Coleção
1. Faça o download do arquivo JSON desta coleção no repositório.
2. No Postman, clique em **"Import"**.
3. Selecione o arquivo JSON da coleção.
4. Importe também o arquivo de variáveis de ambiente (se houver).

### Configuração de Variáveis de Ambiente
Adicione as variáveis de ambiente necessárias:
- `baseUrl`: URL base da API (exemplo: `https://serverest.dev`).
- `authToken`: Token de autenticação (obtido após login).

### Exemplos de Uso
- **GET** `/produtos`:
  - Retorna todos os produtos cadastrados.
- **POST** `/produtos`:
  - Cria um novo produto (necessário token de autenticação).
- **GET** `/produtos/{id}`:
  - Retorna informações de um produto específico com base no ID.
- **PUT** `/produtos/{id}`:
  - Edita um produto especifico com base no ID informado.
- **DELETE** `/produtos/{id}`:
  - Delete um produto especifico com base no ID informado.

## Tecnologias Utilizadas

- [Postman](https://www.postman.com/) para criação e teste de requisições.
- API [Serverest](https://serverest.dev) para simular operações.
