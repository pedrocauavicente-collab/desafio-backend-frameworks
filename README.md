# Desafio Backend Frameworks

## Objetivo

Este repositório foi desenvolvido com o objetivo de demonstrar conhecimentos práticos em desenvolvimento back-end, utilizando dois frameworks amplamente adotados no mercado: Node.js com Express e Java com Spring Boot. Ambos os projetos seguem a arquitetura em camadas, baseada no padrão MVC (Model-View-Controller).

---

## Tecnologias Utilizadas

### Node.js + Express
- Node.js
- Express
- JavaScript
- npm

### Java + Spring Boot
- Java
- Spring Boot
- Maven
- Spring Web

---

## Estrutura do Repositório

bash desafio-backend-frameworks/ ├── java-springboot/ └── node-express/ 

---

## Projeto Node.js com Express

O projeto desenvolvido em Node.js utiliza o framework Express e segue a arquitetura MVC.

### Estrutura

bash node-express/ ├── controllers/ │   └── UserController.js ├── models/ │   └── UserModel.js ├── routes/ │   └── userRoutes.js ├── index.js └── package.json 

### Camadas

- Models: Responsáveis pela estrutura e manipulação dos dados.
- Controllers: Processam as requisições e retornam as respostas.
- Routes: Definem os endpoints da aplicação.
- index.js: Arquivo principal responsável pela inicialização do servidor.

---

## Projeto Java com Spring Boot

O projeto desenvolvido em Java utiliza o framework Spring Boot e também segue a arquitetura em camadas.

### Estrutura

bash java-springboot/ ├── controllers/ ├── dtos/ ├── models/ ├── repositories/ └── services/ 

### Camadas

- Controllers: Recebem as requisições HTTP.
- Services: Contêm as regras de negócio.
- Repositories: Responsáveis pela comunicação com o banco de dados.
- Models: Representam as entidades da aplicação.
- DTOs: Utilizados para transferência de dados entre camadas.

---

## Comparação entre Frameworks

### Node.js + Express

- Inicialização rápida e simples.
- Código menos verboso.
- Gerenciamento de dependências realizado com npm.
- Excelente para APIs leves e aplicações em tempo real.

### Java + Spring Boot

- Estrutura robusta e altamente escalável.
- Forte tipagem e maior segurança em tempo de compilação.
- Gerenciamento de dependências realizado com Maven.
- Amplamente utilizado em sistemas corporativos.

---

##Arquitetura em Camadas

Ambos os projetos seguem o padrão MVC, promovendo organização, reutilização de código e facilidade de manutenção.

### Fluxo de Comunicação

1. O cliente realiza uma requisição HTTP.
2. A rota (ou controller) recebe a solicitação.
3. O controller processa a requisição.
4. O model ou service executa a lógica necessária.
5. A resposta é retornada ao cliente.

---

## Conclusão

O Node.js com Express destaca-se pela simplicidade, rapidez e flexibilidade no desenvolvimento de APIs. Já o Spring Boot oferece uma estrutura mais robusta, escalável e adequada para aplicações empresariais de grande porte.

A implementação de ambos os projetos permitiu compreender as diferenças entre as tecnologias e reforçar a importância da arquitetura em camadas no desenvolvimento back-end moderno.
