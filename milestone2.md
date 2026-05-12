---
layout: page
title: Milestone 2
parent: Projects
nav_order: 2
---

## Milestone 2: MLOps Infrastructure

### Key Dates

- **Due:** 10/20

---

### Overview

This milestone focuses on moving from proposal to implementation. You will set up reproducible working environments, containerize core components, and establish foundational data operations.

- **LLM teams:** Build an initial RAG-ready workflow (data collection, chunking, and vector database integration at a basic functional level).
- **Vision / other teams:** Build a robust data ingestion/preprocessing workflow and train or adapt a baseline model.

By the end, each team should have the required components in place and an **initial working app skeleton** informed by the Milestone 1 mock-up.

---

### Template Repository

<span style="color: red">**[ADD LINK]**</span>

---

### Objectives

Build a reproducible, containerized pipeline and establish practical data management and application foundations.

#### 1. Virtual Environment Setup

- Create virtual machines/environments to support containers.
- Provide clear setup documentation.

#### 2. End-to-End Containerized Pipeline

- Containerize each component (e.g., ingestion, preprocessing, RAG steps).
- Compose them into a single pipeline that runs start-to-finish.
- The pipeline must be runnable with one command (e.g., `docker compose up` or `make run`).
- Include basic data/version tracking (e.g., dataset snapshot IDs, file versions, or a lightweight versioning tool).

#### 3. Teams Using LLMs

- Implement an initial RAG pipeline with data collection, chunking, and vector database integration.
- Show at least one complete retrieval flow from query to retrieved context.

#### 4. Teams Using Vision or Other Modalities

- Create a robust data ingestion and preprocessing pipeline.
- Train or adapt a baseline model for your task.
- Document early experiments and rationale for next technical decisions.

#### 5. Application Mock-up

- Submit a simple working app skeleton or clickable mock-up.
- Refine or extend the Milestone 1 design based on feedback and what you learned during implementation.

---

### Deliverables

#### 1. Virtual Environment Setup

- Screenshot of running instances (cloud or local).

#### 2. End-to-End Containerized Pipeline

- Dockerfiles + build instructions.
- `pyproject.toml` (using `uv`) for each container.
- Scripts or `docker-compose.yml` (when applicable).
- Documentation explaining the pipeline and exact run instructions.
- Evidence it works end-to-end (logs + a small sample input → output artifact).

#### 3. Teams Using LLMs

- Containerized RAG pipeline with scripts for chunking, vectorization, and DB integration.
- Documentation of the pipeline design and usage.
- Logs showing pipeline runs with sample data.
- Evidence of one end-to-end retrieval example.

#### 4. Teams Using Vision or Other Modalities

- Containerized pipeline for data ingestion and preprocessing.
- Baseline model training/adaptation scripts with documentation of datasets, key hyperparameters, and model versions.
- Experiment logs showing early results and planned next iteration.

#### 5. Application Mock-up

- Application mock-up/wireframe plus a minimal working app skeleton showing basic UI and back-end interaction.

---

### Submission Instructions

All deliverables must be submitted via GitHub (**milestone2** branch); submit the full commit hash on Canvas by **11:59 PM, October 20th**.

---

### TF Presentation & Evaluation

This milestone is evaluated through a **15-minute team presentation (with slides) to your assigned project TF**, held during your regular weekly TF meeting.

- **Format:** 15 minutes of team-led presentation, followed by Q&A from the TF.
- **Q&A scope:** The TF will ask questions of the team **and of individual members**, covering both the slides and the details of your GitHub repository (code, configs, infrastructure, tests, design choices).
- **Shared accountability:** Every team member must be prepared to answer questions on **all** parts of the project. "I didn't do that part" is not an acceptable answer. Divide the labor however you choose — but the *understanding* must be shared across the entire team.
- **Slides:** Bring slides that walk through what you built, why, and what's next. Be ready to navigate to specific files in your repository when asked.
