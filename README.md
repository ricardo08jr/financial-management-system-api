# Sistema de Gestão Financeira

## Sobre o projeto

Este projeto consiste no desenvolvimento de uma API de gestão financeira, voltada para o controle de contas, transações e geração de relatórios, simulando as principais funcionalidades de um mini banco.

O objetivo principal é aprofundar meus conhecimentos em desenvolvimento backend com Java, aplicando boas práticas de arquitetura, segurança, persistência de dados e organização de código.

---

## Objetivo técnico

O foco deste projeto está totalmente no backend e envolve principalmente:

- Modelagem de domínio
- Regras de negócio financeiras
- Autenticação e autorização com JWT
- Persistência de dados com ORM
- Estruturação de uma API REST escalável

---

## Decisão estratégica: uso de IA no frontend

Para otimizar o tempo de desenvolvimento e manter o foco total no backend, a interface inicial do sistema foi gerada com apoio de Inteligência Artificial.

Isso permitiu acelerar uma etapa que, se feita manualmente, consumiria bastante tempo.
[Acessar versão frontend do projeto](https://github.com/ricardo08jr/financial-management-system-frontend)

### Comparação de tempo
- Desenvolvimento manual do frontend: cerca de 1 semana
- Geração com IA: cerca de 1 minuto

### Ganho estimado de produtividade
A redução de tempo foi superior a 99% na criação do frontend inicial.

Com essa abordagem, foi possível direcionar quase todo o esforço para a construção de uma API mais robusta, organizada e bem estruturada.

---

## Funcionalidades

- Cadastro de contas
- Registro de transações de entrada e saída
- Categorização de transações
- Transferência entre contas
- Geração de relatórios financeiros:
  - Mensais
  - Por categoria
- Autenticação e autorização com JWT

---

## Tecnologias utilizadas

- Java
- Spring Boot
- Spring Security
- JPA / Hibernate
- PostgreSQL

---

## Evolução do projeto e arquitetura

Este projeto foi pensado para evoluir de forma incremental, seguindo uma lógica próxima da realidade de mercado: primeiro entregar valor, depois aprimorar a qualidade e, por fim, evoluir a arquitetura.

A evolução está organizada em branches, representando cada etapa de maturidade do sistema.

### Fase 1 — MVP (Minimum Viable Product)

Nesta etapa, o objetivo é entregar uma solução funcional o mais rápido possível.

Características desta fase:

- Separação básica em camadas
- Implementação direta das regras de negócio
- Menor complexidade arquitetural
- Foco total em funcionamento e entrega

---


## Conclusão
O Sistema de Gestão Financeira é um projeto desenvolvido com foco em aprendizado prático, organização e evolução contínua.
