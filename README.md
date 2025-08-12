# 🎮 Loja de Games - Projeto Generation Brasil

Este projeto é uma aplicação backend desenvolvida em **Java** como parte da formação da **Generation Brasil**. Ele simula o funcionamento de uma loja de games, com funcionalidades típicas de um sistema de e-commerce.

> Este repositório é um fork do projeto original [`games_store_GEN`](https://github.com/projetogen/games_store_GEN).

## Tecnologias utilizadas

- Java 11
- Spring Boot
- Spring Data JPA
- MySQL
- Maven

## Estrutura do projeto

- `model/`: classes que representam as entidades (Produto, Categoria, etc.)
- `repository/`: interfaces para acesso ao banco de dados
- `controller/`: endpoints REST para manipulação dos dados
- `configuration/`: configurações de segurança e CORS
- `application.properties`: configurações da aplicação

## Funcionalidades

- Cadastro de produtos e categorias
- Atualização e exclusão de registros
- Filtros e buscas por nome ou faixa de preço
- Integração com banco de dados relacional
- Estrutura RESTful com boas práticas

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/mariana-nogueira21/lojaDeGames.git
