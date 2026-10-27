## Software Engineer · Systems Architecture · AI on the JVM

My career is in the Java Enterprise world, designing and building the systems large organizations run on, with system design and architecture at the core of the work. I now build AI into production software: language models grounded in an organization's own data, agents with controlled access to real systems, and the predictability every production system has to meet.

AI has been a Python story, and enterprise software is a JVM story. The two are converging through agent frameworks and native model integration, and that convergence is where I build. Further out, I'm building toward intelligence that leaves the text box and acts in the physical world, where applications, models and hardware are designed as one system.

### Products

#### RaastaPay · [raastapay.in](https://raastapay.in) · [Architecture docs](https://raastapay.in/docs)
An AI advisory platform for small trucking operators in India. A fleet owner enters a trip, gets the cost math back instantly, and Claude returns a take-or-skip verdict asynchronously over Kafka, so a slow model never blocks the app.

**Tech stack:** Java 25 · Spring Boot 4.1 · Spring Web · Spring Security · Spring Data JPA · Spring AI + Claude · Apache Kafka 4.3 (KRaft) · PostgreSQL 16 · Flyway · Docker Compose · LangChain4j agentic (multi-agent market simulation) · Tribuo (in-JVM TAKE/SKIP scorecard) · React Native + Expo · TypeScript · TanStack Query · Zustand · Razorpay (UPI) · WhatsApp Cloud API · OCR for lorry receipts · Redis · Azure Container Apps · Azure Event Hubs · Azure Blob Storage · Azure Key Vault · Application Insights · Sentry

### Open source

#### jamna.nn · [Code](https://github.com/vishnu-vardhan-d/jamna.nn) · [Interactive explainer](https://vishnu-vardhan-d.github.io/jamna.nn/)
A small transformer language model written in pure Java with no libraries, not even a math one. It learns to sort numbers by predicting the next token, the same way a language model learns to write. The interactive explainer walks through embeddings, attention and softmax with the real trained weights.

**Tech stack:** Java (zero dependencies) · Maven

#### options-wall-street · [Code](https://github.com/vishnu-vardhan-d/options-wall-street) · [Docs](https://vishnu-vardhan-d.github.io/options-wall-street/) · [Architecture](https://github.com/vishnu-vardhan-d/options-wall-street/blob/main/docs/ARCHITECTURE.md)
An options screener for the wheel strategy, built for personal use. A Spring Boot engine pulls market data from the Charles Schwab API, pre-computes the screen on a schedule to stay under the API rate limit, and serves it to a Next.js dashboard. Brokers sit behind ports and adapters, and an ArchUnit test fails the build if the screener imports a concrete broker.

**Tech stack:** Java 25 · Spring Boot 4 · Spring Data JPA · Flyway · Spring Kafka · Next.js · TypeScript · Tailwind · Azure (Bicep)

#### KanbanAssist
An assistant for engineering teams. It reads a new Azure DevOps ticket, finds the most similar closed tickets with vector search, and suggests a likely root cause and fix with the matching tickets as evidence. Every step is traced, and answers are scored against closed tickets whose real cause is known. Open-source release planned for December 2026.

**Tech stack:** Java 25 · Spring Boot 4.1 · Spring Web MVC · Spring AI 2 · Claude Sonnet and Haiku · Ollama (nomic-embed-text) · MCP client · Azure DevOps MCP · Azure DevOps service hooks · Apache Kafka 4 (KRaft) · PostgreSQL 16 + pgvector · Hibernate Vector · Flyway · OpenTelemetry · Langfuse · Spring Boot Actuator · Cloudflare Tunnel · LangChain4j agentic · Playwright MCP · JUnit 5 · Testcontainers · React · TypeScript · Vite · Tailwind CSS · assistant-ui · shadcn/ui · Zustand · Docker Compose · GitHub Actions · Terraform · AWS

### Articles
- [Ollama on a 4 GB GPU vs Claude: When a Local Model Stops Being Enough](https://vishnuvardhan.io/blog/ollama-or-claude)
- [Running an Open-Source LLM on My Own GPU](https://vishnuvardhan.io/blog/run-an-llm-on-your-own-gpu)
- [Attention in pure Java, with real numbers](https://vishnuvardhan.io/blog/attention-in-pure-java)
- [Publishing a Home Server Through a Cloudflare Tunnel](https://vishnuvardhan.io/blog/publishing-a-home-server)
- [Counting Visitors on a Static Site](https://vishnuvardhan.io/blog/counting-visitors-on-a-static-site)

### GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=vishnu-vardhan-d&show_icons=true&hide_border=true&theme=github_dark&include_all_commits=true&count_private=true" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=vishnu-vardhan-d&hide_border=true&theme=github-dark" />
</p>
