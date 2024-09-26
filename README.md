# Mini Sistema de Gestão de Produtos

Este projeto foi desenvolvido como parte da disciplina de Programação para Internet, com o objetivo de criar um sistema de CRUD (Create, Read, Update, Delete) para gerenciamento de produtos e fornecedores. O sistema inclui funcionalidades como cadastro de usuários, criptografia de senhas, autenticação e uma interface para criação e gerenciamento de uma cesta de compras.

## Funcionalidades

- **Criação do Banco de Dados**: O sistema se conecta ao banco de dados `gerenciadordb` para gerar as tabelas automaticamente. Recomenda-se o uso do phpMyAdmin para a configuração inicial do banco de dados.

- **Cadastro de Usuários**: Permite a criação de novos usuários. Após o cadastro, o usuário pode acessar a tela de login para entrar no sistema e acessar o painel principal.

- **Cadastro de Fornecedores**: Permite o registro de fornecedores com todas as informações necessárias para o cadastro de produtos.

- **Cadastro de Produtos**: Inclui o registro de produtos com detalhes como nome, descrição, valor, quantidade e fornecedor associado.

- **Criação de Cesta de Compras**: Os produtos podem ser adicionados a uma cesta de compras através de uma interface com checkbox, permitindo ao cliente selecionar os itens que deseja comprar.

- **Atualização Dinâmica da Cesta**: A cesta de compras é atualizada dinamicamente usando AJAX, evitando o recarregamento da página e proporcionando uma experiência mais fluida ao usuário.

## Tecnologias Utilizadas

- **Backend**: PHP
- **Banco de Dados**: MySQL
- **Frontend**: HTML
- **CSS**: Bootstrap
- **JavaScript (AJAX)**: