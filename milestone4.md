---
layout: page
title: Milestone 4
parent: Projects
nav_order: 4
---

## Milestone 4: Design & Development

### Key Dates

- **Due:** 12/1

---

### Overview

These guidelines are meant to provide general direction for preparing your Milestone 4 submission. Every project is unique, so if you believe your work doesn't fully fit within these expectations, please discuss it with your TF. The goal is to ensure that your submission aligns with the spirit of the assignment while still reflecting the specific goals and scope of your project.

Since Milestone 3, we've covered:

- Application design, code organization, and patterns for separating frontend, backend, and data science components.
- Building APIs with FastAPI and connecting them to user-facing frontends (simple and React-based).
- Continuous Integration with GitHub Actions: automated builds, linting, and test execution on every commit.
- Automated testing strategies: unit, integration, and system (end-to-end) tests, and measuring code coverage.

For this milestone, your goal is to **design and develop a user-facing application** that integrates all components from previous milestones, backed by a CI pipeline and an automated test suite. By the end of this milestone, your project should be **deployment-ready** — meaning that all components run reliably in your local environment and are packaged (containerized) so they can be deployed in Milestone 5. Deployment-ready means: (1) all services run successfully with a single command, (2) the frontend can interact with the backend locally, and (3) no manual configuration is needed to start the application.

Full cloud deployment, scaling, and CI/CD with deploy-on-merge will be addressed in **Milestone 5**.

---

### Template Repository

<span style="color: red">**[ADD LINK]**</span>

---

### Objectives

#### 1. App Design, Setup, and Code Organization

- Design the application's overall architecture, including the user interface and underlying code structure.
- Emphasize clean code organization for maintainability and efficiency.

#### 2. APIs & Frontend

- Build on the API delivered in Milestone 3, extending or refining it as needed for the full application.
- Develop a user-facing frontend connected to your API that allows end-to-end interaction with your model, running in your local environment.
  - **LLM teams:** typically a chat-style interface (input box, streaming/typed responses, citations or sources where relevant).
  - **Vision / other teams:** typically an upload-and-results interface (file/image upload, model output, optional confidence or explanation).
- Cover the basics of usability: a clean responsive layout (desktop browser is required; mobile responsiveness is optional), loading indicators for long-running calls, and visible error/empty states when things go wrong or no results exist.
- Include a screenshot or short demo of the frontend interacting with the API end-to-end.

#### 3. Continuous Integration (CI)

- Implement CI using GitHub Actions or a similar tool.
- Automate building, linting, and testing on every commit or pull request so new code is automatically validated. (Continuous *deployment* is covered in Milestone 5.)

#### 4. Automated Testing

- Write and integrate unit tests and end-to-end tests for APIs and the front end.
- Ensure all tests run automatically in the CI pipeline, with results reported on every commit or pull request.

---

### Deliverables

#### 1. Application Design Document

A detailed document outlining the application's architecture, user interface, and code organization.

- **User Interface Mockups / Wireframes:** Include screenshots of the user interface wireframes or mockups from MS1 / MS2, plus the primary user flow(s) walking through the key screens.
- **Solution Architecture:** High-level overview of system components and their interactions.
- **Technical Architecture:** Specific technologies, frameworks, and design patterns used.
- **Data Flow Diagram:** How data moves through the system end-to-end (ingestion → preprocessing → model/inference → API → frontend).
- **Sequence Diagram:** Runtime interaction for at least one primary user flow (e.g., user submits a query → frontend → API → model → response).
- **API Contract Summary:** Table or short list of endpoints, methods, and request/response shapes. May reference the API docs / OpenAPI spec from MS3.
- **Code Organization:** Follow a code organization pattern that cleanly separates code for frontend, backend, and data science tasks.

#### 2. APIs & Frontend Implementation

Working code for APIs and the front-end interface.

- **GitHub repository:** All source code with logical organization and proper documentation.
- **README file:** Description of application components, setup instructions, and usage guidelines.
- **Containerization:** The frontend should be containerized alongside the API and any services from MS2 / MS3.
- **Local Testing:** After bringing the components up, the frontend should be reachable in a browser at a documented local URL (e.g., `http://localhost:3000`), and the API at its documented port (e.g., `http://localhost:9000`).

#### 3. Continuous Integration Setup

A functioning CI pipeline that runs on every push or merge.

- **Code build and linting:** Automated build process and code quality checks using linting tools (e.g., ESLint, Flake8) running on GitHub Actions.
- **Automated testing:** Execution of unit, integration, and system tests with test results reported.

#### 4. Automated Testing Implementation

Integration of automated tests within the CI pipeline using GitHub Actions.

- **Unit tests:** For individual components and functions.
- **Integration tests:** For integrating multiple components.
- **System tests:** Covering user flows and interactions.
- **Test coverage reports:** Integrated into the CI pipeline; code coverage must be at least 50% (applies to API and backend code; frontend and data science notebooks are encouraged but not strictly required for this threshold).

#### 5. Test Documentation

Detailed explanations of the testing strategy and implemented tests.

- **Testing tools used:** (e.g., PyTest).
- **Instructions to run tests manually:** For developers to replicate test results locally.

---

### Submission Instructions

All deliverables must be submitted via GitHub (**milestone4** branch); submit the full commit hash on Canvas by **9:00 PM ET, December 1st**.

---

### TF Presentation & Evaluation

This milestone is evaluated through a **15-minute team presentation (with slides) to your assigned project TF**, held during your regular weekly TF meeting.

- **Format:** 15 minutes of team-led presentation, followed by Q&A from the TF.
- **Q&A scope:** The TF will ask questions of the team **and of individual members**, covering both the slides and the details of your GitHub repository (code, configs, infrastructure, tests, design choices).
- **Shared accountability:** Every team member must be prepared to answer questions on **all** parts of the project. "I didn't do that part" is not an acceptable answer. Divide the labor however you choose — but the *understanding* must be shared across the entire team.
- **Slides:** Bring slides that walk through what you built, why, and what's next. Be ready to navigate to specific files in your repository when asked.
