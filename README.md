# Olá, eu sou o Wallace Campista

**AI Engineer & Desenvolvedor Full Stack** · Java / Spring Boot · Rio de Janeiro, Brasil

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/wallace-campista-rocha-7582b3141)
[![Site](https://img.shields.io/badge/wallacecampista.com.br-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.wallacecampista.com.br)
[![Email](https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=minutemailer&logoColor=white)](mailto:wallace_campista@live.com)

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![LangChain4j](https://img.shields.io/badge/LangChain4j-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL_+_pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logoColor=black)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

Sou um desenvolvedor brasileiro com mais de 4 anos de experiência em back-end **Java/Spring Boot** e foco em **IA generativa**: pipelines de **RAG**, **agentes com function calling** e integração com **LLMs** (OpenAI, Anthropic e modelos locais).

Gosto de levar IA para produção do jeito certo: com testes, avaliação, observabilidade e respostas fundamentadas em fontes reais, não só em demos.

## 🚀 Agora

- 💼 **Analista Java Pleno na Extreme Digital**: microsserviços, API Gateway e agentes de IA para sistemas da Secretaria de Planejamento e Gestão do Estado do RJ (SEPLAG/RJ)
- 🎓 **Ciência da Computação na UNICARIOCA**, 8º período, com conclusão prevista para 2026

## 🧠 IA & LLMs

- Pipelines de **RAG** ponta a ponta: ingestão, chunking, embeddings e busca vetorial com **pgvector**
- **Retrieval híbrido**: BM25/FTS + busca vetorial fundidos por **Reciprocal Rank Fusion**, com reranking por **MMR**
- **Agentes com function calling** usando **Spring AI** e **LangChain4j**, com pre-routing determinístico e recuperação automática de erros
- **Guardrails e grounding**: nenhum valor, prazo ou código chega ao usuário sem uma fonte rastreável
- **Avaliação de agentes (evals)** automatizada e prompt engineering para saídas confiáveis
- **LLMs locais** (Ollama, LM Studio) quando a privacidade dos dados é requisito
- Automações inteligentes com **n8n**, integrando sistemas e eliminando etapas manuais

## ⚙️ Back-end & Arquitetura

- Microsserviços em **Java 21/25** e **Spring Boot**, com **Spring Cloud Gateway** para roteamento, autenticação centralizada e resiliência
- Segurança com **Spring Security**, **OAuth2 Authorization Server** e **JWT**
- APIs REST documentadas com **Swagger/OpenAPI** e schema versionado com **Flyway**
- Performance: correção de N+1 no JPA, cache com **Redis** e processamento assíncrono
- Persistência poliglota em **PostgreSQL** e **MongoDB**

## ☁️ Cloud, DevOps & Observabilidade

- Infraestrutura como código com **Terraform** na **AWS** (EC2, ECS, RDS, ALB, S3, CloudFront, Lambda, Route 53)
- **Docker** e Docker Compose em produção, TLS com **Traefik** + Let's Encrypt
- CI/CD com **GitHub Actions**, incluindo testes e smoke test pós-deploy
- Observabilidade com **Prometheus**, **Micrometer**, **Grafana** e **Loki**

## 🧪 Qualidade

- Testes unitários e de integração com **JUnit**, **Mockito**, **MockMvc** e **Testcontainers**
- **pytest** e CI em múltiplas versões do Python nos projetos de IA

## 📌 Projetos em destaque

### [Acervo](https://github.com/WallaceCampista/Acervo): plataforma de estudo com IA, RAG 100% local
Assistente de estudo com **Spring AI** rodando inteiramente em máquina local (Ollama / LM Studio). Retrieval híbrido (pgvector + PostgreSQL FTS com RRF e MMR), flashcards com repetição espaçada, quizzes, resumos e tutor socrático com respostas em streaming (SSE).
`Java 21` `Spring Boot` `Spring AI` `pgvector` `Testcontainers` `Docker`

### [Artefact](https://github.com/WallaceCampista/Artefact_Challenge): agente de atendimento com LLM local
Agente de atendimento para e-commerce rodando em um modelo 7B local (Qwen2.5), com function calling sobre seis ferramentas, busca híbrida BM25 + embeddings (hit@3 de 21/22) e guardas de grounding na saída. 31 casos de avaliação ponta a ponta aprovados em 3 execuções (93/93) e 107 testes unitários.
`Python` `FastAPI` `Qwen2.5` `RRF` `SSE` `pytest`

### Clinicado: SaaS multi-clínica de gestão em saúde (founder)
Plataforma com cinco perfis de acesso e isolamento de dados por clínica, agenda com validação de conflitos e dashboard de métricas. 205 testes automatizados, observabilidade completa e documentação de conformidade com a **LGPD**.
`Java 25` `Spring Boot 4` `OAuth2` `PostgreSQL 16` `Terraform` `AWS`

## 🌎 Idiomas

Português (nativo) · Inglês (intermediário, leitura técnica fluente) · Francês e Espanhol (básico)
