# Literalura 📚

Projeto para busca, listagem e análise estatística de livros e autores usando a API Gutendex.

## 🚀 Tecnologias

Este projeto utiliza as seguintes tecnologias:
- **Java** 🟦
- **Spring Boot** 🌱
- **JPA/Hibernate** 🗄️
- **API Gutendex** 🌍

## 📖 Funcionalidades

- Buscar livro pelo título via API Gutendex
- Listar livros e autores cadastrados no banco de dados
- Filtrar autores por ano de nascimento/morte
- Buscar livros por idioma
- Obter estatísticas sobre livros e autores
- Top 10 livros mais baixados

## 🛠️ Como executar

1. 📥 Clone o repositório
   ```bash
   (https://github.com/Daiana-Rocha/literalura-Daiana.git)
   cd literalura
   mvn spring-boot:run
   ```
2. ⚙️ Configure o banco de dados no `application.properties`
   ```properties
   spring.application.name=literalura
   spring.datasource.url=jdbc:postgresql://${DB_HOST}/literalura
   spring.datasource.username=${DB_USER}
   spring.datasource.password=${DB_PASSWORD}
   spring.datasource.driver-class-name=org.postgresql.Driver
   hibernate.dialect=org.hibernate.dialect.HSQLDialect
   spring.jpa.hibernate.ddl-auto=update
   ```

