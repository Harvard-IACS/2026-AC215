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

This milestone focuses on building the core infrastructure for your MLOps projects. You will set up working environments and containerize components for reproducibility.

- **LLM teams:** Build a RAG workflow, including data collection, chunking, and integration with a vector database.
- **Vision / other teams:** Create a robust data setup, fine-tune models for the specific task, and run documented experiments on different model architectures.

By the end, each team should have the required components in place and a **mock-up of the final application** (refining or extending Milestone 1).

---

### Template Repository

<span style="color: red">**[ADD LINK]**</span>

---

### Objectives

Build a reproducible, containerized pipeline and set up the data and model components described below.

#### 1. Virtual Environment Setup

- Create virtual machines/environments to support containers.
- Provide clear setup documentation.

#### 2. End-to-End Containerized Pipeline

- Containerize each component (e.g., ingestion, preprocessing, RAG steps).
- Compose them into a single pipeline that runs start-to-finish.
- The pipeline must be runnable with one command (e.g., `docker compose up` or `make run`).

#### 3. Teams Using LLMs

- Implement a RAG pipeline with data collection, chunking, and vector database integration.

#### 4. Teams Using Vision or Other Modalities

- Create a robust data ingestion and preprocessing pipeline.
- Fine-tune models for your specific task.
- Experiment with different model architectures and document results.

#### 5. Application Mock-up

- Submit a working prototype or mock-up.
- If submitted in Milestone 1, refine or extend it based on feedback.

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

#### 4. Teams Using Vision or Other Modalities

- Containerized pipeline for data ingestion and preprocessing.
- Model fine-tuning scripts with documentation of datasets, hyperparameters, and model versions.
- Experiment logs showing results across models, architectures, or techniques.

#### 5. Application Mock-up

- Application mock-up or wireframe showing UI and back-end interaction.

---

### TF Presentation & Evaluation

This milestone is evaluated through a **15-minute team presentation (with slides) to your assigned project TF**, held during your regular weekly TF meeting.

- **Format:** 15 minutes of team-led presentation, followed by Q&A from the TF.
- **Q&A scope:** The TF will ask questions of the team **and of individual members**, covering both the slides and the details of your GitHub repository (code, configs, infrastructure, tests, design choices).
- **Shared accountability:** Every team member must be prepared to answer questions on **all** parts of the project. "I didn't do that part" is not an acceptable answer. Divide the labor however you choose — but the *understanding* must be shared across the entire team.
- **Slides:** Bring slides that walk through what you built, why, and what's next. Be ready to navigate to specific files in your repository when asked.
