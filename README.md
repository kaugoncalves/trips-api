# Planner

## Descrição

Projeto de demonstração para Spring Boot.

## Requisitos

- Java 21
- Maven 3.6.3 ou superior

## Tecnologias Utilizadas

- Spring Boot 3.3.1
- Spring Data JPA
- Spring Web
- Flyway
- H2 Database
- Lombok
- Spring Boot DevTools


## Endpoints
A aplicação expõe alguns endpoints RESTful. Aqui estão alguns exemplos:

GET /trips: Lista todas as viagens.
POST /trips: Cria uma nova viagem.
GET /trips/{id}: Busca uma viagem pelo ID.
PUT /trips/{id}: Atualiza uma viagem existente.
GET /trips/{id}/confirm: Confirma uma viagem pelo ID e envia um e-mail de confirmação para os participantes.
POST /trips/{id}/invite: Convida um participante para uma viagem e envia um e-mail de confirmação se a viagem já estiver confirmada.
GET /trips/{id}/participants: Lista todos os participantes de uma viagem.
POST /trips/{id}/activities: Registra uma nova atividade para uma viagem.
GET /trips/{id}/activities: Lista todas as atividades de uma viagem.
POST /trips/{id}/links: Registra um novo link para uma viagem.
GET /trips/{id}/links: Lista todos os links de uma viagem.

## Configuração do Projeto

### Clonando o Repositório

```bash
git clone https://github.com/seu-usuario/planner.git
cd planner
