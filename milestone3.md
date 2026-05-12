---
layout: page
title: Milestone 3
parent: Projects
nav_order: 3
---

## Milestone 3: Integration and Deployment

### Key Dates

- **Due:** 11/12

---

### Overview

These guidelines are meant to provide general direction for preparing your Milestone 3 submission. Every project is unique, so if you believe your work doesn't fully fit within these expectations, please discuss it with your TF. The goal is to ensure that your submission aligns with the spirit of the assignment while still reflecting the specific goals and scope of your project.

In the weeks since Milestone 2, we've covered:

- Advanced training workflows: experiment tracking with W&B, multi-GPU training, and serverless training on Vertex AI.
- Serverless deployment using Cloud Functions and Cloud Run.
- ML Workflows with Vertex AI for orchestrating scalable pipelines.
- System tradeoffs: performance, cost, and design choices.
- Evaluating and monitoring ML systems in production.
- APIs for exposing model functionality.
- Frontend development for user-facing interfaces.

For this milestone, your goal is to **integrate your model into a running system**. You should have a working end-to-end application — from training and deployment to a user-facing interface.

---

### Template Repository

<span style="color: red">**[ADD LINK]**</span>

---

### Objectives

#### 1. Advanced Training Workflows

- Experiment tracking using Weights & Biases (W&B) or an equivalent tool.
- Serverless training on Vertex AI (or documented equivalent), with at least one training run logged and reproducible.
- If applicable: multi-GPU training or distributed training setup.

#### 2. Serverless Deployment

- Deploy your model or API using Cloud Functions or Cloud Run.
- The service should be publicly accessible (or accessible to the teaching staff).
- Document the deployment configuration and how to redeploy.

#### 3. ML Workflows with Vertex AI

- At least one automated ML pipeline or workflow using Vertex AI Pipelines or equivalent.
- Workflow should cover data preprocessing, model training, and/or evaluation steps.

#### 4. Production Monitoring

- Basic monitoring in place: logging, error tracking, and/or performance metrics.
- Document what is being monitored and how to access logs or dashboards.

#### 5. Working API

- A functional API that exposes your model's predictions.
- API should be documented (endpoints, input/output format, example requests).
- API should be tested (unit tests or integration tests).

#### 6. Functional Frontend

- A user-facing interface connected to your API.
- The frontend should allow a user to interact with your model end-to-end.
- Can be a simple web app, Streamlit app, or equivalent — polish is not the priority; functionality is.

---

### Deliverables

#### 1. Code Submission

- All code for the components above, well-organized and documented.
- Any additions or modifications relative to Milestone 2 must be highlighted in the README.md file.

#### 2. README.md

- How to reproduce training runs (experiment tracking setup, Vertex AI job configuration).
- How to deploy the service (Cloud Functions/Cloud Run config and commands).
- How to run the ML pipeline.
- How to access the API (endpoints and example calls).
- How to launch the frontend.

#### 3. Evidence of a Running System

- A training run tracked in W&B (or equivalent).
- The deployed service responding to a request.
- The frontend interacting with the API.

---

### Submission Instructions

All deliverables must be submitted via GitHub (**milestone3** branch); submit the full commit hash on Canvas by **9:00 PM ET, November 12th**.

---

### TF Presentation & Evaluation

This milestone is evaluated through a **15-minute team presentation (with slides) to your assigned project TF**, held during your regular weekly TF meeting.

- **Format:** 15 minutes of team-led presentation, followed by Q&A from the TF.
- **Q&A scope:** The TF will ask questions of the team **and of individual members**, covering both the slides and the details of your GitHub repository (code, configs, infrastructure, tests, design choices).
- **Shared accountability:** Every team member must be prepared to answer questions on **all** parts of the project. "I didn't do that part" is not an acceptable answer. Divide the labor however you choose — but the *understanding* must be shared across the entire team.
- **Slides:** Bring slides that walk through what you built, why, and what's next. Be ready to navigate to specific files in your repository when asked.
