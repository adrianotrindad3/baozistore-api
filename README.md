# 🥟 Baozi Store - API REST

API REST desenvolvida em **Java** com **Spring Boot** para o gerenciamento de clientes, produtos e pedidos da loja fictícia **Baozi Store**.

---

## 👨‍💻 Desenvolvedor
* **Nome:** Adriano José Trindade Silva
* **RU:** 5086095
* **Instituição:** Centro Universitário Internacional UNINTER

---

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Java
* **Framework:** Spring Boot (Spring Web, Spring Data JPA)
* **Banco de Dados:** H2 Database / PostgreSQL
* **Ferramenta de Testes:** Postman

---

## 📌 Funcionalidades e Endpoints

### 👤 Clientes (`/clientes`)
* `POST /clientes` - Cadastra um novo cliente.
* `GET /clientes` - Lista todos os clientes cadastrados.
* `GET /clientes/{id}` - Busca cliente por ID.
* `DELETE /clientes/{id}` - Remove cliente por ID.

### 📦 Produtos (`/produtos`)
* `POST /produtos` - Cadastra um novo produto.
* `GET /produtos` - Lista todos os produtos.
* `GET /produtos/{id}` - Busca produto por ID.
* `DELETE /produtos/{id}` - Remove produto por ID.

### 🛒 Pedidos (`/pedidos`)
* `POST /pedidos` - Registra um novo pedido.
* `GET /pedidos` - Lista todos os pedidos.
* `GET /pedidos/{id}` - Busca pedido por ID.
* `DELETE /pedidos/{id}` - Remove/cancela pedido por ID.

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone [https://github.com/adrianotrindad3/baozistore-api.git](https://github.com/adrianotrindad3/baozistore-api.git)