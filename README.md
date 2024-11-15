Projeto Spring Boot

Este repositório é um portfólio que documenta minhas aprendizagens e práticas ao longo de um projeto de desenvolvimento com Spring Boot. O projeto inclui configurações de ambiente, scripts de banco de dados, e uma estrutura robusta para APIs RESTful.

## Sumário

1. [Configuração de Projeto com Spring Boot e Maven](#configuracao-de-projeto)
2. [Uso de Docker Compose para Ambiente de Desenvolvimento](#docker-compose)
3. [Scripts SQL e Estrutura de Banco de Dados](#scripts-sql)
4. [Estrutura de Camadas: Controller, Service, Repository](#camadas)
5. [Idempotência e Práticas com Verbos HTTP](#idempotencia)

---

### Configuração de Projeto com Spring Boot e Maven

Aprendi a estruturar e configurar um projeto Spring Boot utilizando o Maven, incluindo a personalização do arquivo `pom.xml` para gerenciar dependências e plugins. Com o Maven, o processo de build e gerenciamento de dependências torna-se mais eficiente e organizado.

### Uso de Docker Compose para Ambiente de Desenvolvimento

Para facilitar a criação de ambientes de desenvolvimento, utilizei o arquivo `docker-compose.yml`. Com ele, pude configurar rapidamente contêineres para o banco de dados e para o ambiente de execução do projeto, garantindo uma infraestrutura replicável e consistente.

### Scripts SQL e Estrutura de Banco de Dados

Trabalhei com scripts SQL (`create.sql`) para criar e popular o banco de dados do projeto. Com esses scripts, aprendi sobre a estrutura de tabelas, relações e como fazer o seeding inicial dos dados, o que facilita o desenvolvimento e testes da aplicação.

### Estrutura de Camadas: Controller, Service, Repository

A aplicação foi organizada em camadas, seguindo boas práticas de design para aplicações Spring:
- **Controller**: Responsável por gerenciar as requisições HTTP e retornar respostas adequadas.
- **Service**: Contém a lógica de negócios, separando as regras de negócio das camadas de controle e dados.
- **Repository**: Realiza a comunicação direta com o banco de dados.

### Idempotência e Práticas com Verbos HTTP

Ao desenvolver endpoints RESTful, aprendi a importância da idempotência, especialmente para os verbos HTTP como `POST`, `PUT`, `DELETE`, e `GET`. Implementei práticas para garantir que operações sejam seguras e consistentes, mesmo em casos de múltiplas requisições.

---

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/projeto-spring-api.git
   ```

2. Navegue até a pasta do projeto:
   ```bash
   cd projeto-spring-api
   ```

3. Compile o projeto:
   ```bash
   mvn clean install
   ```

4. Execute o projeto:
   ```bash
   mvn spring-boot:run
   ```

5. (Opcional) Execute via Docker:
   ```bash
   docker-compose up
   ```

---

Este portfólio reflete meu progresso e aprendizado no desenvolvimento de APIs com Spring Boot, integração com Docker, configuração de banco de dados com scripts SQL, e implementação de boas práticas com idempotência em operações RESTful.
```
