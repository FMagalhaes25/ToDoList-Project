# ToDoList API

![Java 21](https://img.shields.io/badge/Java-21-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-4.0.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-1f6feb?style=for-the-badge)

Projeto de estudo em Java com Spring Boot para iniciar uma API de ToDo List.

## Tecnologias

- Java 21
- Spring Boot 4.0.5
- Spring Web MVC
- Spring Data JPA
- H2 Database (memória)
- Maven
- Lombok

## Pré-requisitos

- JDK 21 instalado
- Maven (opcional, o projeto já inclui Maven Wrapper)

## Como executar

### 1. Clonar o repositório

```bash
git clone https://github.com/FMagalhaes25/ToDoList-Project.git
cd ToDoList-Project
```

### 2. Rodar a aplicação

No Windows (cmd/PowerShell):

```bash
mvnw.cmd spring-boot:run
```

No Linux/macOS:

```bash
./mvnw spring-boot:run
```

A aplicação sobe por padrão em:

- http://localhost:8080

## Executar testes

```bash
mvnw.cmd test
```
