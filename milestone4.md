---
layout: page
title: Milestone 4
parent: Projects
nav_order: 4
---

## Milestone 4: Development and Deployment

### Key Dates

- **Due:** 12/1

---

### Overview

Milestone 4 focuses on developing, testing, and deploying a user-facing application that integrates all components from previous milestones. This milestone ensures the project is functional, well-tested, and ready for real-world usage through automation and deployment strategies.

---

### Template Repository

<span style="color: red">**[ADD LINK]**</span>

---

### Objectives

#### 1. App Design, Setup, and Code Organization

- Design the application's overall architecture, including the user interface and underlying code structure.
- Emphasize clean code organization for maintainability and efficiency.

#### 2. APIs & Frontend Integration

- Develop robust APIs for communication between the front end and back end.
- Implement a user-friendly front-end interface using these APIs for a seamless user experience.

#### 3. Continuous Integration (CI)

- Implement CI using GitHub Actions or a similar tool.
- Automate building, testing, and deployment processes to ensure new code merges are automatically validated.

#### 4. Automated Testing

- Write and integrate unit tests and end-to-end tests for APIs and the front end.
- Ensure all tests run automatically in the CI pipeline, with results reported on every commit or pull request.

---

### Deliverables

#### 1. Application Design Document

A detailed document outlining the application's architecture, user interface, and code organization.

- **Solution Architecture:** High-level overview of system components and their interactions.
- **Technical Architecture:** Specific technologies, frameworks, and design patterns used.

#### 2. APIs & Frontend Implementation

Working code for APIs and the front-end interface.

- **GitHub repository:** All source code with logical organization and proper documentation.
- **README file:** Description of application components, setup instructions, and usage guidelines.

#### 3. Continuous Integration Setup

A functioning CI pipeline that runs on every push or merge.

- **Code build and linting:** Automated build process and code quality checks using linting tools (e.g., ESLint, Flake8) running on GitHub Actions.
- **Automated testing:** Execution of unit, integration, and system tests with test results reported.

#### 4. Automated Testing Implementation

Integration of automated tests within the CI pipeline using GitHub Actions.

- **Unit tests:** For individual components and functions.
- **Integration tests:** For integrating multiple components.
- **System tests:** Covering user flows and interactions.
- **Test coverage reports:** Integrated into the CI pipeline; code coverage must be at least 50%.

#### 5. Test Documentation

Detailed explanations of the testing strategy and implemented tests.

- **Testing tools used:** (e.g., PyTest).
- **Instructions to run tests manually:** For developers to replicate test results locally.

---

### Submission Instructions

All deliverables must be submitted via GitHub (**milestone4** branch); submit the full commit hash on Canvas by **11:59 PM, December 1st**.

---

### TF Presentation & Evaluation

This milestone is evaluated through a **15-minute team presentation (with slides) to your assigned project TF**, held during your regular weekly TF meeting.

- **Format:** 15 minutes of team-led presentation, followed by Q&A from the TF.
- **Q&A scope:** The TF will ask questions of the team **and of individual members**, covering both the slides and the details of your GitHub repository (code, configs, infrastructure, tests, design choices).
- **Shared accountability:** Every team member must be prepared to answer questions on **all** parts of the project. "I didn't do that part" is not an acceptable answer. Divide the labor however you choose — but the *understanding* must be shared across the entire team.
- **Slides:** Bring slides that walk through what you built, why, and what's next. Be ready to navigate to specific files in your repository when asked.
