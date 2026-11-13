# Hi, I'm Luiz Guerra 👋

**Backend Developer (Java) · APIs & SQL · Porto Alegre, Brazil**

<details>
<summary><strong>🇧🇷 Versão em português</strong></summary>

<br>

# Olá, eu sou o Luiz Guerra 👋

**Desenvolvedor Backend (Java) · APIs e SQL · Porto Alegre, Brasil**

Estou em transição para o desenvolvimento de software depois de mais de 4 anos em sistemas corporativos de alta disponibilidade: servidores Linux, bancos relacionais de ERPs críticos e análise de causa raiz de incidentes em produção. Essa bagagem define como eu desenvolvo backends: confiáveis, fáceis de depurar e pensados para o que acontece quando algo falha em produção.

---

### 🛠️ Stack

- **Linguagens:** Java (foco principal), TypeScript (NestJS)
- **APIs:** REST, JSON, OpenAPI/Swagger
- **Bancos de dados:** PostgreSQL, MySQL, SQL (consultas complexas, modelagem de dados)
- **Conceitos de backend:** DDD, Clean Architecture, idempotência, transactional outbox, controle de concorrência
- **Ferramentas:** Git, GitHub, Docker, Linux

---

### 🚀 Projetos

#### [`backend-challange`](https://github.com/luizguerradev/backend-challange) — Microserviço de Carteira e Apostas
*TypeScript (NestJS, Bun) · PostgreSQL · Docker*

Minha solução para um desafio técnico de backend: carteiras digitais e transações de apostas em cenário de iGaming, com gestão de carteiras, extrato contábil (ledger) e transações (`BET`, `WIN`, `LOSS`, `REFUND`, `ROLLBACK`).

- **DDD e Clean Architecture**, com regras de negócio isoladas do framework e do ORM
- **Lock pessimista** (`SELECT FOR UPDATE`) contra condições de corrida e saldo negativo
- **`Idempotency-Key`** para evitar processamento duplicado
- **Transactional outbox** para eventos assíncronos confiáveis (SQS via LocalStack)
- **Ledger imutável** garantido por triggers no banco, mais reconciliação de carteira
- **Documentação Swagger/OpenAPI**, testes unitários e e2e

---

### 🎓 Formação

- **Análise e Desenvolvimento de Sistemas** — Uniftec *(conclusão prevista: julho de 2027)*

---

### 📫 Contato

- **LinkedIn:** [linkedin.com/in/luiz-guerra](https://www.linkedin.com/in/luiz-guerra)
- **E-mail:** [luizhc.guerra@gmail.com](mailto:luizhc.guerra@gmail.com)

</details>


I'm moving into software development after 4+ years working with high-availability corporate systems: Linux servers, relational databases behind critical ERPs, and root-cause analysis of production incidents. That background shapes how I build backends: reliable, easy to debug, and aware of what happens when things break in production.

---

### 🛠️ Tech Stack

- **Languages:** Java (main focus), TypeScript (NestJS)
- **APIs:** REST, JSON, OpenAPI/Swagger
- **Databases:** PostgreSQL, MySQL, SQL (complex queries, data modeling)
- **Backend concepts:** DDD, Clean Architecture, idempotency, transactional outbox, concurrency control
- **Tools:** Git, GitHub, Docker, Linux

---

### 🚀 Projects

#### [`backend-challange`](https://github.com/luizguerradev/backend-challange) — Wagering & Wallet Microservice
*TypeScript (NestJS, Bun) · PostgreSQL · Docker*

My solution to a backend technical challenge: digital wallets and bet transactions in an iGaming scenario, with wallet management, an accounting ledger, and transactions (`BET`, `WIN`, `LOSS`, `REFUND`, `ROLLBACK`).

- **Domain-Driven Design & Clean Architecture**, with business rules isolated from the framework and ORM
- **Pessimistic locking** (`SELECT FOR UPDATE`) to prevent race conditions and negative balances
- **`Idempotency-Key` handling** to avoid duplicate processing
- **Transactional outbox** for reliable async events (SQS via LocalStack)
- **Immutable ledger** enforced by database triggers, plus wallet reconciliation
- **Swagger/OpenAPI docs**, unit and e2e tests

---

### 🎓 Education

- **Associate's degree in Systems Analysis and Development** — Uniftec *(expected graduation: July 2027)*

---

### 📫 Let's Connect

- **LinkedIn:** [linkedin.com/in/luiz-guerra](https://www.linkedin.com/in/luiz-guerra)
- **Email:** [luizguerra.dev@gmail.com](mailto:luizguerra.dev@gmail.com)

---

