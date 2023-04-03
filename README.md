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
Pré-requisitos: Java

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
# Busca de cidades
GET /cities

# Busca de cliente por id
GET /clients/1

# Inserção de nova cidade
POST /cities
{
  "name": "Recife"
}

# Deleção de cidades
DELETE /cities/5

# Atualização de evento
PUT /events/1
{
  "name": "Expo XP",
  "date": "2021-05-18",
  "url": "https://expoxp.com.br",
  "cityId": 7
}

```

# Autor

Cristhian Bitencourt

https://www.linkedin.com/in/cristhian-bitencourt-588b3317a/
