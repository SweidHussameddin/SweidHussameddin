<p align="center">
  <img src="assets/banner.png" alt="Hussameddin Sweid, senior Java / Spring Boot engineer" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hussameddin-sweid"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-hussameddin--sweid-0E2B38?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://www.upwork.com/freelancers/~01ac1112d05d8dcdde"><img alt="Upwork" src="https://img.shields.io/badge/Upwork-fixed--price%20projects-1C8C86?style=flat-square&logo=upwork&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/Germany-remote%2C%20EU%20contracts-F1F3F0?style=flat-square">
</p>

Seven years of Java and Spring Boot, microservices on Kubernetes, event-driven systems on RabbitMQ and Kafka, OAuth2 and OIDC. Today a senior engineer on an industrial IoT telemetry platform with 50+ developers. Before that I founded and led an AI agent platform: a multi-provider LLM gateway, agents with tool calling, MCP, a team of up to ten, two years in production.

<br>

## Building in public

<table>
<tr>
<td width="55%" valign="top">
  <a href="https://github.com/SweidHussameddin/support-bot"><img src="assets/support-bot-demo.gif" alt="support-bot demo: a question is answered from a PDF with the page cited, a booking request is handed over to a person" width="100%"></a>
</td>
<td valign="top">

### [support-bot](https://github.com/SweidHussameddin/support-bot)

A support chatbot that answers from your own documents, cites file and page, and hands the conversation to a person instead of guessing.

- FastAPI, one process, no vector database to operate
- Local hybrid retrieval: embeddings on CPU plus BM25, fused
- Any OpenAI-compatible model, free OpenRouter models for the demo
- Strict JSON answer contract; sources the model never saw are dropped
- Drop-in widget, one script tag, no framework
- Tests run without a key or network

![CI](https://img.shields.io/github/actions/workflow/status/SweidHussameddin/support-bot/ci.yml?style=flat-square&label=ci) ![Python](https://img.shields.io/badge/Python-3.12-F1F3F0?style=flat-square&logo=python&logoColor=0E2B38)

</td>
</tr>
<tr>
<td width="55%" valign="top">
  <a href="https://github.com/SweidHussameddin/llm-gateway"><img src="assets/llm-gateway-console.png" alt="llm-gateway console: an agent run that calls two tools on a local model, every model call and tool step listed with tokens and cost" width="100%"></a>
</td>
<td valign="top">

### [llm-gateway](https://github.com/SweidHussameddin/llm-gateway)

One OpenAI-compatible endpoint in front of several providers, with failover, cost control and tool-calling agent runs. The shape of the gateway I ran in production, reduced to what a team needs on day one.

- Spring Boot 4, Java 25, virtual threads, no database or broker
- Model aliases map to ordered routes; circuit breaker per route
- OpenAI-compatible providers plus a native Anthropic adapter, both streaming
- Tokens priced per route, JSONL ledger, per-key budgets (402 when spent)
- Agents run server-side tools that are plain Spring beans
- Checkstyle (Google style) and tests that need no network

![CI](https://img.shields.io/github/actions/workflow/status/SweidHussameddin/llm-gateway/ci.yml?style=flat-square&label=ci) ![Java](https://img.shields.io/badge/Java-25-F1F3F0?style=flat-square&logo=openjdk&logoColor=0E2B38) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-4-F1F3F0?style=flat-square&logo=springboot&logoColor=0E2B38)

</td>
</tr>
</table>

**Next up:** a Spring Boot 4 / Java 25 upgrade walkthrough on a real service, step by step with the tests green at every stop.

<br>

## What I do for clients

<table>
<tr><td width="24%"><b>AI into existing backends</b></td><td>LLM gateways, agents with tools, retrieval over your own data, evaluation sets, cost control. Java (Spring AI, LangChain4j) or Python (FastAPI).</td></tr>
<tr><td><b>Modernisation</b></td><td>Spring Boot 2 to 3 and 4, Java 8 to 25, Auth0 or Keycloak to Entra ID, monolith to events. Tests stay green at every step.</td></tr>
<tr><td><b>Quality and operations</b></td><td>Testcontainers, WireMock, quality gates, CI/CD, Kubernetes on Azure and bare metal.</td></tr>
<tr><td><b>Automation</b></td><td>n8n and AI agents for support and back-office work, built with error handling and runbooks.</td></tr>
</table>

<br>

## Stack

<p>
  <img alt="Java" src="https://img.shields.io/badge/Java_25-0E2B38?style=flat-square&logo=openjdk&logoColor=white">
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot_4-0E2B38?style=flat-square&logo=springboot&logoColor=7FE3D2">
  <img alt="Python" src="https://img.shields.io/badge/Python-0E2B38?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-0E2B38?style=flat-square&logo=fastapi&logoColor=7FE3D2">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-0E2B38?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="Kafka" src="https://img.shields.io/badge/Kafka-0E2B38?style=flat-square&logo=apachekafka&logoColor=white">
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-0E2B38?style=flat-square&logo=rabbitmq&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-0E2B38?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Azure" src="https://img.shields.io/badge/Azure-0E2B38?style=flat-square&logo=icloud&logoColor=white">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-0E2B38?style=flat-square&logo=n8n&logoColor=white">
</p>

<sub>Most of my work lives in private repositories, by contract. The repos above are the part I can show.</sub>
