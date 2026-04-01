---
layout: home
title: "AC215: MLOps, LLMOps & AIOps - Productionizing AI Systems"
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: "AC215: MLOps & LLMOps Course"
  description: "Learn MLOps, LLMOps, and AIOps fundamentals. Master production AI systems, LLM deployment, and machine learning operations at Harvard."
  keywords: "MLOps, LLMOps, AIOps, machine learning operations, LLM deployment, AI systems, production AI"
---

# **MLOps & LLMOps: Production AI Systems** - AC215
{:.no_toc}

<!-- ## **<span style="color: red;">Enrollment is closed - the class has reached capacity.</span>**
{:.no_toc} -->

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
draft: April 1, 2026  

---

## Course Overview

### Course Introduction

In today’s AI-driven world, building a model is only half the journey. The real challenge is turning that model into a system that is reliable, scalable, and usable in practice.

Welcome to AC215/E115: Productionizing AI. This course focuses on the full lifecycle of machine learning systems, with a strong emphasis on Large Language Models (LLMs). We move beyond model development and focus on what it takes to make systems work in the real world.

You will work with containerization, cloud infrastructure, data pipelines, and modern training workflows. We will cover how to use LLM APIs, build applications around them, fine-tune models for specific tasks, and deploy them at scale. We will also explore emerging patterns such as agentic systems and workflows, where models interact with tools and operate as part of larger pipelines.

The goal is simple: by the end of the course, you should be able to design, build, and deploy a complete AI system.

### Learning Objectives

- Understand the MLOps, LLMOps, and AIOps ecosystem and its role in modern AI systems.
- Deploy and scale AI models, particularly LLM-based systems.
- Work with containerization, cloud infrastructure, data pipelines, and advanced training workflows.
- Build and operate scalable AI applications.

### Course Topics Overview

We have designed an in-depth curriculum to ensure a comprehensive understanding of modern AI systems and MLOps. The topics include (see the [full topics list](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vRGX6JiavaCkk11eg-BKSGvU9D5KKXaBONw9ZflnKJK52QUuTTpDnHpBhxSoBf95Q/pubhtml?gid=182104043&single=true) ):


1. **Introduction:** 
   - Begin with an understanding of the importance of MLOps and how it fits in the broader AI and software development ecosystem.
2. **LLM Topics:** 
   - Large Language Models (LLMs) have led to many new tools and agents that students will use in their projects. In these lectures, we'll look at some of these tools, such as LangChain, LlamaIndex, and API-based workflows. We will also explore RAG and agent-based systems.
3. **Virtual Environments and Virtual Machines:** 
   - Delve into the foundations of isolated software environments, their importance in AI development, and how virtual machines offer a layer of abstraction over physical hardware.
4. **Containers:** 
   - Understand the concept of containerization using tools like Docker, and how they differ from virtual machines.
5. **Data Pipelines, & Cloud Storage:** 

   - Learn core data management techniques including ETL and data versioning. Work with TF Data, TF Records, and PyTorch Dataset/DataLoader. We will also cover how cloud storage fits into the broader MLOps ecosystem. Explore specialized tools for managing large-scale datasets for computer vision and language models. 
     ​
6. **Advanced Training Workflows:** 
   - We will cover advanced training workflows, including experiment tracking with tools like Weights & Biases, leveraging multi-GPU setups for accelerated training, exploring serverless training options using Vertex AI, and fine-tuning large language models (LLMs). 

7. **Advanced Inference Workflows:** 
   - Understand the nuances of model optimization techniques like distillation, quantization, compression, and Low-Rank Adaptation (LoRA). We then move to deployment, hosting, and serving of large language models (LLMs). Explore post-deployment monitoring for model performance, data drift detection, and testing strategies, using tools such as Cloud Functions, Cloud Run, Kubeflow, and Vertex AI Pipelines.
     ​
8. **App Design, Setup, and Code Organization:** 
      - Best practices in designing user-centric AI applications, setting up your development environment, and organizing code for scalability and maintainability.
        ​
9. **APIs & Frontend:** 
      - Learn about RESTful APIs to serve your models and design user interfaces for seamless user interactions.
        ​
10. **Scaling (Kubernetes):** 
       - Delve into Kubernetes, its significance in deploying containerized applications, and understand how to scale your applications to operate at production scale.
         ​

---

## Logistics & Tools

### Lectures

- **Location:** SEC 1.321  
- **Meeting Time:** Tuesday and Thursday 12:45 - 2:45 PM  
- **For Extension Students Only:** Via Zoom  

### Technologies and Platforms
We use TensorFlow and PyTorch for examples, with a primary focus on Google Cloud Platform (GCP). 

Equivalent materials are available for AWS. However, we will not demonstrate AWS in lectures, and support for AWS-specific issues will be limited.

### Prerequisites

You are expected to be comfortable with the following:

1. **Python Programming**  
   - Writing functions, using classes, and organizing code into modules  
   - Familiarity with libraries such as NumPy, Pandas, and Matplotlib  

2. **Deep Learning (TensorFlow or PyTorch)**  
   - Basic model building, training, and data handling  
   - You should have trained simple models before  

3. **Command Line Basics**  
   - Navigating directories, running scripts, and basic file operations  

4. **Core Python Data Structures**  
   - Lists, dictionaries, and how to manipulate them  

5. **File I/O**  
   - Reading from and writing to files  

6. **Basic ML Concepts**  
   - What a model is, how it is trained, and how it is evaluated  

You do **not** need to be an expert in all of these areas. However, you should be comfortable learning quickly and working through technical material independently.

If you are unsure whether you meet these prerequisites, a simple guideline is:  
         If you have completed an introductory machine learning course and have written Python code for it, you should be prepared.

---

## Course Components & Requirements

### Course Components

- **Lectures & Tutorials:** Each class is 2 hours. The first ~75 minutes focus on core concepts. The remaining time is a hands-on tutorial where we apply what you just learned.

- **Support Hours / TF Meetings:**  
  - **Before MS1 (team formation):** Open support hours with TFs for general questions and guidance.  
  - **After MS1:** Structured team meetings with your assigned TF, focused on project progress and feedback.

- **Quizzes (6 total; best 4 of 6 count):** Short assessments to evaluate understanding of core concepts. Quizzes are **in-person for on-campus students** and **online for DCE students**.

- **Team Projects:** Collaborate with classmates to build a fully functional AI application.


- **Supplementary Readings:** Curated materials to deepen understanding. This field moves fast, so developing the habit of independent reading is part of the course.

### Team Projects

You will **design and build your own project** in a team. The staff will help you scope and refine the idea, but the direction and execution are yours.

By the end of the term, you should have a **working web or mobile application** that:
- includes a **meaningful modeling component** (beyond simple API calls), and
- is **fully evaluable** by the teaching staff (i.e., we can access, run, and assess all major components without relying on private or inaccessible systems).
The expectation is a project comparable in scope to a small production-ready application.

1. **Project Development**  
   - You will propose and develop your own project idea.  
   - The goal is to build something functional and meaningful, not just a prototype.  
   - Your project should integrate modeling with a complete system (data, training, deployment, and interface).

2. **Guided Example Project**  
   - The teaching team will develop a reference project throughout the semester ([Formaggio](http://formaggio.me)).  
   - Each week, we will highlight one aspect of this system and connect it to course topics.  
   - You are expected to apply similar ideas to your own project as the course progresses.

3. **Milestones and Evaluation**  
   - The project is structured through a series of milestones.  
   - These milestones are a major component of your grade and track your progress from idea to final system.  
   - Details for each milestone will be provided during the semester.

**In summary:**  
The goal is simple: build something real. Your project should be an end-to-end solution that includes modeling, infrastructure, and a usable interface.

### Grade Distribution

The table below reflects how we weight **steady project progress** and **understanding of core ideas** (quizzes) relative to the full arc above.

| Milestone                                                    | Weight |
| ------------------------------------------------------------ | ------ |
| [MS1](https://harvard-iacs.github.io/2026-AC215/milestone1/) | 4%     |
| [MS2](https://harvard-iacs.github.io/2026-AC215/milestone2/) | 10%    |
| [MS3](https://harvard-iacs.github.io/2026-AC215/milestone3/) | 18%    |
| [MS4](https://harvard-iacs.github.io/2026-AC215/milestone4/) | 18%    |
| [MS5](https://harvard-iacs.github.io/2026-AC215/milestone5/) | 34%    |
| Quizzes (6 total; best 4 count)                             | 16%    |

For more information about the projects and milestones, you can click the links above or visit the [project page](https://harvard-iacs.github.io/2026-AC215/projects/).

---

## Course Policies

### Getting Help

- **ED Forum:** Post questions related to course content or technical issues on the ED forum. This encourages peer learning and allows teaching staff to address common concerns. We regularly monitor the forum to provide guidance.  
- **Teaching Staff Helpline:** For matters specific to the teaching staff, please send your queries to ac215harvard@gmail.com.  
- **Email the Instructor:** For private or individual concerns, please feel free to directly email the instructor.

### Deadline Policy

All course milestones must be submitted by **9:00 PM ET** on the specified due dates.

#### Attendance and participation (on-campus students)

Per university policy, attendance is required for on-campus students. However, we do not take attendance and will not enforce it directly. 
Whether you attend is your choice — but based on extensive prior course data, students who attend (semi-regularly) tend to perform better.

- **Lecture recordings**: Lectures will be recorded, but recording quality may not always be ideal.
- **No in-class midterm/final**: There is no in-class midterm or final exam.
- **Showcase**: The main end-of-term in-person requirement is the project showcase (currently scheduled for **Dec 10**, subject to change).

#### Quizzes and the “best 4 of 6” rule

- **On-campus students**: Quizzes are **in person**. There is **no online version** and **no make-ups**.
- **DCE students**: Quizzes will be **online**.

- **Format:** Quizzes are short (20–30 minutes) and conducted during class time.  
- **Content:** Quizzes include a mix of conceptual questions and short coding tasks (e.g., reading, completing, or modifying code).  
- **Scope:** Quizzes focus on recently covered material and are designed to test practical understanding rather than memorization.

- **Maximum flexibility**: We use the “best **4 of 6** count” rule to accommodate common disruptions (illness, interviews, travel, etc.). Beyond this flexibility, exceptions are very rare. We enforce this consistently for fairness.

#### Late days (all students)

You have **4 late days total** to use across milestones **MS1–MS4**.

- You may use **at most 2 late days per milestone**.
- **MS5 (final milestone)**: **No late days and no extensions** under any circumstances.

In extreme medical or personal emergencies, contact the course staff as soon as possible. We will review such situations on a case-by-case basis, at the teaching team’s discretion, and requests must be communicated **before the deadline whenever possible**.

### Academic Honesty

- Students are expected to maintain high standards of academic integrity.
- **Acceptable Behaviors:** Discussing course materials, engaging in office hours, debugging with peers, using and citing small portions of code found online, seeking online knowledge, and seeking guidance from tutors.  
- **Unacceptable Behaviors:** Accessing or sharing solutions before submission, plagiarizing, not citing sources of external code or techniques, paying or offering payment for coursework, and sharing course material with future potential students.  
- Engaging in unacceptable behaviors will lead to disciplinary action. When in doubt, always consult the course instructors.

### Collaboration & Teamwork

- Collaboration is encouraged, especially for projects. However, all team members are expected to understand and be able to explain all parts of the project.

---

## Policy on Usage of Publicly Available Class Material

1. **Permitted Use:**  
   Class Material is made available primarily for the educational benefit of enrolled students and may be used by others for personal educational purposes only.

2. **Prohibited Use:**  
   - Selling or commercializing any part of the Class Material.  
   - Sharing, distributing, or publishing any part of the Class Material in any form or through any medium without explicit permission from the instructor.  
   - Modifying or altering the Class Material to create derivative works.

3. **Attribution:**  
   Any permitted use of the Class Material must carry appropriate acknowledgment of the source (e.g., the instructor's name, course title, and institution).

4. **Enforcement:**  
   Failure to comply with this policy may result in legal action and/or disciplinary measures as applicable.

### Consent

By accessing and using the Class Material, you indicate your acknowledgment and acceptance of this policy.

---

## Accessibility

We are committed to ensuring that this course is accessible to everyone. If you require special accommodations or have any specific needs, please contact the course administrators as soon as possible.

Adherence to accessibility policies and a commitment to fairness, respect for your learning journey, and consideration for the learning journey of your peers are expected from all students.

---

## Inclusion and Belonging Statement

In this data science class, we strive to create a diverse and inclusive learning environment that respects all identities, including race, gender, class, sexuality, religion, and ability. Our goal is to:

- Advance ethical data science and expose biases in its applications.  
- Encourage a variety of thoughts, perspectives, and experiences.  
- Be a supportive resource, open to understanding and adapting to your unique needs.

To foster inclusion:

- Please inform us if your name or pronouns differ from official records.  
- If something affects your class performance or if you feel uncomfortable with any classroom interactions, reach out to us. You may also find resources at the Harvard Office of Diversity and Inclusion.  
- Respect and consideration for diverse backgrounds and perspectives are expected from all participants.  
- Your feedback is essential in enhancing diversity, inclusion, and ethics within our class. Feel free to contact us or submit anonymous suggestions.

---

## Auditing

To request permission to audit the course, please email ac215harvard@gmail.com with the following:

- Your **Harvard University ID (HUID)**
- A brief **statement of agreement** to the auditing terms outlined below

**Important:**  
You must **not** be currently enrolled in the course when making this request. If you are listed as an enrolled student in Canvas, you must drop the course before you can be added as an auditor.

**Auditors must agree to the following policies:**

- ✅ **In-person attendance is mandatory.** This is a Harvard-wide policy. Auditors who do not confirm their presence during the **first week** of in-class instruction will be removed from the course.

- ✅ **Academic honesty standards apply.** Auditors are expected to follow the same academic integrity rules as enrolled students. Sharing or distributing assignment or solutions is strictly prohibited and will be reported to the Harvard Administrative Board.

- ✅ **No future credit.** Auditors may **not** take this course for credit in the future.

- ✅ **No submissions.** Auditors should **not submit homework, milestones, or participate in course projects**.

- ✅ **Limited access to course resources.** Auditors may not use resources intended for registered students, including **Ed Discussion or TF office hours**.