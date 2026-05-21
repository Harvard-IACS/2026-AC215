---
layout: page
title: Milestone 5
parent: Projects
nav_order: 5
---

## Milestone 5: Deployment & Final Project Delivery

### Key Dates

- **Due:** 12/11
- **Showcase:** 12/10

---

### Overview

These guidelines are meant to provide general direction for preparing your Milestone 5 submission. Every project is unique, so if you believe your work doesn't fully fit within these expectations, please discuss it with your TF. The goal is to ensure that your submission aligns with the spirit of the assignment while still reflecting the specific goals and scope of your project.

The final milestone focuses on two key areas:

1. Production-ready deployment with Kubernetes.
2. Public communication of results through a live showcase.

---

### Template Repository

<span style="color: red">**[ADD LINK]**</span>

---

### Objectives

#### 1. Kubernetes Deployment

- Deploy the application to a Kubernetes cluster.
- Demonstrate basic scaling by manually increasing and decreasing the load (e.g., scaling the number of replicas up and down; document the commands used and include screenshots or logs showing the scaling action).

#### 2. CI/CD Pipeline Implementation

Set up a CI/CD pipeline using *GitHub Actions*. The pipeline should:

- Run unit tests across every container.
- Run integration tests across the exposed API on every pull request.
- Deploy updates to the Kubernetes cluster upon merging changes into the main branch.
- Test coverage must be at least 70% of the lines (applies to API and backend code; frontend and data science notebooks are encouraged but not strictly required for this threshold). Document what functions and modules lack testing.

#### 3. Machine Learning Workflow

Demonstrate a production-ready ML workflow, including:

- Data preprocessing, model training, and evaluation steps integrated into the pipeline.
- Automated retraining and deployment triggered by new data or updates to the codebase.
- Validation checks to ensure only models meeting performance thresholds are deployed (you define the thresholds based on your project; document the metrics and thresholds used).

---

### Deliverables

#### 1. GitHub Repository

- Well-structured and modular codebase.
- Comprehensive README with:
  - Prerequisites and setup instructions.
  - Deployment instructions.
  - Usage details and examples.
  - Known issues and limitations.
- Submit the `main` branch for this deliverable.

#### 2. Video Presentation

Record a **6-minute video** covering:

- Problem statement and the proposed solution.
- Technical architecture and key components.
- Live demo of the application in action.
- Challenges faced and solutions implemented.

Submit the video in **MP4 format** with a minimum resolution of 720p.

#### 3. Blog Post

- Write a **600–800 word Medium blog post** summarizing your project for a general audience. The post should highlight the problem, solution, technical approach, and impact.
- Include visuals or diagrams where appropriate.

#### 4. Self and Peer Review Forms

- Complete self-assessment and peer evaluation forms to provide feedback on team contributions.

#### 5. Showcase (Dec 10th)

- **Event format:** Each team will have **1 hour** during the live showcase to present their project (this is your assigned booth time slot for receiving visitors, not a 1-hour presentation). Participants will visit your booth to interact with your application and learn about your implementation. Monitors will be provided to most teams; additional equipment must be arranged by the team.
- **App requirements:** The app must be fully functional and hosted on **Google Cloud Platform (GCP)** or **AWS**, accessible via a public URL. Include a **QR code** linking to your application.
- **Best of Show award:** A committee will evaluate all projects during the showcase to select the **Best of Show**, based on innovation and impact, technical complexity and robustness, and clarity of presentation.

---

### Submission Instructions

- Submit all deliverables (GitHub repository link, video file, blog post link, and self/peer review forms) via the course submission portal by **9:00 PM ET, December 11th**.
- No late submissions.

---

### Evaluation Criteria

- **GitHub Repository (10 points / ~38%):** Technical depth, final code quality, 70% test coverage, ML workflow validation, coding style, and repository structure.
- **Video Presentation (7 points / ~27%):** Clarity, technical depth, demo quality, and communication of challenges and solutions.
- **Blog Post (4 points / ~15%):** Writing quality, accessibility for general audience, visuals, and effectiveness in communicating project value.
- **Showcase (5 points / ~19%):** Live demo functionality, booth presentation, engagement with visitors, and overall clarity of communication.
