---
layout: default
title: Data Management and Analysis (Unit 1) A.A. 2022/23
description: 
---

### Data Management and Analysis (Unit 1)

#### General Information
 
 - **Instructor**: Giuseppe Perelli
 - **Google Classroom**: [Enroll](https://classroom.google.com/c/NTM4NjE5NTc0NDYx?cjc=f6gyif7)
 
#### Classes

 - **Timetable**: TBA
 
#### Course content (tentative)

- Introduction to DBMS
- The relational model
- Relational algebra
  - unary operators: projection, selection. Binary operators: union, difference, intersection, Cartesian production, natural join, θ-join. Negation, universal and existence quantification.
- Database design and normalization
  - Data redundancy, insertion, update, and deletion anomalies. Relational theory definitions: schema, tuple instance, functional dependency, legal instance, closure of F. Trivial dependencies, properties of functional dependencies. Armstrong's axioms. Rules: decomposition, union, pseudotransitivity, with Theorem and demonstration. Closure of X and first lemma on the closure with demonstration). Theorem F+=FA with proof. Third normal form, formal definition and alternative definition. Algorithm for computing X+, correctness theorem and proof. Key definition, practical ways to find the keys of a schema, uniqueness check. Decomposition of a schema, definition. Projection of F on the decomposition of a schema, definition. Equivalence between two sets of functional dependencies, definition. Lemma on the closures of two sets of functional dependencies, with proof. Decomposition preserving F, definition. Algorithm for checking if F is preserved. Algorithm for computing X+G. Decomposition with lossless join, definition. Algorithm for checking if a decomposition has a lossless join, with proof. Minimal cover, definition, and steps to compute it. Decomposition algorithm, with extra step for lossless join, and proof.
- Physical organization of a database
  - Heap, sequential, random (hash). Primary and secondary indexes, clustered indexes. Tree organizations: b-trees, b+-trees, b*-trees
- Concurrency management
  - Transactions, schedules, serial schedules, serialization. Locking, binary lock, 2-phase locking, serialization graph, 2PL theorem with proof
 
#### Material
- Books:
  - [B1] J. D. Ullman: Principles of Database & Knowledge-Base Systems, Vol. 1: Classical Database Systems
  - [B2] Lemahieu, W., vanden Broucke, S., & Baesens, B. (2018). Principles of Database Management: The Practical Guide to Storing, Managing and Analyzing Big and Small Data. Cambridge University Press
  - [B2-OA] Online Appendix on relational algebra

- slides: TBA
- exercises: TBA



#### Examination rules (Please **read carefully** before asking already answered questions)

- The course is the first unit of a 2 units 12 credits course "Data Management and Analysis", the second unit will be taught in semester 2 by [Prof. Giuseppe Pirrò](https://ergotid.wordpress.com/).
- To pass the 12 credits course, you have to pass 2 separate examinations, one for unit 1 and one for unit 2; only after passing both examinations you will get the 12 credits; there can be no exception to this, so you cannot take unit 1 only, or unit 2 only and receive 6 credits, that is not possible (and that applies also to Erasmus students).
- To pass the whole examination, you have to pass a written part and an oral part (the written part gives you access to the oral one).
- A passed written examination can be carried forward in the same session, so for example, if you pass the written part in January you can carry it forward and access the oral part in February.
- If you pass the written part and then fail the oral part, in principle, you can still carry forward the written part to the next exam date in the same session (if there is one).
- If I realize that both of your written and oral parts are really poor, I could ask you to re-sit the written part again in the same session, even if you already passed it.
- Between different sessions, you cannot carry forward any passed written part (e.g., you cannot carry forward the written part passed in February to take the oral part in June)
- Students are no longer allowed to sit the exam from remote.
- Erasmus students: unfortunately, Data Management and Analysis is a 12 credits course split into 2 units across 2 semesters, and we cannot record the first (or second) half of the course only.