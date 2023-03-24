# DsTest
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/cristhianbiten/dstest/blob/main/LICENSE) 

# Sobre o projeto


Projeto desenvolvido para o desafio do módulo de testes automatizados do Bootcamp Spring da DevSuperior.

O projeto foi desenvolvido utilizando TDD, onde recebemos os testes e criamos a aplicação, realizando todo o CRUD.

## Modelo conceitual
![Modelo Conceitual](https://github.com/cristhianbiten/assets/blob/main/dstest.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- H2
- JUnit
- Mockito
- MockBean

# Como executar o projeto

## Back end
Pré-requisitos: Java 17

[Tutorial de instalação Java](https://www.youtube.com/watch?v=QekeJBShCy4)

```bash
# Clonar repositório
git clone https://github.com/cristhianbiten/dstest.git

# Entrar na pasta do projeto back end
cd dstest

# Executar o projeto
./mvnw spring-boot:run
```

## Testes manuais
Pré-requisitos: Postman

Collection do Postman
https://www.getpostman.com/collections/c347ea3428d6b199b391

```bash
# Busca paginada de clientes
GET /clients?page=0&linesPerPage=6&direction=ASC&orderBy=name

# Busca de cliente por id
GET /clients/1

# Inserção de novo cliente
POST /clients
{
  "name": "Maria Silva",
  "cpf": "12345678901",
  "income": 6500.0,
  "birthDate": "1994-07-20T10:30:00Z",
  "children": 2
}

# Atualização de cliente
PUT /clients/1
{
  "name": "Maria Silvaaa",
  "cpf": "12345678901",
  "income": 6500.0,
  "birthDate": "1994-07-20T10:30:00Z",
  "children": 2
}

# Deleção de cliente
DELETE /clients/1
```

# Autor

Cristhian Bitencourt

https://www.linkedin.com/in/cristhian-bitencourt-588b3317a/
