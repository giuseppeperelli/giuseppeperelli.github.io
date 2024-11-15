---
layout: page
title: Data Management and Analysis 
description: CdS Applied Computer Science and Artificial Intelligence
importance: 2
category: current
---

 - **Instructor**: Giuseppe Perelli
 - **[Google Classroom](https://classroom.google.com/c/NzExMDI3NTU1ODMx?cjc=6liexth)**: Enroll to stay updated about the course.
  - **Codice OPIS**: SN4A9A6Q ([Vademecum](https://www.uniroma1.it/en/pagina/student-opinion-survey-opis))

------


#### Resources
- Books:
  - [B1] J. D. Ullman: Principles of Database & Knowledge-Base Systems, Vol. 1: Classical Database Systems
  - [B2] Lemahieu, W., vanden Broucke, S., & Baesens, B. (2018). Principles of Database Management: The Practical Guide to Storing, Managing and Analyzing Big and Small Data. Cambridge University Press
  - [B3] [A. Albano: Databases Essentials](https://www.fondamentidibasididati.it/) **Free book**

- [Slides](https://drive.google.com/drive/folders/1w_x8EK4SN6WiPuuDG8XtrqjxfVCga3f9?usp=sharing)
- [Hand notes](https://drive.google.com/drive/folders/12YOdTpneBSp8hhmSqzJwPvkqhAgsVBSE?usp=sharing) **WARNING**: the notes might contain mistakes. You can report them by sending me an email.
- [Exercises](https://drive.google.com/drive/folders/1_KQJe6iYN_n7bcm6LlJTLkeUeGsNkV7p?usp=sharing)
- [Exam simulations](https://drive.google.com/drive/folders/1OoCmqzMN04iTN4foI8suPfceJRLaTjlc?usp=sharing)
- [Past exams sheets](https://drive.google.com/drive/folders/1eHVjiabSOjRHNqRuM7ooAwpi0-hKfHcG?usp=sharing)

##### **<span style="color:red"> WARNING </span>**

Due to some work in progress, the first lectures will take place in a different location from the rest of the course.

 - The lecture of **Tuesday 12 November** on **14:00** will take place at **Aula 101** of **Building D - Regina Elena** (RM112-E01P01L005 Viale Regina Elena, 295).

 - The lecture of **Thursday 14 November** on **16:00** will take place at **Aula 101** of **Building D - Regina Elena** (RM112-E01P01L005 Viale Regina Elena, 295).

 - The lecture of **Tuesday 19 November** on **14:00** will take place at **<span style="color:red"> TBA </span>**.

 - The lecture of **Thursday 21 November** on **16:00** will take place at **Aula 101** of **Building D - Regina Elena** (RM112-E01P01L005 Viale Regina Elena, 295).

You are all invited to monitor the updates on the webpage of the course, at page Frequentare, under the tab "Orario delle lezioni": [https://corsidilaurea.uniroma1.it/it/corso/2024/30786/programmazione](https://corsidilaurea.uniroma1.it/it/corso/2024/30786/programmazione)


--------


#### **Timetable**

Classes will start on Tuesday 24th September according to the following calendar:

- **Mondays**: from **14:00** to **17:00** at **Aula De Lollis 3** (Warning! Read the news about rooms above!)
- **Thursdays**: from **16:00** to **18:00** at **Aula De Lollis 3** (Warning! Read the news about rooms above!)

##### **<span style="color:red"> Office hour </span>**

Office hour meetings **<span style="color:red">must be agreed by appointment before hand</span>**. They will start on Wednesday 9th October at the following time.

- Wednesdays: from 16:00 to 18:00 at Department of Computer Science, Edificio E, Viale Regina Elena, 295.

Whenever needed, I can meet students out of the office hours.


#### **Course content**

- Introduction to DBMS
- The relational model
- Relational algebra
  - unary operators: projection, selection. Binary operators: union, difference, intersection, Cartesian production, natural join, \\(\theta-join\\). Negation, universal and existence quantification.
- Database design and normalization
  - Data redundancy, insertion, update, and deletion anomalies. Relational theory definitions: schema, tuple instance, functional dependency, legal instance, closure of \\(F\\). Trivial dependencies, properties of functional dependencies. Armstrong's axioms. Rules: decomposition, union, pseudotransitivity, with Theorem and demonstration. Closure of \\(X\\) and first lemma on the closure (with proofs). Theorem \\(F^+ = F^A\\) with proof. Third normal form, formal definition and alternative definition. Algorithm for computing \\(X^+\\), correctness theorem and proof. Key definition, practical ways to find the keys of a schema, uniqueness check. Decomposition of a schema, definition. Projection of \\(F\\) on the decomposition of a schema, definition. Equivalence between two sets of functional dependencies, definition. Lemma on the closures of two sets of functional dependencies, with proof. Decomposition preserving \\(F\\), definition. Algorithm for checking if \\(F\\) is preserved. Algorithm for computing \\(X^{+}_{G}\\). Decomposition with lossless join, definition. Algorithm for checking if a decomposition has a lossless join, with proof. Minimal cover, definition, and steps to compute it. Decomposition algorithm, with extra step for lossless join, and proof.
- Physical organization of a database
  - Heap, sequential, random (hash). Index sequential access method (ISAM) organization. Tree organizations: b-trees

#### Course diary

 - **26-09-2024** - Relational Model: basic concepts and definitions.
 - **01-10-2024** - Relational Algebra: Projection, Selection, Union Compatible operations, Cartesian Product, natural join, \\(\theta-join\\).
 - **03-10-2024** - Relational Algebra: Universal Quantification.
 - **08-10-2024** - Relational Algebra: Exercises.
 - **10-10-2024** - Relational Theory: relation schemas, instances, functional dependences, closure, keys.
 - **15-10-2024** - Relational Theory: Armstrong's Axioms, closure of \\(X\\), equivalence \\(F^+ = F^A\\).
 - **17-10-2024** - Relational Theory: Third normal form (3NF).
 - **29-10-2024** - Relational Theory: 3NF and BCNF. Exercises on Relational Algebra.
 - **31-10-2024** - Relational Theory: Computing the closure of \\(X\\).
 - **05-11-2024** - Relational Theory: Checking Keys and 3NF. Dependence preservation.
 - **07-11-2024** - Relational Theory: Dependence preservation, Computing \\(X^{+}_{G}\\) from \\(F\\).
 - **12-11-2024** - Relational Theory: Exercises on checking that a given decomposition preserves \\(F\\). Lossless join.
 - **14-11-2024** - Relational Theory: Checking Lossless Join Decompositions (Algorithm).

#### Examination rules (Please **read carefully**)
- The exam for Unit 1 consists to a written part and an oral part.
  - The written part (about 2 and half hours) consists in a section of multiple choice questions about theori and a section with three exercises about: Relational Algebra, Relational Theory, Physical Organization.
  - For the multiple choice questions, each correct answer adds a point, each wrong answer subtracts half a point. You need to score **at least** 6 points out of 10 to pass the section.
  - The exercises of the second section are worth 10 points each. If **all** exercises are evaluated with a sufficient score (6/10), the section is passed.
  - If the written test is passed, you are assigned a mark according to the following *conversion table*

    | **Written Score** | **Final Mark** |
    |-------------------|----------------|
    |   18              |     18         |
    |   19              |     19         |
    |   20              |     19         |
    |   21              |     20         |
    |   22              |     20         |
    |   23              |     21         |
    |   24              |     21         |
    |   25              |     22         |
    |   26              |     22         |
    |   27              |     23         |
    |   28              |     23         |
    |   29              |     24         |
    |   30              |     24         |

  - The final mark can be adjusted by taking the oral part, which is then *optional*. The oral exam can **add or subtract** up to 10 points from the written score.
  - The oral part consists into questions about:
    - Definitions and basics about Relational Theory
    - **Proofs** of theorems in Relational Theory
    - Physical Organization
<!--     - Concurrency -->
  - The oral examination **usually** takes place one week after the written test. **However**, this highly depends on the time needed to mark all the written exams, which is subject to variations, due to my ongoing duties and the number of students taking the exam themselves.
<!--- A passed written examination can be carried forward in the same session, so for example, if you pass the written part in January you can carry it forward and access the oral part in February.
- Between different sessions, you cannot carry forward any passed written part (e.g., you cannot carry forward the written part passed in February to take the oral part in June)
- Students are no longer allowed to sit the exam from remote.-->


#### Exam transcription (Please **read carefully**)

- The course is the first unit of a 2 units 12 credits course "Data Management and Analysis", the second unit will be taught in semester 2 by [Prof. Walter Quattrociocchi](https://walterquattrociocchi.site.uniroma1.it/).
- To pass the 12 credits course, you have to pass 2 separate examinations, one for unit 1 and one for unit 2; only after passing both examinations you will get the 12 credits; there can be no exception to this, so you cannot take unit 1 only, or unit 2 only and receive 6 credits, that is not possible (for Erasmus students, please see below).
- Due to administrative reasons, the students passing Unit 1 who did not yet pass Unit 2, will be recorded as *rinuncia* on the verbale. At the same time, they will receive an email from the instructor, confirming they passed the exam, together with date and final mark.
- **Erasmus students**: unfortunately, Data Management and Analysis is a 12 credits course split into 2 units across 2 semesters, and we cannot record the first (or second) half of the course only. **However**, it is possible to record a single unit in your transcript of records. All you need to do is to mention this to me after you passed the exam. I will then communicate the result to the Erasmus office in Sapienza, which will take care of the official transcription.

------

#### Previous Editions

- **A.A. 2023-24**
  - **[Google Classroom](https://classroom.google.com/c/NjIzNTcyNDQ1OTk5?cjc=w2alm6o)**: Enroll to stay updated about the course.

- **A.A. 2022-23**
  - **[Google Classroom](https://classroom.google.com/c/NTM4NjE5NTc0NDYx?cjc=f6gyif7)**: Enroll to stay updated about the course.
