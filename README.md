# Sistema de Agendamentos para Barbearias

Este é um sistema de agendamentos desenvolvido para barbearias, com o objetivo de proporcionar uma experiência fluída tanto para os clientes quanto para os barbeiros. A plataforma permite agendar horários de forma simples e eficiente, com uma interface moderna e responsiva.

## Estrutura do Projeto

O projeto está dividido em duas partes principais:

- **Backend (API)**:  
  Desenvolvido com **Java** utilizando o framework **Spring Boot**. A persistência de dados é feita no banco de dados **PostgreSQL**, utilizando **JPA** com **Hibernate**. As migrações do banco de dados são gerenciadas pelo **Flyway**.

- **Frontend (UI)**:  
  Desenvolvido com **Angular** e **Angular Material**, oferecendo uma interface moderna, responsiva e intuitiva, garantindo uma excelente experiência para o usuário final.

## Tecnologias Utilizadas

- **Backend**:
  - Java
  - Spring Boot
  - PostgreSQL
  - JPA (Hibernate)
  - Flyway

- **Frontend**:
  - Angular
  - Angular Material
  - HTML5
  - CSS3

## Objetivos do Projeto

- Facilitar o agendamento de horários para clientes de barbearias.
- Oferecer uma interface intuitiva e fácil de usar tanto para clientes quanto para barbeiros.
- Garantir uma integração eficaz entre o frontend e o backend, com uma API robusta e escalável.
- Proporcionar uma experiência fluída e moderna através de uma interface responsiva.
- Melhorar a gestão dos horários de atendimento para os barbeiros, oferecendo controle sobre os agendamentos.

## Como Executar o Projeto

### 1. Executando o Backend

1. Clone este repositório:
   ```bash
   git clone https://github.com/AllysonAraujo/java-barber-shop.git
   ```
2. Acesse a pasta do backend:
   ```bash
   cd barber-shop-api
   ```
3. Configure o banco de dados no arquivo `application.properties`.

4. Execute a aplicação:
   ```bash
   ./gradlew bootRun
   ```

### 1. Executando o Frontend

1. Acesse a pasta do frontend:
   ```bash
   cd barber-shop-ui
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie o servidor de desenvolvimento:
   ```bash
   ng serve
   ```

A aplicação estará disponível em: `http://localhost:4200/`