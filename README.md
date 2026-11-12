# Termo API

API desenvolvida em **Java 21** com **Spring Boot 3** para um jogo de adivinhação de palavras estilo Termo, com suporte a integração com fontes externas.

## Tecnologias
- **Java 21**
- **Spring Boot 3.4** (Web, Data JPA, Validation)
- **H2 Database** (Em memória para desenvolvimento inicial)
- **Maven**

## Como executar
```bash
mvn spring-boot:run
```

- **API**: `http://localhost:8080`
- **Console H2**: `http://localhost:8080/h2-console` (JDBC URL: `jdbc:h2:mem:termodb`, User: `sa`, Password: *(vazio)*)
