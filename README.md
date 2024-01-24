# Projeto web services com Spring Boot e JPA / Hibernate
[![Static Badge](https://img.shields.io/badge/LICENCE-MIT-blue)](https://github.com/wagneralm/workshop-springboot-jpa/blob/main/LICENSE)
## Sobre o projeto
O objetivo é desenvolver uma aplicação Spring Boot Java, seguindo as diretrizes de qualidade e boas práticas de desenvolvimento, com ênfase na estrutura eficiente do código e tratamento sólido de exceções. O curso, ministrado pelo professor Nelio Alves da [DevSuperior](https://devsuperior.com.br/ "Site da DevSuperior"), foi fundamental para incorporar esses princípios. O projeto visa não apenas atender aos requisitos de CRUD e ao uso do banco de dados H2 para testes, mas também destaca-se pela clareza do código, facilitando a manutenção e promovendo uma experiência de aprendizado enriquecedora.

## Modelo conceitual
![Modelo conceitual](https://github.com/wagneralm/workshop-springboot-jpa/blob/main/assets/domain_model.png)

## Tecnologias utilizadas
### Back end:
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- H2

### Implantação em produção:
- Insomnia

## Como executar o projeto
Pré-requisitos: Java 11
### Clonando o projeto:
```bash
# comandos bash
# clonar repositorio
git clone https://github.com/wagneralm/workshop-springboot-jpa
# entrar na pasta do projeto
cd course

# executar o projeto
./mvnw spring-boot:run
```
```cmd
:: comandos cmd
:: clonar repositorio
git clone https://github.com/wagneralm/workshop-springboot-jpa

:: entrar na pasta do projeto
cd course

:: executar o projeto
mvnw spring-boot:run
```
## Requisições HTTP - Insomnia/PostMan

```http
GET
  localhost:8080/users
  localhost:8080/users/{id}
  localhost:8080/oders
  localhost:8080/oders/{id}
  localhost:8080/products
  localhost:8080/products/{id}
  localhost:8080/categories
  localhost:8080/categories/{id}
POST
  localhost:8080/users
PUT
  localhost:8080/users/{id}
DELETE
  localhost:8080/users/{id}
```

# Autor

Wagner de Almeida

[LinkedIn](https://www.linkedin.com/in/wagner-alm-dev)


