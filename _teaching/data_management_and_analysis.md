---
layout: page
title: Data Management and Analysis 
description: CdS Applied Computer Science and Artificial Intelligence
img: assets/img/database.jpg
importance: 2
category: current
---

 - **Instructor**: Giuseppe Perelli
 - **[Google Classroom](https://classroom.google.com/c/MjM0ODU1NDU5MzBa?cjc=uygvvjxi)**: Enroll to stay updated about the course.
<!--   - **Codice OPIS**: SN4A9A6Q ([Vademecum](https://www.uniroma1.it/en/pagina/student-opinion-survey-opis)) -->

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

##### **<span style="color:red"> Important News </span>**

 - Due to possible transport and other services interruption, as well as to allow everyone to participate to the national strike and demonstrations, **the lecture of Friday 3rd October is cancelled**. Classes will resume regularly on Monday 6th October.
 - Due to other work duties, the **lectures on Monday 27th October and Friday 31st October are cancelled**.
 - To allow the regular carrying out of extraordinary exams, the **lecture on Monday 3rd November is cancelled**. Lectures will resume regularly on Friday 7th November.

#### Classroom and Timetable

Aula De Lollis 3 - RM158-E01PTEL003

 - Monday: 15:00 -- 18:00
 - Friday: 16:00 -- 18:00

##### Office hour

Office hour is **<span style="color:red">by appointment</span>**. It will start on Friday 26th September as follows.

- Fridays: from 14:00 to 16:00 at Dipartimento di Informatica, Edificio E, Viale Regina Elena, 295.

It is possible to setup meetings in other time slots, if needed.

<center>
<!-- Google Calendar Appointment Scheduling begin -->
<link href="https://calendar.google.com/calendar/scheduling-button-script.css" rel="stylesheet">
<script src="https://calendar.google.com/calendar/scheduling-button-script.js" async></script>
<script>
(function() {
  var target = document.currentScript;
  window.addEventListener('load', function() {
    calendar.schedulingButton.load({
      url: 'https://calendar.google.com/calendar/appointments/schedules/AcZssZ1d9MlxvLxrlBg1Mwklw45roPB8BjyPYIr06Toa85h4Oiylubj9wKQAQQS_NOe5i0Joshw15G_q?gv=true',
      color: '#039BE5',
      label: 'Book an appointment',
      target,
    });
  });
})();
</script>
<!-- end Google Calendar Appointment Scheduling -->
</center>


##### Tutor

The tutor for the course is **Gianmaria Romano**. He is available to meet the students to discuss the content of the course in preparation for the exam. This includes both theory and exercises. You can [get in touch](mailto:romano.2105539@studenti.uniroma1.it?subject=Tutoring appointment for Data Management and Analysis) directly with him. Meetngs work by appointment and are generally taking place in the following slot:

- Tuesdays: from 10:00 to 12:00 Room S1, Department of Computer Science, Viale Regina Elena, 295, Building E


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

 - **22-09-2025** - Relational Model: basic concepts and definitions.
 - **26-09-2025** - Relational Algebra: Projection, Selection, Union Compatible operations, Cartesian Product, natural join, \\(\theta-join\\).
 - **29-09-2025** - Relational Algebra: Universal Quantification. Exercises.
 - **06-10-2025** - Relational Theory: relation schemas, instances, functional dependences, closure, keys.
 - **10-10-2025** - Relational Theory: Armstrong's Axioms, closure of \\(X\\), equivalence \\(F^+ = F^A\\).
<!--  - **17-10-2024** - Relational Theory: Third normal form (3NF). -->
<!--  - **29-10-2024** - Relational Theory: 3NF and BCNF. Exercises on Relational Algebra. -->
<!--  - **31-10-2024** - Relational Theory: Computing the closure of \\(X\\). -->
<!--  - **05-11-2024** - Relational Theory: Checking Keys and 3NF. Dependence preservation. -->
<!--  - **07-11-2024** - Relational Theory: Dependence preservation, Computing \\(X^{+}_{G}\\) from \\(F\\). -->
<!--  - **12-11-2024** - Relational Theory: Exercises on checking that a given decomposition preserves \\(F\\). Lossless join. -->
<!--  - **14-11-2024** - Relational Theory: Checking Lossless Join Decompositions (Algorithm). -->
<!--  - **21-11-2024** - Relational Theory: Checking Lossless Join Decompositions (Exercises). -->
<!--  - **26-11-2024** - Relational Theory: Minimal covers and Decompositions. -->
<!--  - **28-11-2024** - Relational Theory: Finding a decomposition of a relational schema. -->
<!--  - **03-12-2024** - Physical Organization: Heap, Sequential, and Hash files. -->
<!--  - **05-12-2024** - Physical Organization: Exercises on file organization. -->
<!--  - **10-12-2024** - Physical Organization: B-trees. -->
<!--  - **12-12-2024** - Physical Organization: Exercises on file organizations. -->
<!--  - **17-12-2024** - Exam Simulation. -->
<!--  - **19-12-2024** - Relational Theory: Recap on decomposition preserving dependencies. -->

#### Examination rules
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

  - The final mark can be adjusted by taking an *optional* oral part. The oral exam can **add or subtract** up to 10 points from the written score.
  - **<span style="color:red">WARNING</span>**: although optional, **I reserve the right to call some students to the oral exam** whenever I *deem it appropriate*.
  - The oral part consists into questions about:
    - Definitions and basics about Relational Theory
    - **Proofs** of theorems in Relational Theory
    - Physical Organization
<!--     - Concurrency -->
  - The oral examination *usually* takes place one week after the written test. **However**, this highly depends on the time needed to mark all the written exams, which is subject to variations, due to my ongoing duties and the number of students taking the exam themselves.

##### **Important**

- To take the exam, it is **mandatory to book on time** on INFOSTUD. The registration deadline is alwas 7 days before the written test day.
- When registering, *carefully check the notes of the verbale* to find whether it is for Unit 1 or Unit 2 of the course (read the Exam recording section for more info).
- Often, in order to facilitate the organization and progress of the exam, after the registration deadline on INFOSTUD, I will send a simple *google form* to **mandatory fill** just to confirm your attendance. I use this to get the most accurate number of students taking the exam, which I need to book the correct exam room, print an adequate number or tests and, occasionally, organize the exam in more rounds, if needed.

#### Exam recording

- The course is the first unit of a 2 units 12 credits course "Data Management and Analysis", the second unit will be taught in semester 2 by [Prof. Walter Quattrociocchi](https://walterquattrociocchi.site.uniroma1.it/).
- To pass the 12 credits course, you have to pass 2 separate examinations, one for unit 1 and one for unit 2; only after passing both examinations you will get the 12 credits; there can be no exception to this, so you cannot take unit 1 only, or unit 2 only and receive 6 credits, that is not possible (for Erasmus students, please see below).
- Due to administrative reasons, the students passing Unit 1 who did not yet pass Unit 2, will be recorded as *rinuncia* on the verbale. At the same time, they will receive an email from the instructor, confirming they passed the exam, together with date and final mark.
- **Erasmus students**: unfortunately, Data Management and Analysis is a 12 credits course split into 2 units across 2 semesters, and we cannot record the first (or second) half of the course only.

------

#### Previous Editions

- **A.A. 2024-25 [Google Classroom](https://classroom.google.com/c/NzExMDI3NTU1ODMx?cjc=6liexth)**

- **A.A. 2023-24 [Google Classroom](https://classroom.google.com/c/NjIzNTcyNDQ1OTk5?cjc=w2alm6o)**

- **A.A. 2022-23 [Google Classroom](https://classroom.google.com/c/NTM4NjE5NTc0NDYx?cjc=f6gyif7)**
