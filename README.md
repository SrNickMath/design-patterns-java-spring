# design-patterns-java-spring

![Java](https://img.shields.io/badge/Java-22-orange)

![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.3.2-brightgreen)

## Descrição

O projeto `design-patterns-java-spring` é uma aplicação baseada em Spring Boot que demonstra a aplicação de padrões de design em um contexto Java. O objetivo principal é fornecer exemplos práticos de como aplicar padrões de design comuns, como o padrão Singleton, o padrão Strategy e o padrão Facade, utilizando o Spring Framework. O projeto inclui funcionalidades básicas de CRUD para gerenciamento de clientes e endereços, integrados com a API do ViaCEP para consulta de endereços.

## Funcionalidades

- **CRUD de Clientes**: Criação, leitura, atualização e exclusão de clientes.
- **Integração com ViaCEP**: Consulta de endereços utilizando a API do ViaCEP.
- **Validação de Dados**: Validação de dados de entrada usando anotações do Spring.
- **Tratamento de Exceções**: Tratamento centralizado de exceções usando `GlobalExceptionHandler`.

## Tecnologias Utilizadas

- **Java 22**
- **Spring Boot 3.3.2**
- **Spring Data JPA**
- **Spring Web**
- **Spring Cloud OpenFeign**
- **Springdoc OpenAPI**
- **H2 Database** (para testes)
- **Spring Boot Starter Validation** (para validação de dados)

## Configuração do Projeto

### Requisitos

- **Java 22**
- **Maven 3.x**