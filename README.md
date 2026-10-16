# Yuri Martins

**Software Architect · Java & AI Engineering**

I build backend systems and applied AI tools with a focus on clear architecture, reproducible workflows, and verifiable results.

## Featured AI projects

### [TracePilot](https://github.com/codeyuri1/tracepilot)

An incident investigation application with a Java 21 and Spring Boot backend and an interactive React interface. It produces structured analyses with a probable cause, supporting evidence, and recommendations for investigation, mitigation, and validation.

The application verifies that cited excerpts appear in the incident material before completing an analysis. I integrated Ollama through an OpenAI-compatible API and validated the flow locally with `qwen2.5-coder:7b`. A deterministic mode supports reproducible demonstrations.

The project also includes PostgreSQL/pgvector, controlled investigation tools, automated tests, CI, and observability with Prometheus and Grafana.

**Technologies:** Java 21 · Spring Boot · Spring AI · React · TypeScript · Ollama · PostgreSQL/pgvector · Docker

### [Repo Agent Chat](https://github.com/codeyuri1/repo-analyzer)

A local assistant for investigating codebases with Retrieval-Augmented Generation (RAG), hybrid search, repository-aware tools, and source-grounded answers.

It indexes repository content, retrieves relevant context, and coordinates an LLM with tools for code investigation. It supports local models through Ollama or OpenAI models, provides terminal and Gradio interfaces, and requires file-and-line citations in its answers.

**Technologies:** Python · RAG · Vector Search · Ollama · OpenAI · Gradio · Docker

## Java project

### [DTO Facility API](https://github.com/codeyuri1/dto-facility-api)

A Spring Boot application that converts JSON input into Java DTOs or Java Records. It includes a Thymeleaf interface, nested-object support, validation, tests, and Docker support.

**Technologies:** Java · Spring Boot · Gradle · Thymeleaf · Docker

## Technical focus

- **Backend and architecture:** Java, Spring Boot, REST APIs, modular design
- **Applied AI:** RAG, hybrid retrieval, LLM integration, controlled tools, verifiable evidence
- **Delivery and operations:** Docker, automated tests, CI, observability, reproducible local environments
