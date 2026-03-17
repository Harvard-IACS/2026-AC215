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
draft: March 17, 2026  

---

## Course Overview

### Course Introduction

In today's AI-driven world, building a robust deep learning model is only half the journey. The real challenge often lies in bringing this model to life in the form of an application that's scalable, maintainable, and ready for real-world deployment. Welcome to AC215/E115: Productionizing AI (Machine Learning Operations), where we will traverse the complex landscape of Machine Learning Operations, with a special focus on Large Language Models (LLMs). This course has been meticulously curated to provide a holistic understanding of the complete deep learning workflow, from refining your models to deploying them in production environments.

We will dive deep into topics like containerization, cloud functions, data pipelines, and advanced training workflows, with specific emphasis on LLMs. You will learn how to utilize LLM APIs effectively, host APIs, fine-tune LLMs for specific tasks, adapt them to various domains, and build applications around them. Our objective is not only to help you grasp these concepts but also to enable you to build and deploy scalable AI applications. We will examine the particular intricacies of LLMs and their applications in real-world scenarios.

Whether you are an AI enthusiast wanting to understand the intricacies of Machine Learning Operations or a seasoned professional aiming to fortify your knowledge, this course promises a comprehensive exploration of the production side of AI, with a spotlight on LLM applications and productionizing.

### Learning Objectives

- Understand the AI-Ops ecosystem and its role in modern AI systems.
- Master deployment and scaling of AI models, particularly LLMs.
- Gain practical skills in containerization, cloud infrastructure, data pipelines, and advanced training workflows.
- Build scalable AI applications and production systems.

### Course Topics Overview

We have designed an in-depth curriculum to ensure a comprehensive understanding of AI-Ops. Here's a closer look at the topics we'll be covering (see [full topics list](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vRGX6JiavaCkk11eg-BKSGvU9D5KKXaBONw9ZflnKJK52QUuTTpDnHpBhxSoBf95Q/pubhtml?gid=182104043&single=true) ) for a full list of topics):


1. **Introduction:** 
   - Begin with an understanding of the importance of AI-Ops and how it fits in the broader AI and software development ecosystem.
2. **LLM Topics:** 
   - Large Language Models (LLMs) have led to many new tools and agents that students will use in their projects. In these lectures, we'll look at some of these tools, such as LangChain, LamaIndex, and API calls. We'll also explore RAGS and AI agents, which make it easy to work with LLMs.
3. **Virtual Environments and Virtual Machines:** 
   - Delve into the foundations of isolated software environments, their importance in AI development, and how virtual machines offer a layer of abstraction over physical hardware.
4. **Containers:** 
   - Understand the concept of containerization using tools like Docker, and how they differ from virtual machines.
5. **Data Pipelines, & Cloud Storage:** 

   - Learn core data management techniques including ETL and data versioning. Learn to leverage TF Data and TF Records, PyTorch's Dataset and DataLoader for efficient data handling. Also we will learn how cloud storage solutions fit into the AI-Ops ecosystem.solutions. Explore specialized tools for managing large-scale datasets for computer vision and language models. 
     ​
6. **Advanced Training Workflows:** 
   - We will look into techniques of advanced training workflows, covering experiment tracking with tools like Weights & Biases, leveraging multi-GPU setups for accelerated training, exploring serverless training options using Vertex AI, and fine-tuning large language models (LLMs) . 

7. **Advanced Inference Workflows:** 
   - Understand the nuances of model optimization techniques like distillation, quantization, compression, and Low-Rank Approximation (LORA). We then move to model deployment, hosting, and serving large language models (LLMs) effectively. Explore post-deployment monitoring for model performance, data drift detection, and testing strategie.  Cloud Functions, Cloud Run, Kubeflow, and Vertex AI Pipelines.
     ​
8. **App Design, Setup, and Code Organization:** 
      - Best practices in designing user-centric AI applications, setting up your development environment, and organizing code for scalability and maintainability.
        ​
9. **APIs & Frontend:** 
      - Learn about RESTful APIs to serve your models and design user interfaces for seamless user interactions.
        ​
10. **Scaling (k8):** 
       - Delve into Kubernetes, its significance in deploying containerized applications, and understand how to scale your applications to cater to millions of users.
         ​


As we journey through these topics, students will gain a holistic perspective, bridging the gap between model development and real-world deployment. With a blend of theory and practical exercises, this course ensures that by the end, you're not just familiar with these concepts, but proficient in applying them.

---

## Logistics & Tools

### Lectures

- **Location:** SEC 1.321  
- **Meeting Time:** Tuesday and Thursday 12:45 - 2:45 PM  
- **For Extension Students Only:** Via Zoom  

### Technologies and Platforms

We will demonstrate most ideas using TensorFlow/PyTorch, utilizing the Google Cloud Platform (GCP). Additionally, tutorials will be provided for AWS for reference purposes.

### Prerequisites

To ensure a seamless learning experience and to make the most of this course, participants are expected to come with a foundational knowledge in the following areas:

1. **Programming Proficiency in Python:**  
   - A strong command over Python's basic constructs, including functions, classes, and modules. Familiarity with libraries like NumPy, Pandas, Matplotlib is essential, as they form the backbone of many data manipulation tasks in AI.

2. **Deep Learning Framework - Tensorflow or PyTorch:**  
   - A working knowledge of the TensorFlow or PyTorch framework is crucial, as many topics will go into its functionalities and methods. Understanding TensorFlow's/PyTorch's basic operations, data handling, and model building mechanisms will be invaluable.

3. **Basic Shell Commands:**  
   - Comfortability in navigating the command-line interface (CLI), executing shell commands, and performing basic file operations are foundational for many AI-Ops tasks.

4. **Basic Data Structures:**  
   - A good grasp of Python's primary data structures, especially dictionaries and lists, will be instrumental in understanding and manipulating data.

5. **File I/O:**  
   - Knowledge of basic file input/output operations in Python, including reading from and writing to files, is vital for tasks involving data storage and manipulation.

6. **General AI and ML Concepts:**  
   - While this course is centered around AI-Ops, a basic understanding of AI and machine learning concepts, including what models are and how they are trained, will set the context for many advanced topics.

It's important to note that while prior knowledge in these areas will provide a solid foundation, the course has been structured to ensure gradual progression. Even if you're not an expert in all of the prerequisites, a willingness to learn and engage actively in the course's hands-on components will be crucial for success. If you find yourself struggling with some concepts, we encourage leveraging the course resources, attending office hours, and participating in peer discussions to reinforce your understanding.

---

## Course Components & Requirements

### Course Components

- **Sessions:** Structured lectures focusing on the core topics.  
- **Office Hours:** Dedicated time with your Teaching Fellow (TF) for questions, clarifications, or project guidance.  
- **Quizzes (6 total; best 4 of 6 count):** Short, in-class, closed-book assessments designed to evaluate understanding of core concepts.
- **Team Projects:** Collaborate with classmates to build a fully functional AI application.  
- **Discussion Forums:** Engage in peer-to-peer learning, discussions, and knowledge sharing.  
- **Supplementary Readings:** To complement the topics covered in lectures and enrich your academic comprehension, a selection of readings has been curated. As this is an evolving field, the ability to continuously update your knowledge through independent reading is an integral part of the course.

### Team Projects: Project-Based Learning: Crafting Your Own AI Solutions

In the dynamic realm of AI and AI-Ops, hands-on experience is paramount. This course encourages each student to bring a unique perspective by working on self-conceived projects. Here's what you need to know:

1. **Crafting Your AI Project:**  
   - Students are expected to conceptualize and develop their own projects. While our teaching staff is here to provide ideas and guidance, the core objective is for each student to nurture and shape their original initiative.  
   - By the end of the semester, the aim is to transform your idea into a fully functional web-app or mobile application.  
   - Project Scope: Your project should incorporate some element of modeling, ensuring it aligns with the learning objectives of the course. Moreover, it is essential that every component of the project CAN be evaluable by our teaching staff.  
   - **Unleash Your Creativity:** Whether you're driven by a start-up vision, by research lab innovations, or inspired by a personal hobby, this is your platform to bring that idea to life.  

2. **A Guided Demonstration by Pavlos:**  
   - We, the teaching team, will undertake a project that Pavlos [proposes](http://formaggio.me) throughout the semester. This serves as a demonstration and reference point.  
   - Each week will spotlight a different facet of Pavlos' project development. This structured showcase offers students practical insight into course concepts.  
   - Parallelly, students will be prompted to integrate the week's learnings into their projects, ensuring steady progress toward their end goals.

3. **Milestones and Assessment:**  
   - The course will be punctuated with key milestones, designed to assess your project's evolution and your grasp of the AI-Ops concepts. Details of these milestones will be shared in due course.  
   - It's imperative to understand that a significant portion of your grade hinges on these milestones. They are not just checkpoints but pivotal phases that contribute to your project's holistic development and your learning journey.

**In Summation:**  
The heart of this course is experiential learning. We fervently believe that your ideas and paralleling them with structured guidance, we can equip you with the tangible skills essential in today's AI-driven world.

### Grade Distribution

| Milestone                                                    | Weight |
| ------------------------------------------------------------ | ------ |
| [MS1](https://harvard-iacs.github.io/2026-AC215/milestone1/) | 4%     |
| [MS2](https://harvard-iacs.github.io/2026-AC215/milestone2/) | 10%    |
| [MS3](https://harvard-iacs.github.io/2026-AC215/milestone3/) | 25%    |
| [MS4](https://harvard-iacs.github.io/2026-AC215/milestone4/) | 14%    |
| [MS5](https://harvard-iacs.github.io/2026-AC215/milestone5/) | 35%    |
| [HW1](https://harvard-iacs.github.io/2026-AC215/HW1/)        | 4%     |
| [HW2](https://harvard-iacs.github.io/2026-AC215/HW2/)        | 4%     |
| [HW3](https://harvard-iacs.github.io/2026-AC215/HW3/)        | 4%     |

For more information about the projects and milestones, you can click the links above or visit the [project page](https://harvard-iacs.github.io/2026-AC215/projects/).

---

## Course Policies

### Getting Help

- **ED Forum:** Post questions related to course content or technical issues on the ED forum. This encourages peer learning and allows teaching staff to address common concerns. We regularly monitor the forum to provide guidance.  
- **Teaching Staff Helpline:** For matters specific to the teaching staff, please send your queries to ac215harvard@gmail.com.  
- **Email the Instructor:** For private or individual concerns, please feel free to directly email the instructor.

### Deadline Policy

Consistent and timely completion of assignments is imperative in this course. All course milestones must be submitted by **9:00 PM EST** on the specified due dates.  

Attendance at lectures and sections is **required for all on-campus students**. The teaching staff will record on-campus attendance. For every **4 sessions attended, on-campus students will earn 1 additional late day**. **Any effort to misrepresent attendance will be considered a violation of the honor code and dealt with accordingly.**

Students start with **zero late days** at the beginning of the semester. **They earn 1 late day for every 4 lectures attended**, encouraging regular participation.

If a student has **exhausted all their late days**, **late assignments will not be accepted**. The late day policy is designed to provide maximum flexibility upfront and is intended to cover common disruptions such as illness, travel, or busy schedules. As such, additional late days will **not** be granted for these reasons.

In cases of **serious or extended circumstances** (e.g., prolonged illness, family emergency), students should contact the course staff as soon as possible. In such cases, we may consider alternate arrangements, but please note that extended absences may make it difficult to meet the learning objectives of the course within the semester.

You are allowed a maximum of **three late days per assignment**.  

For group project milestones, the **total number of late days available to the group must be at least equal to the number of group members multiplied by 4**. This ensures sufficient flexibility for the entire team.

If the group’s combined late days do not meet this requirement, the group **cannot** collectively extend the deadline. We encourage groups to plan accordingly and support all members in managing their late days responsibly.

**Final Milestone / Midterms:** No extensions will be permitted for the final milestone or midterms under any circumstances. Therefore, careful time management is strongly encouraged to ensure that you can meet this critical deadline.

*If you have a medical or personal emergency, contact us as soon as possible — do not wait until the deadline passes.*

### Extension School Late Days

**Extension School** students are allocated a maximum of **6 late days** with **at most 3 days applied to any single assignment**.

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

- ✅ **Limited access to course resources.** Auditors may not use resources intended for registered students, including **Ed Discussion,  or TF office hours**.