# Hi, I'm Chris Okorochukwu 👋

4th year Computer Science major @ University of Florida (B.S., Spring 2027) — 3× Software Development Engineer Intern @ Amazon, currently applying for a full-time new-grad SWE role.

I like building things end-to-end: backend systems, distributed architecture, and lately a lot of applied LLM work — extraction pipelines, structured outputs, and evaluation harnesses rather than just wrapper apps.

- 🔭 Currently building **[Skiljo](https://github.com/chrisokor/skiljo)** — a policy-fidelity system for turning refund/billing policy into versioned, executable, auditable Skills
- 💼 Three consecutive summers on Amazon's CXT Framework team (2024–2026), designing and delivering production-ready serverless systems
- 🎓 AWS Solutions Architect – Associate (expected completion by Oct. 2026)
- 📫 Reach me at [chrisokor3@gmail.com](mailto:chrisokor3@gmail.com) or [LinkedIn](https://www.linkedin.com/in/christusx/)

---

## Projects

### [Skiljo](https://github.com/chrisokor/skiljo)
Converts refund/billing policy documents into versioned, executable **Skills**, then simulates them against historical support tickets to surface where written policy and real-world practice diverge.
- Four-pass LLM extraction with Pydantic validation, retries, and character-offset citations linking every rule back to source text
- Immutable versioning, full LLM-call audit trail, cross-document contradiction detection
- **Stack:** Python, FastAPI, PostgreSQL, SQLAlchemy, Pydantic, TypeScript/Zod SDK, Streamlit

### [EncryptoChat](https://github.com/chrisokor/EncryptoChat)
An end-to-end encrypted messaging system with a real cryptographic handshake, not a toy cipher.
- X25519 key exchange, PyNaCl (NaCl Box) encryption, Ed25519 signed-challenge authentication, one-time prekeys
- Dockerized, GitHub Actions CI/CD with PostgreSQL + Redis service containers, 64 tests at 89% coverage, versioned image publishing to GHCR
- **Stack:** Python, FastAPI, PostgreSQL, Redis, WebSockets, Docker

---

## Tech I work with

**Languages:** Java, Python, C/C++, TypeScript, SQL
**Cloud/Infra:** AWS (Lambda, API Gateway, DynamoDB, OpenSearch, CDK), Docker
**Backend:** FastAPI, Spring Boot, PostgreSQL, Redis, SQLAlchemy
**AI/ML:** Amazon Bedrock, RAG, structured-output extraction pipelines
