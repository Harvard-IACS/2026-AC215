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
draft: March 29, 2026  

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

We have designed an in-depth curriculum to ensure a comprehensive understanding of modern AI systems and MLOps. Here's a closer look at the topics we'll be covering (see the [full topics list](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vRGX6JiavaCkk11eg-BKSGvU9D5KKXaBONw9ZflnKJK52QUuTTpDnHpBhxSoBf95Q/pubhtml?gid=182104043&single=true) ):


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


As we journey through these topics, students will gain a holistic perspective, bridging the gap between model development and real-world deployment. With a blend of theory and practical exercises, this course ensures that by the end, you should be able to apply them in practice.

---

## Logistics & Tools

### Lectures

- **Location:** SEC 1.321  
- **Meeting Time:** Tuesday and Thursday 12:45 - 2:45 PM  
- **For Extension Students Only:** Via Zoom  

### Technologies and Platforms

We use TensorFlow and PyTorch for examples, with a primary focus on Google Cloud Platform (GCP). Additionally, tutorials will be provided for AWS for reference purposes.

### Prerequisites

To ensure a seamless learning experience and to make the most of this course, participants are expected to come with a foundational knowledge in the following areas:

1. **Programming Proficiency in Python:**  
   - A strong command over Python's basic constructs, including functions, classes, and modules. Familiarity with libraries like NumPy, Pandas, Matplotlib is essential, as they form the backbone of many data manipulation tasks in AI.

2. **Deep Learning Framework - TensorFlow or PyTorch:**  
   - A working knowledge of the TensorFlow or PyTorch framework is crucial, as many topics will go into its functionalities and methods. Understanding TensorFlow's/PyTorch's basic operations, data handling, and model building mechanisms will be invaluable.

3. **Basic Shell Commands:**  
   - Comfort navigating the command-line interface (CLI), executing shell commands, and performing basic file operations are foundational for many AI-Ops tasks.

4. **Basic Data Structures:**  
   - A good grasp of Python's primary data structures, especially dictionaries and lists, will be instrumental in understanding and manipulating data.

5. **File I/O:**  
   - Knowledge of basic file input/output operations in Python, including reading from and writing to files, is vital for tasks involving data storage and manipulation.

6. **General AI and ML Concepts:**  
   - While this course is centered around AI-Ops, a basic understanding of AI and machine learning concepts, including what models are and how they are trained, will set the context for many advanced topics.

You do not need to be an expert in all of these areas. However, you should be comfortable learning quickly and working through technical material independently. Use course resources, support hours, and peer discussions as needed.

---

## Course Components & Requirements

### Course Components

- **Lectures & Tutorials:** Each class is 2 hours. The first ~75 minutes focus on core concepts. The remaining time is a hands-on tutorial where we apply what you just learned.

- **Support Hours / TF Meetings:**  
  - **Before MS1 (team formation):** Open support hours with TFs for general questions and guidance.  
  - **After MS1:** Structured team meetings with your assigned TF, focused on project progress and feedback.

- **Quizzes (6 total; best 4 of 6 count):** Short assessments to evaluate understanding of core concepts. Quizzes are **in-person for on-campus students** and **online for DCE students**.

- **Team Projects:** Collaborate with classmates to build a fully functional AI application.

- **Discussion Forums:** Ask questions, share ideas, and help each other.

- **Supplementary Readings:** Curated materials to deepen understanding. This field moves fast, so developing the habit of independent reading is part of the course.

### Team Projects: Project-Based Learning: Crafting Your Own AI Solutions

In the dynamic realm of AI and AI-Ops, hands-on experience is paramount. This course encourages each student to bring a unique perspective by working on self-conceived projects. Here's what you need to know:

1. **Crafting Your AI Project:**  
   - Students are expected to conceptualize and develop their own projects. While our teaching staff is here to provide ideas and guidance, the core objective is for each student to nurture and shape their original initiative.  
   - By the end of the semester, the aim is to transform your idea into a fully functional web-app or mobile application.  
   - Project Scope: Your project should incorporate some element of modeling, ensuring it aligns with the learning objectives of the course. Moreover, it is essential that every component of the project must be evaluable by our teaching staff.  
   - **Unleash Your Creativity:** Whether you're driven by a start-up vision, by research lab innovations, or inspired by a personal hobby, this is your platform to bring that idea to life.  

2. **A Guided Demonstration by Pavlos:**  
   - We, the teaching team, will undertake a project that Pavlos [proposes](http://formaggio.me) throughout the semester. This serves as a demonstration and reference point.  
   - Each week will spotlight a different facet of Pavlos' project development. This structured showcase offers students practical insight into course concepts.  
   - Parallelly, students will be prompted to integrate the week's learnings into their projects, ensuring steady progress toward their end goals.

3. **Milestones and Assessment:**  
   - The course will be punctuated with key milestones, designed to assess your project's evolution and your grasp of the AI-Ops concepts. Details of these milestones will be shared in due course.  
   - It's imperative to understand that a significant portion of your grade hinges on these milestones. They are not just checkpoints but pivotal phases that contribute to your project's holistic development and your learning journey.

**In Summation:**  
The heart of this course is experiential learning. We fervently believe that your ideas and paralleling them with structured guidance, we can help you build something real and usable.

### Grade Distribution

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

Per university policy, attendance is required for on-campus students. That said, **we do not take attendance**.
Whether you attend is your choice — but based on extensive prior course data, students who attend (semi-regularly) tend to perform better.

- **Lecture recordings**: Lectures will be recorded, but recording quality may not always be ideal.
- **No in-class midterm/final**: There is no in-class midterm or final exam.
- **Showcase**: The main end-of-term in-person requirement is the project showcase (currently scheduled for **Dec 10**, subject to change).

#### Quizzes and the “best 4 of 6” rule

- **On-campus students**: Quizzes are **in person**. There is **no online version** and **no make-ups**.
- **DCE students**: Quizzes will be **online**.
- **Maximum flexibility**: We use the “best **4 of 6** count” rule to accommodate common disruptions (illness, interviews, travel, etc.). Beyond this flexibility, exceptions are very rare. We enforce this consistently for fairness.

#### Late days (all students)

You have **4 late days total** to use across milestones **MS1–MS4**.

- You may use **at most 2 late days per milestone**.
- **MS5 (final milestone)**: **No late days and no extensions** under any circumstances.

In extreme medical or personal emergencies, contact the course staff as soon as possible. We will review such situations on a case-by-case basis, at the teaching team’s discretion, and requests must be communicated **before the deadline whenever possible**.

### Academic Honesty

- This course places a strong emphasis on ethical behavior. Whether it's ethically handling data or attributing the work of others, students are expected to maintain high standards of integrity.  
- **Acceptable Behaviors:** Discussing course materials, engaging in office hours, debugging with peers, using and citing small portions of code found online, seeking online knowledge, and seeking guidance from tutors.  
- **Unacceptable Behaviors:** Accessing or sharing solutions before submission, plagiarizing, not citing sources of external code or techniques, paying or offering payment for coursework, and sharing course material with future potential students.  
- Engaging in unacceptable behaviors will lead to disciplinary action. When in doubt, always consult the course instructors.

### Collaboration & Teamwork

- Collaboration is encouraged, especially for projects. However, ensure you contribute equally and do not divide tasks in a way that prevents you from understanding all parts of the assignment.

### Feedback & Evaluation

- Continuous feedback is vital for the learning process. While the course has several grading components, always focus on understanding rather than just marks. Please provide feedback on the course structure, content, and delivery so we can continually improve.

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