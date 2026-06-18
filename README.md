# Produtos API REST

API REST desenvolvida com Java e Spring Boot para gerenciamento de produtos, permitindo operações completas de cadastro, consulta, atualização e remoção de registros.

Este projeto foi criado com o objetivo de consolidar conhecimentos em desenvolvimento backend utilizando boas práticas de mercado, arquitetura em camadas e conceitos de APIs RESTful.

## Tecnologias Utilizadas

* Java 17
* Spring Boot
* Spring Data JPA
* Hibernate
* PostgreSQL
* Maven
* Jakarta Validation
* HATEOAS
* REST API

## Funcionalidades

* Cadastro de produtos
* Consulta de todos os produtos
* Consulta de produto por ID
* Atualização de produtos
* Exclusão de produtos
* Validação de dados de entrada
* Persistência de dados com JPA/Hibernate
* Navegação HATEOAS para recursos relacionados

## Arquitetura

O projeto segue uma estrutura organizada em camadas:

* Controller: Responsável pelos endpoints da API.
* DTO: Transferência e validação dos dados.
* Model: Entidades persistidas no banco de dados.
* Repository: Comunicação com o banco utilizando Spring Data JPA.

## Endpoints

| Método | Endpoint       | Descrição             |
| ------ | -------------- | --------------------- |
| POST   | /products      | Cadastrar produto     |
| GET    | /products      | Listar produtos       |
| GET    | /products/{id} | Buscar produto por ID |
| PUT    | /products/{id} | Atualizar produto     |
| DELETE | /products/{id} | Excluir produto       |

## Objetivo do Projeto

Este projeto faz parte da minha jornada de transição da área de Suporte para Desenvolvimento de Software. O objetivo foi praticar conceitos amplamente utilizados em aplicações corporativas, como APIs REST, persistência de dados, validação, arquitetura em camadas e boas práticas de desenvolvimento utilizando o ecossistema Spring.

## Próximas Evoluções

* Testes unitários com JUnit e Mockito
* Documentação com Swagger/OpenAPI
* Autenticação e autorização com Spring Security e JWT
* Dockerização da aplicação
* Pipeline CI/CD

## Autor

Vitor Galetti

Engenheiro de Software formado pela Unicesumar, atuando profissionalmente na área de tecnologia e desenvolvendo projetos para aprimorar conhecimentos em backend com Java e Spring Boot.
