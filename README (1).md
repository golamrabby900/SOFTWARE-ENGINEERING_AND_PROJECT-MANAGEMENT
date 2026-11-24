# Software Engineering Design – Mid-Term Question Paper

---

## Student Information

| Field | Details |
|---|---|
| **Student Name** | Golam Rabbi |
| **Student ID** | IT24025 |
| **Department** | Department of Information and Communication Technology |
| **Course** | Software Engineering Design |
| **BNQF Level** | Level 6 |
| **Assessment Type** | OBE-Based (Outcome-Based Education) |
| **Total Marks** | 40 |
| **Duration** | 1 Hour |
| **Date** | 24 November 2026 |

---

## Exam Overview

This mid-term examination is developed following **OBE (Outcome-Based Education)** principles aligned with the **Bangladesh National Qualifications Framework (BNQF) Level 6** standard.

- **Cognitive Domain:** Knowledge & Understanding
- **Bloom's Taxonomy Levels:** L1 (Remember) · L2 (Understand)
- All questions are mapped to **Course Outcomes (CO)**

---

## Exam Structure

| Section | Type | Questions | Marks |
|---|---|---|---|
| **Section A** | Short Answer — Answer ALL | Q1 – Q5 | 20 |
| **Section B** | Structured — Answer any TWO | Q6 – Q8 | 20 |
| | **Total** | | **40** |

**Instructions:**
- Answer **ALL** questions from Section A and any **TWO** from Section B.
- Write clearly and concisely. Marks will be deducted for irrelevant content.
- Each question carries the marks indicated in [ ]. Time allocation: ~1.5 min per mark.

---

## Questions

---

### Section A — Short Answer Questions [20 Marks] · Answer ALL

---

**Q1. [4 Marks] | Bloom: L1 – Remember | CO1**

Define *software design* and briefly explain the two main steps of the design process: **Architectural Design** and **Detailed Design**. What is the output of the design process?

---

**Q2. [4 Marks] | Bloom: L2 – Understand | CO2**

Explain the concepts of **coupling** and **cohesion** in software design. Why do software engineers aim for *low coupling* and *high cohesion*?

---

**Q3. [4 Marks] | Bloom: L1 – Remember | CO3**

State the *intent* of each of the following GoF Design Patterns:

- (a) **Strategy Pattern**
- (b) **Adapter Pattern**
- (c) **Facade Pattern**
- (d) **Command Pattern**

---

**Q4. [4 Marks] | Bloom: L1 – Remember | CO4**

List and briefly describe **four architectural styles** in software architecture. Write one sentence describing the key idea of each:
*Layered, MVC (Model-View-Controller), Event-Based, and Pipes & Filters.*

---

**Q5. [4 Marks] | Bloom: L2 – Understand | CO5**

Distinguish between **Single Table Inheritance** and **Class Table Inheritance** in Object-Relational Mapping (ORM). Mention *one benefit* and *one drawback* of each approach.

---

### Section B — Structured Questions [20 Marks] · Answer any TWO (10 marks each)

---

**Q6. Design Quality Metrics [10 Marks] | Bloom: L2 – Understand | CO2**

- (a) **[2]** Define the CK metric *CBO (Coupling Between Object Classes)*. What does it measure and how is it calculated?
- (b) **[3]** Define *LCOM2 (Lack of Cohesion of Methods)*. Write its formula and explain what LCOM2 = 0 and LCOM2 = 1 each indicate about a class.
- (c) **[3]** Define *WMC (Weighted Methods per Class)*. Explain how *McCabe's complexity* is used to calculate C_i. Which control structures (e.g., `if`, `for`, `while`) each count as one condition?
- (d) **[2]** Write the formula for *RFC (Response For a Class)* and explain why it is a useful complexity measure.

---

**Q7. GoF Design Patterns – Structure and Benefits [10 Marks] | Bloom: L1–L2 | CO3**

- (a) **[3]** Explain the *Template Method* pattern. State its intent and describe the roles of **AbstractClass** and **ConcreteClass**.
- (b) **[3]** Explain the *Composite* pattern. What problem does it solve? Name and describe the four participant roles: **Component, Leaf (Primitive), Composite, Client**.
- (c) **[2]** State *two benefits* and *one liability* of the **Strategy** pattern.
- (d) **[2]** Classify each of the following as *Creational*, *Structural*, or *Behavioral*:
  **Singleton, Adapter, Observer, Facade, Builder**

---

**Q8. Enterprise Application Architecture (EAA) Patterns [10 Marks] | Bloom: L2 – Understand | CO5**

- (a) **[3]** Describe the *Domain Model* pattern. What type of business logic is it best suited for? How does it differ from a simple data-centric approach?
- (b) **[3]** Explain the *Data Mapper* pattern (also known as Repository / DAO). What is the key benefit of separating in-memory objects from the database layer?
- (c) **[2]** Compare *Page Controller* and *Front Controller* as presentation logic patterns. When is each more appropriate?
- (d) **[2]** Explain the purpose of *Foreign Key Mapping* in ORM. Give a concrete example of a **One-to-Many** relationship and describe how it is mapped to database tables.

---

## Question–CO–Bloom Mapping

| Question | Topic | Marks | CO | Bloom's Level | Cognitive Domain |
|---|---|---|---|---|---|
| Q1 | Software design definition & process steps | 4 | CO1 | L1 – Remember | Knowledge |
| Q2 | Coupling & Cohesion | 4 | CO2 | L2 – Understand | Understanding |
| Q3 | GoF Pattern intents (Strategy, Adapter, Facade, Command) | 4 | CO3 | L1 – Remember | Knowledge |
| Q4 | Architectural Styles (Layered, MVC, Event-Based, Pipes & Filters) | 4 | CO4 | L1 – Remember | Knowledge |
| Q5 | Single Table vs. Class Table Inheritance (ORM) | 4 | CO5 | L2 – Understand | Understanding |
| Q6 | OO Metrics: CBO, LCOM2, WMC (McCabe), RFC | 10 | CO2 | L2 – Understand | Understanding |
| Q7 | Template Method, Composite, Strategy, Pattern Classification | 10 | CO3 | L1–L2 | Knowledge / Understanding |
| Q8 | Domain Model, Data Mapper, Page/Front Controller, Foreign Key Mapping | 10 | CO5 | L2 – Understand | Understanding |
| | **Total** | **40** | CO1–CO5 | L1–L2 | Knowledge & Understanding |

---

## Course Outcomes (CO)

| CO | Statement | Bloom's Level |
|---|---|---|
| **CO1** | Recall and describe the fundamental concepts of software design including the design process, its steps, and expected outcomes. | L1 – Remember |
| **CO2** | Explain and distinguish software design quality attributes including coupling, cohesion, and OO metrics (CBO, LCOM, WMC, RFC). | L2 – Understand |
| **CO3** | Identify and describe GoF design patterns (Creational, Structural, Behavioral), their intent, structure, benefits, and liabilities. | L1–L2 |
| **CO4** | Recall and explain major software architectural styles including Layered, MVC, Event-Based, Blackboard, and Pipes & Filters. | L1 – Remember |
| **CO5** | Understand and describe Enterprise Application Architecture (EAA) patterns for business logic, ORM mapping, and presentation layers. | L2 – Understand |

---

## Topics Covered

### Design Fundamentals
- What is software design?
- Architectural design vs. detailed design
- Outcomes of the design process
- Modularity, decomposition, abstraction, encapsulation, information hiding

### Design Quality Metrics (CK Suite)
- **Coupling** – CBO (Coupling Between Object Classes)
- **Cohesion** – LCOM, LCOM2, LCOM3
- **Complexity** – WMC (McCabe's Cyclomatic Complexity), RFC (Response For a Class)

### Software Architecture Styles
- Layered Architecture
- Event-Based Architecture
- Model-View-Controller (MVC)
- Blackboard / Repository
- Pipes and Filters

### GoF Design Patterns

| Creational | Structural | Behavioral |
|---|---|---|
| Singleton | Adapter | Strategy |
| Builder | Composite | Template Method |
| Factory Method | Facade | Command |
| Abstract Factory | Bridge | Observer |
| Prototype | Decorator | Iterator |
| | Flyweight | Mediator |
| | Proxy | State |

### Enterprise Application Architecture (EAA) Patterns
- **Business Logic:** Domain Model, Service Layer
- **ORM Mapping:** Data Mapper (DAO/Repository), Identity Field, Foreign Key Mapping (1-1, 1-N, N-N), Single Table Inheritance, Class Table Inheritance, Concrete Table Inheritance, Association Table Mapping
- **Presentation Logic:** MVC, Page Controller, Front Controller, Template View, Transform View

---

## OBE & BNQF Alignment

This question paper is designed in compliance with:

- **OBE (Outcome-Based Education):** Every question is explicitly mapped to a Course Outcome (CO).
- **BNQF Level 6:** Aligns with the cognitive expectations of an undergraduate degree-level qualification in Bangladesh.
- **Bloom's Taxonomy:** Questions target **L1 (Remember)** and **L2 (Understand)** — appropriate cognitive levels for a mid-term examination.

---

## Source Material

| Reference | Author(s) |
|---|---|
| *Software Engineering: Theory & Practice* | S. L. Pfleeger |
| *Introduction to Software Engineering* | I. Sommerville |
| *IEEE SWEBOK v3 – Software Engineering Body of Knowledge* | IEEE |
| *Agile Software Development: Principles, Patterns, and Practices* (2003) | R. C. Martin |
| *Design Patterns: Elements of Reusable OO Software* (GoF, 1995) | Gamma, Helm, Johnson, Vlissides |
| *Patterns of Enterprise Application Architecture* | M. Fowler |
| *An Introduction to Software Architecture* (1993) | Garlan & Shaw |
| CK Metrics Suite | Chidamber & Kemerer |
| *Structured Design*, IBM Systems Journal (1974) | Stevens, Myers & Constantine |

---

## Repository Structure

```
.
├── README.md                    ← This file (full assignment documentation)
└── question_paper.html          ← Printable question paper
```

### How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/golamrabby/SE-Design-MidTerm.git
   ```
2. Open `question_paper.html` in any browser.
3. Use **Print → Save as PDF** for a printable copy.

---

*Department of Information and Communication Technology | BNQF Level 6 | OBE-Based Assessment*
