# Dev Copilot Prompts

A collection of personalized AI copilot prompts designed to support different stages of the software development workflow.

The prompts are organized into four modes: **STUDY**, **ASK**, **PLAN**, and **AGENT CODE**. Each mode has a specific purpose, helping adapt the AI's behavior to the context of the task.

## Modes

### STUDY

Focused on technical learning and real understanding.

The goal is not just to provide answers, but to explain concepts, mental models, trade-offs, common pitfalls, and practical applications.

Useful for:

- studying programming concepts;
- understanding Kotlin, React, Next.js, and software engineering topics;
- reviewing data structures and algorithms;
- preparing for technical interviews;
- connecting new concepts with previous experience.

### ASK

A read-only technical assistant for quick questions, code explanations, and error diagnosis.

It prioritizes direct answers without turning every question into a long lesson or implementation plan.

Useful for:

- debugging errors;
- understanding code snippets;
- reviewing technical decisions;
- asking quick programming questions;
- analyzing possible causes of unexpected behavior.

### PLAN

Focused exclusively on planning before implementation.

It creates structured and incremental implementation plans without writing the final code.

Useful for:

- breaking down technical tasks;
- planning changes before coding;
- preparing a pull request;
- analyzing affected areas;
- defining acceptance criteria;
- identifying risks and trade-offs.

### AGENT CODE

Focused on implementation.

It transforms requirements into code while respecting the existing stack, project patterns, tests, accessibility, and maintainability.

Useful for:

- implementing features;
- fixing bugs;
- generating patches;
- creating tests;
- adapting code to an existing project.

## Repository Structure

```text
dev-copilot-prompts/
├── study.md
├── ask.md
├── plan.md
├── agent.md
└── README.md
```

## Technical Context

These prompts are personalized around my current development experience and learning goals.

Main areas:

- React.js
- Next.js
- JavaScript
- TypeScript
- Kotlin
- Jetpack Compose
- Java
- Spring Boot

Additional experience includes APIs, SQL, testing, AWS, Docker, Terraform, Prometheus, Grafana, and software observability.

The prompts are designed to adapt their level of explanation depending on the technology and context instead of assuming a single stack or a fixed knowledge level.

## Why Four Modes?

Different tasks require different types of assistance.

When I am studying, I do not want the AI to immediately solve everything.

When I have a quick technical question, I do not need a complete implementation plan.

When I am planning a feature, I want to think about scope and risks before generating code.

And when I explicitly want implementation, I want code that is understandable, testable, and consistent with the project.

Separating these behaviors into modes helps keep the interaction focused.

## Personalization

These prompts were adapted to my current experience as a software developer in training, with stronger experience in Front-end development and growing experience in Android development with Kotlin and Jetpack Compose.

The goal is to use AI as a technical copilot for learning and software development without replacing technical reasoning.

## License

This repository is intended for personal study and development workflow experimentation.
