# Projeto DAO JDBC com MySQL

Projeto desenvolvido durante o curso **Java COMPLETO: Programação Orientada a Objetos + Projetos**, ministrado pelo instrutor **Nelio Alves** na Udemy.

A aplicação foi construída utilizando **Java**, **JDBC**, **Maven** e **MySQL**, tendo como objetivo demonstrar a implementação do padrão **DAO (Data Access Object)** para o acesso e manipulação de dados em banco de dados relacionais.

A conexão com o banco é gerenciada por meio do **Maven**, utilizando o driver JDBC do MySQL. As credenciais de acesso são configuradas no arquivo `db.properties`, enquanto a classe `DB.java` é responsável por estabelecer e gerenciar a conexão da aplicação com o banco de dados.

O projeto possui duas interfaces DAO, responsáveis por definir operações específicas de **inserção**, **atualização**, **consulta** e **remoção** de dados para as entidades do sistema:

* `Seller` (Vendedor);
* `Department` (Departamento).

As implementações dessas interfaces seguem boas práticas de programação, promovendo **baixo acoplamento**, **facilidade de manutenção** e **maior organização do código**.

Para validação das funcionalidades desenvolvidas, foram criadas duas classes principais:

* `Main.java`: realiza testes das operações relacionadas à entidade **Seller**;
* `Main2.java`: realiza testes das operações relacionadas à entidade **Department**.

Este projeto teve como principal objetivo consolidar os conhecimentos sobre **JDBC**, **persistência de dados**, **MySQL** e a aplicação do padrão **DAO** em aplicações Java.

## Tecnologias Utilizadas

- Java
- JDBC
- Maven
- MySQL
- Padrão DAO

## Conceitos Aplicados

- Programação Orientada a Objetos (POO)
- Separação de responsabilidades
- Persistência de dados
- CRUD
- Boas práticas de manutenção e organização de código
