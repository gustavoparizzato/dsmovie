# Listagem de Filmes

Este é um projeto de avaliação de filmes que utiliza Java no Spring Boot no backend, JavaScript com React no frontend e um banco de dados PostgreSQL. Ele permite aos usuários visulizar a listagem de filmes (contém imagem, nome e a média das notas), clicar sobre os mesmos e atribuir notas a eles, o que faz ser recalculado a média de classificação instantâneamente e exibindo aos usuários.
OBS: Cada E-mail pode avaliar somente 1 única vez cada filme.

Projeto realizado juntamente ao evento realizado pela @devsuperior

### Tecnologias Utilizadas

- Java 17 com Spring Boot
- Hibernate
- Maven
- JPA

- JavaScript com React
- Bootstrap
- Yarn
- Axios

## Banco de dados

Este projeto utiliza o banco de dados PostgreSQL para armazenar e gerenciar os dados da aplicação. O PostgreSQL é um sistema de gerenciamento de banco de dados relacional de código aberto amplamente utilizado.

### Funcionalidades

O projeto oferece as seguintes funcionalidades:

- Listagem de filme com a exibição de sua imagem, nome e a média de notas.
- Permissão para clicar sobre o filme e abrir uma nova guia.
- Permissão para preencher um e-mail válido e atribuir uma nota ao filme.

### Arquitetura 

Este projeto foi desenvolvido seguindo o padrão de arquitetura Model-View-Controller (MVC) para criar a API RESTful.
O padrão MVC foi escolhido para garantir uma separação clara de preocupações, tornando o projeto mais organizado e escalável.
