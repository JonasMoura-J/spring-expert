# 🚀 Projeto Spring Boot Expert

---

## 📚 Sobre o Projeto

A aplicação demonstra a construção de APIs modernas utilizando o ecossistema Spring, seguindo boas práticas de arquitetura, segurança, testes e deploy.

Este projeto cobre todo o ciclo de desenvolvimento:

- Modelagem
- Implementação
- Segurança
- Testes
- Documentação
- Deploy em Cloud

---

## 🧠 O que você vai encontrar aqui

### 🔹 Fundamentos
- Java básico e Orientação a Objetos
- Estrutura de projetos com Spring Boot

### 🔹 Spring Framework e Ecossistema
- Funcionamento interno do Spring
- Injeção de dependência
- Configuração e modularização

### 🔹 Persistência de Dados
- Spring Data JPA
- JpaRepository
- Query Methods
- Specifications
- Query By Example

### 🔹 APIs RESTful
- Construção de APIs seguindo boas práticas
- Uso correto de HTTP (status codes, verbs)
- DTOs para transporte de dados
- Mapeamento com MapStruct
- Tratamento global de exceções (Exception Handler)

### 🔹 Design de APIs
- Modelagem de contratos REST
- Boas práticas de versionamento
- Padronização de respostas

### 🔐 Segurança
- Spring Security
- Autenticação:
    - Basic Auth
    - Form Login
- Controle de acesso por permissões

### 🔑 Autenticação Avançada
- Login Social (Google)
- OAuth2
- Criação de Authorization Server

### 🔐 Keycloak
- Integração com Keycloak
- Gerenciamento de autenticação externa

### 🐳 Docker
- Containerização da aplicação
- Subida de banco de dados com Docker

### ☁️ AWS (Cloud)
- Deploy em instância EC2
- Banco de dados com RDS

### 📄 Documentação de API
- Swagger / OpenAPI
- Customização de endpoints protegidos

### 🧪 Testes
- Testes unitários
- Testes de integração

### 📬 Ferramentas
- Uso do Postman para testes de API

---

## 🛠️ Tecnologias Utilizadas

- Java 25
- Spring Boot
- Spring Data JPA
- Spring Security
- OAuth2
- Keycloak
- Docker
- AWS (EC2, RDS)
- Swagger / OpenAPI
- MapStruct
- JUnit / Testes

---

## ▶️ Como Executar o Projeto

### Pré-requisitos

- Java instalado
- Docker (opcional, mas recomendado)
- Maven ou Gradle

### Passos

```bash
# Clonar o repositório
git clone <url-do-repositorio>

# Acessar a pasta
cd nome-do-projeto

# Rodar a aplicação
./mvnw spring-boot:run