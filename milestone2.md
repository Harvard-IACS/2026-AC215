---
layout: page
title: Milestone 2
parent: Projects
nav_order: 2

---

### Milestone 2: _MLOps Infrastructure_  

**Building Containers and ML Components**

---

### Key Date

- **Due:** 10/16

---

### Overview
This milestone focuses on building the core infrastructure for your MLOps projects.
You will set up working environments and containerize components for reproducibility.

- **LLM Teams:** Build a RAG workflow, including data collection, chunking, and integration with a vector database.  
- **Vision / Other Teams:** Create a robust data setup, fine-tune models for the specific task, and run documented experiments on different model architectures.  

By the end, each team should have the required components in place and a **mock-up of the final application** (refining or extending Milestone 1).

---

### [Template Repository](https://github.com/ac2152024/ac2152024_template/tree/milestone2)

---

### Objectives & Deliverables

#### 1. Virtual Environment Setup

- Create virtual machines/environments to support containers.  
- Provide clear setup documentation.  

**Deliverable:**  

- Screenshot of running instances (cloud or local).

---

#### 2. End-to-End Containerized Pipeline

- Containerize each component (e.g., ingestion, preprocessing, RAG steps, etc.).
- Compose them into a single pipeline that runs start-to-finish.
- The pipeline must be runnable with one command (e.g., `docker compose up` or `make run`).

**Deliverables:**

- Dockerfiles + build instructions  
- `pyproject.toml` (using `uv`) for each container  
- Scripts or `docker-compose.yml` (when applicable)  
- Documentation explaining the pipeline and exact run instructions  
- Evidence it works end-to-end (logs + a small sample input → output artifact)


---

#### 3. Teams Using LLMs

- Implement a RAG pipeline with data collection, chunking, and vector database integration.  

**Deliverables:**  

- Containerized RAG pipeline with scripts for chunking, vectorization, and DB integration  
- Documentation of the pipeline design and usage  
- Logs showing pipeline runs with sample data  

---

 #### 4. Teams Using Vision or Other Modalities
- Create a robust data ingestion and preprocessing pipeline.  
- Fine-tune models for your specific task.  
- Experiment with different model architectures and document results.  

**Deliverables:**  
- Containerized pipeline for data ingestion and preprocessing  
- Model fine-tuning scripts with documentation of datasets, hyperparameters, and model versions  
- Experiment logs showing results across models, architectures, or techniques  

---

#### 5. Application Mock-up

- Submit a working prototype or mock-up.  
- If submitted in Milestone 1, refine or extend it based on feedback.  

**Deliverables:**  

- Application mock-up or wireframe showing UI and back-end interaction  

---