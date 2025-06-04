# 🎬 Catálogo de Séries e Filmes - API REST  

Este repositório abriga o desenvolvimento de uma API RESTful para um sistema completo de catálogo de séries e filmes, focado em gerenciamento de conteúdos, usuários e avaliações. Construído com **Java + Spring Boot**, o projeto busca entregar uma solução robusta, segura e bem documentada.

---

## 🧠 Sobre o Projeto

O Catálogo de Séries e Filmes é parte do projeto final da disciplina de Desenvolvimento Backend. A proposta é entregar uma **API funcional e escalável**, com operações CRUD completas, segurança via autenticação e documentação automatizada.

Além disso, adotamos uma **arquitetura limpa**, separando as responsabilidades em camadas, e um banco de dados relacional com modelagem coerente e expansível.

---

## 🎯 Objetivos Técnicos

✅ Criar uma API RESTful seguindo boas práticas (HTTP status, verbos, rotas).  
✅ Implementar controle de usuários e sistema de avaliações.  
✅ Persistência de dados com PostgreSQL.  
✅ Possibilitar paginação, ordenação e filtros nas consultas.  
✅ Analisar e implementar segurança com JWT.  
✅ Documentar os endpoints via Swagger/OpenAPI.  

---

## 👨‍💻 Equipe de Desenvolvimento

| Nome | GitHub |
|------|--------|
| Nome 1 | [@usuario1](https://github.com/usuario1) | 
| Nome 2 | [@usuario2](https://github.com/usuario2) |
| Nome 3 | [@usuario3](https://github.com/usuario3) | 

---

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Java  
- **Framework:** Spring Boot  
- **ORM:** Spring Data JPA  
- **Banco de Dados:** PostgreSQL  
- **Segurança:** Spring Security + JWT  
- **Documentação:** 
- **Deploy:** 

---

## 🧱 Estrutura Inicial do Projeto

```
catalogo/
├── controllers/             # Endpoints e rotas
├── models/                  # Entidades JPA
├── repositories/            # Interfaces de acesso ao banco
├── services/                # Lógica de negócio
├── CatalogoApplication.java # Classe principal
└── resources/
    └── application.properties # Configurações do ambiente
```

---

## 🧩 Modelagem de Dados 

### 📁 Entidades:
- **Conteúdo:** Filmes e Séries  
- **Usuário:** Cadastro e autenticação  
- **Avaliação:** Comentários e notas

### 🔗 Relacionamentos:
- `Usuário` **1:N** `Avaliação`  
- `Conteúdo` **1:N** `Avaliação`


---

## 🚀 Funcionalidades Previstas

- [x] CRUD completo para conteúdos (filmes/séries)  
- [x] CRUD de usuários  
- [x] CRUD de avaliações  
- [ ] Autenticação JWT  
- [ ] Paginação e ordenação nas respostas  
- [ ] Documentação automatizada dos endpoints  

---

## ⚙️ Configuração Local

### 📂 Banco de Dados PostgreSQL

```sql
CREATE DATABASE catalogo;
```

### 🧾 application.properties

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/catalogo
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---
