### Hi, I'm Armando 👋

**Tech Lead and backend engineer** in Mexico City. I build the systems where money moves (card authorization, payment processing, financial cryptography) with **Java and Spring Boot**.

- 💳 **Now:** I lead the transactional core of a credit card processing platform for a Mexican bank: ISO 8583 online authorization with EMV cryptogram validation (ARQC/ARPC), duplicate control and idempotent retries under concurrency, and a full-portfolio migration (customers, accounts, cards, transaction history) completed in a 24-hour window with reconciliation against the source system.
- 🔐 **Before that:** I led an online PIN encryption system (ISO 9564) for a major Mexican bank, covering the key lifecycle under DUKPT and TR-31 with HSM integration in real time.
- 🩺 **On my own:** I built [Curo](https://github.com/armando-calz/curo) end to end. It reached production at a medical practice in two weeks and runs there daily.
- 🎯 **Interested in:** fintech, payments and crypto exchange infrastructure.

#### Featured work

| Project | What it shows |
|---|---|
| [**iso8583-authorizer**](https://github.com/armando-calz/iso8583-authorizer) | Card authorization host speaking ISO 8583 over TCP: hand-written codec, virtual-thread server, issuer rules with standard response codes, credit holds under row locks, tokenized PANs, duplicate retransmissions, reversals released exactly once and EMV ARQC/ARPC verification. Runs end to end with `docker compose` and a self-checking terminal demo. |
| [**ledger-core**](https://github.com/armando-calz/ledger-core) | Double-entry ledger in Java 21 / Spring Boot 4 / PostgreSQL. Exact money arithmetic, overdraft protection under ordered row locks (with a test that reproduces double spending without them), idempotent transfers and design decisions recorded as ADRs. |
| [**curo**](https://github.com/armando-calz/curo) | Offline desktop app (Electron, React, TypeScript, SQLite) for patient records, with consistent backups, an activity log with undo and HMAC-based offline licensing. In production, with a downloadable demo. |

#### Toolbox

- **Backend:** Java · Spring Boot · Hibernate/JPA · REST APIs · Maven
- **Data:** PostgreSQL · SQL Server · Oracle · Redis
- **Payments domain:** ISO 8583 · EMV (ARQC/ARPC) · ISO 9564 PIN blocks · DUKPT · TR-31 · HSM
- **Architecture:** clean / hexagonal architecture · DDD · microservices · system design
- **Ops:** Docker · Podman · GitHub Actions · Testcontainers · Actuator / Micrometer
- **Also:** TypeScript · Go (learning)

#### About

B.S. in Computer Systems Engineering, M.Sc. in Project Management (UNITEC, degree in progress). Spanish (native) · English (professional).
