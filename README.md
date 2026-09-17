<div align="center">

<img src="https://github.com/raiFWnet.png?size=200" width="160" alt="FWNet">

# FWNet

### Tecnologia, desenvolvimento e soluções internas

Construindo soluções com foco em segurança, qualidade, manutenção e evolução controlada.

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

---

## Sobre

Este perfil concentra projetos e soluções desenvolvidos para apoiar a operação da **FWNet**.

O desenvolvimento segue uma abordagem incremental, com foco em arquitetura, segurança, testes, documentação e código manutenível.

---

## Projeto em destaque

### FWNet Time Tracking

Sistema proprietário para controle de jornada de trabalho dos analistas da FWNet.

O projeto é dividido em frontend e backend independentes, comunicando-se exclusivamente através de uma API REST.

### Backend

**fwnet-time-tracking-api**

API responsável por autenticação, autorização, regras de negócio, controle das marcações e persistência.

`Java 21` · `Spring Boot` · `Spring Security` · `JWT` · `Spring Data JPA` · `Flyway` · `PostgreSQL` · `Swagger / OpenAPI` · `JUnit 5` · `Mockito`

[![Backend](https://img.shields.io/badge/REPOSITÓRIO-BACKEND-181717?style=for-the-badge&logo=github)](https://github.com/raiFWnet/fwnet-time-tracking-api)

### Frontend

**fwnet-time-tracking-web**

Aplicação responsável pela interface, navegação, autenticação e integração com a API.

`Angular 22` · `TypeScript` · `Angular Router` · `Reactive Forms` · `HttpClient` · `Guards` · `Interceptors` · `Vitest`

[![Frontend](https://img.shields.io/badge/REPOSITÓRIO-FRONTEND-181717?style=for-the-badge&logo=github)](https://github.com/raiFWnet/fwnet-time-tracking-web)

---

## Arquitetura

```text
Angular
   │
   │ REST / JSON
   ▼
Spring Boot API
   │
   │ JPA / Hibernate
   ▼
PostgreSQL
```

---

## Tecnologias

| Área | Tecnologias |
|---|---|
| Backend | Java, Spring Boot, Spring Security, JWT, Spring Data JPA |
| Frontend | Angular, TypeScript, Reactive Forms, Guards, Interceptors |
| Banco | PostgreSQL, Flyway |
| Testes | JUnit 5, Mockito, Vitest |
| Documentação | Swagger / OpenAPI |
| Versionamento | Git, GitHub |

---

<div align="center">

### FWNet

**Tecnologia aplicada à operação.**

</div>
