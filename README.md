# Jornada de Aprendizado Backend: De Juninho a Júnior

## Índice

- [Jornada de Aprendizado Backend: De Juninho a Júnior](#jornada-de-aprendizado-backend-de-juninho-a-júnior)
  - [Índice](#índice)
  - [Descrição](#descrição)
  - [Estado Atual](#estado-atual)
  - [O Plano](#o-plano)
  - [Conhecimentos Adquiridos](#conhecimentos-adquiridos)
  - [Cronologia do Aprendizado](#cronologia-do-aprendizado)

---

## Descrição

Este repositório trata do meu ponto atual nos estudos de programação, documentando os conhecimentos que vou adquirindo pelo caminho, até passar de Trainee (ou Juninho, para os que sabem) para um Júnior consolidado e inserido no mercado de trabalho.

---

## Estado Atual

Se o nível de conhecimento "Hello World no terminal" até Júnior fosse uma escala de 0 a 10, eu diria que estou no 5 ou 6. Entretanto, a escala de dificuldade que essa segunda metade possui, atualmente, é muito maior do que a primeira.

Abordando os conhecimentos:

- Fundamentos em lógica e linguagem de programação (Intermediário)

- Git/Github (Básico/Intermediário)

- Framework Backend (Básico)

- SQL (Básico)

- Conceitos de API REST (Básico)

- Padrões e Arquitetura (Básico)

- Docker (Básico)

- Testes Unitários e de Integração (nada)

- CI/CD (nada)

- Microsserviços e Relacionados (nada)

- Cloud Computing (nada)

Percebeu algo? A maioria dos conhecimentos que eu deveria ter intermediário, estão como básico (Framework, SQL, API REST) e **todos** os que eu deveria ter uma noção básica, ainda não sei nada. A barreira de entrada do mercado dev hoje está cruel.

E é *por isso mesmo* que eu bolei um plano base de 2 anos (iniciando em 2026) ***realístico*** e alinhado com meus ***objetivos, ocupações atuais, possíveis distrações futuras e tópicos de estudo necessários***, sendo possível expandir para mais tempo caso necessário. É uma estratégia de ataque orientada a projetos práticos, onde na marra vou aplicar tudo que não sei ainda e melhorar o que já sei, do jeitinho que eu gosto.

---

## O Plano

| Trimestre                  | Mês    | Foco Principal                     | Projetos e Aplicação Prática                             | Tópicos de Estudo                                                                                                      |
| -------------------------- | ------ | ---------------------------------- | -------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Q1: Fundamentos            | Mês 1  | Base do Projeto                    | NerdOS                                                   | ---                                                                                                                    |
|                            | Mês 2  | Base do Projeto, Testes e Feedback | NerdOS                                                   | SQL Básico (CRUD, Agregações, Ordenações). SOLID (S).                                                                  |
|                            | Mês 3  | SQL Profundo                       | NerdOS                                                   | Testes Unitários (Jest) e Testes de Integração (Supertest). SOLID (S e D).                                             |
| Q2: Entrega e CI/CD        | Mês 4  | Deploy e Express                   | Fim do MVP do NerdOS + Início do Projeto em Trio         | PostgreSQL (Joins, Índices, Tipos de dados do Postgres e Views). Docker (Básico -> Intermediário).                     |
|                            | Mês 5  | Planejamento Profundo              | Flynances e Outros...                                    | Planejamento SDLC. Lógica de Programação, Estrutura de Dados e Algoritmos (Básico)                                     |
|                            | Mês 6  | Desenvolvimento para Eventos       | Flynances e Outros...                                    | Treinamento para Hackathons                                                                                            |
| Q3: Microsserviços (Local) | Mês 7  | Arquitetura Distribuída            | Início do StarPiece Microsserviços                       | Microsserviços (Conceitos). Modelagem de Dados para Microsserviços.                                                    |
|                            | Mês 8  | Messageria na Prática              | StarPiece (Auth + Notifications-Service)                 | Messageria (BullMQ/Redis). Padrões de Eventos. Comunicação Assíncrona.                                                 |
|                            | Mês 9  | Outros Módulos                     | StarPiece (Jams-Service, etc...)                         | Aplicação de Regras de Negócio                                                                                         |
| Q4: Microsserviços (Cloud) | Mês 10 | NoSQL                              | Faça Festa (Refatoração em NoSQL)                        | Micro Projeto Simples com MongoDB para aprendizado NoSQL                                                               |
|                            | Mês 11 | Deploy na Nuvem                    | StarPiece (Deploy de 3+ serviços)                        | Cloud (Nível 2 - Cloud Run/App Runner, Serviços Gerenciados).                                                          |
|                            | Mês 12 | Observabilidade                    | StarPiece (Refatorar Logs e Tracing)                     | Logging Estruturado (JSON). Métricas (OpenTelemetry).                                                                  |
| Q1: Polimento              | Mês 13 | Portfólio & Revisão                | StarPiece (Diagramas) e Outros Projetos                  | Documentação (READMEs e Diagramas). Refatoração do Portfólio (Design e Conteúdo).                                      |
|                            | Mês 14 | Preparação Técnica                 | Resolução de problemas                                   | Estrutura de Dados & Algoritmos (Intermediário).                                                                       |
|                            | Mês 15 | Entrevistas                        | Simulações                                               | System Design (Explicar a arquitetura StarPiece).                                                                      |
| Q2: Emprego e Cloud        | Mês 16 | Cloud Avançado                     | Escolha um serviço na Nuvem e aprofunde.                 | Cloud (Certificação: AWS Cloud Practitioner ou GCP Digital Leader).                                                    |
|                            | Mês 17 | Padrões de Arquitetura             | Refatorar uma parte do StarPiece.                        | Design Patterns (GoF), CQRS, Padrões do Backend.                                                                       |
|                            | Mês 18 | Networking/OS                      | Contribuições Open Source.                               | Introdução a Sistemas Operacionais (Threads, Processos).                                                               |
| Q3: Início do C#           | Mês 19 | Fundamentos C#                     | Projeto de Estudo Simples (C# CLI)                       | Sintaxe C#, Ecossistema .NET.                                                                                          |
|                            | Mês 20 | Primeira API .NET                  | Recriar um serviço do StarPiece (ex: jams-service) em C# | ASP.NET Core (Framework Web). Entity Framework Core (ORM).                                                             |
|                            | Mês 21 | Comparação                         | Fazer as APIs Node.js e C# se comunicarem                | Testes em C# (xUnit/NUnit). Entendimento da diferença entre Event Loop e Multi-threading.                              |
| Q4: Solidificação          | Mês 22 | Performance C#                     | Otimização da API C#                                     | Conceitos de Tasks (assincronicidade em C#), LINQ.                                                                     |
|                            | Mês 23 | Ecossistema .NET                   | Projeto C# completo                                      | Padrão MediatR (para CQRS em C#).                                                                                      |
|                            | Mês 24 | Planejamento de Carreira           | Revisão Geral                                            | Decisão de Foco (Node.js/TS ou C#/.NET). Preparação para vaga de Pleno (se já empregado) ou Júnior (se não empregado). |

Esse plano é apenas uma base de referência que pode se estender por mais tempo. Mesmo assim, deixo a mensagem para o Ivan do futuro: por favor, faça.

---

## Conhecimentos Adquiridos

Aqui será o índice para todos os arquivos localizados em [assuntos](./assuntos). Você também pode ver a minha experiência que adquiri nos meus [projetos](./projetos). Conforme eu for aprendendo, esses diretórios irão sendo populados.

- [Assuntos](./assuntos)
  
  - [Git e Github](./assuntos/git-e-github)
  
  - [Framework (NestJS)](./assuntos/framework)
  
  - [SQL](./assuntos/sql)
  
  - [NoSQL](./assuntos/nosql)
  
  - [Conceitos de API REST](./assuntos/api-rest)
  
  - [Padrões e Arquitetura](./assuntos/padroes-e-arquitetura)
  
  - [Containerização (Docker)](./assuntos/docker)
  
  - [Testes Unitários e de Integração](./assuntos/testes)
  
  - [CI/CD](./assuntos/ci-cd)
  
  - [Microsserviços](./assuntos/microsservicos)
  
  - [Computação em Nuvem](./assuntos/cloud)

- [Projetos Pessoais](./projetos)
  
  - [Tasksmith](./projetos/Tasksmith.md)
  
  - [AcompanheUmJuninho](./projetos/Acompanhe-Um-Juninho.md)
  
  - [NerdOS](./projetos/NerdOS.md)
  
  - [StarPiece](./projetos/StarPiece.md)

---

## Cronologia do Aprendizado

Esse vai ser o registro da evolução em tempo cronológico.
