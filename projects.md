---
layout: page
title: Projects  
description: A description of project milestones expectations and deliverables.
has_children: true
nav_order: 3
---

# Milestones 

Project Milestones - Overview

| **Milestones** | **Brief Description**                                        | **Due Date** | **Grade %** |
| -------------- | ------------------------------------------------------------ | ------------ | ----------- |
| **MS1**        | <!-- *Project Proposals, Team formation -*  Students submit project proposals and form teams. Staff reviews proposals and return feedback and project approvals by TBD. --><br /><br /> Form teams and submit a project proposal focused on the problem you want to solve, why it matters, who the stakeholders are, and what meaningful impact or success looks like. Include preliminary notes on data, an initial solution direction, and a simple application mockup/wireframe (even low-fidelity) to clarify user flow and scope. Technical choices may remain high-level at this stage and can evolve in later milestones. | **9/29** | **8**       |
| **MS2**        | <!-- *MLOps Infrastructure & Advanced Training Workflows -* Build atomic containers, implement versioned data pipelines, and develop scalable computing solutions for efficient deployment.Scalable and Modular Computing Infrastructure – Enhance training workflows with TensorFlow, experiment tracking, multi-GPU support, and serverless training environments. --><br /><br /> Move from proposal to implementation: set up reproducible environments (VM/virtual env + containers), build a containerized data pipeline with basic data management/versioning, and deliver an initial working app skeleton that reflects your MS1 mockup and user flow. | **10/20** | **14**      |
| **MS3**        | <!-- *Midterm Presentation (video)* - Present your AI application as an investor pitch, covering the problem, value proposition, scalability, future development, and technical details, with slides and code submitted via GitHub. --><br /><br /> Integrate your model into a running backend system. Teams should have advanced training workflows (experiment tracking, serverless training on Vertex AI), ML workflows with Vertex AI Pipelines, a serverless deployment (Cloud Functions or Cloud Run), production monitoring, and a working API. | **11/12** | **18**      |
| **MS4**        | <!-- *Full-Stack Development -*  Design and develop a user-facing application integrating all previous components, with clean code organization, a frontend tied to the API, CI setup, and automated testing. --><br /><br /> Design and develop a user-facing application: an application design document, a frontend connected to the API from MS3, Continuous Integration with GitHub Actions, and an automated test suite with ≥50% coverage. Cloud deployment and scaling are covered in MS5. | **12/1** | **18**      |
| **MS5**        | <!-- *Final Presentation and Deliverables* - Students will complete the project by deploying and scaling it, documenting the work through a Medium blog post, a 6-minute video presentation, and a well-structured GitHub repository. --><br /><br /> Complete the project with Kubernetes deployment, a CI/CD pipeline with ≥70% test coverage, a production-ready ML workflow with automated retraining and deployment, a Medium blog post, a 6-minute video, and a live demo at the Dec 10 showcase. | **12/11**    | **26**      |

**Detailed instructions and submission requirements for each milestone are available on their respective pages:** [MS1](milestone1.md), [MS2](milestone2.md), [MS3](milestone3.md), [MS4](milestone4.md), and [MS5](milestone5.md).

**Total project points: 84** (MS1: 8, MS2: 14, MS3: 18, MS4: 18, MS5: 26)

## Evaluation Format

- **MS1** is submitted as a written proposal (PDF on Canvas).
- **MS2, MS3, and MS4** are evaluated through a **15-minute team presentation (with slides) to your assigned project TF**, held during your regular weekly TF meeting. The TF will ask questions of the team and of individual students, covering both the slides and the contents of the GitHub repository. **Every team member must be prepared to answer questions on all parts of the project** — code, data, infrastructure, modeling, deployment, and design decisions. "I didn't do that part" is not an acceptable answer.
- **MS5** is evaluated through the final video, blog post, GitHub repository, and the Dec 10 showcase.
