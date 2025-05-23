---

## title: Software Process and Estimation

## 📌 1. Software Process and Process Models

### ✅ Software Process:

A software process is a structured set of activities required to develop a software system. Activities include:

* **Specification** (Requirements)
* **Design**
* **Implementation** (Coding)
* **Validation** (Testing)
* **Evolution** (Maintenance)

### ✅ Software Process Models:

Models that represent different approaches to software development.

| Model       | Description                                            |
| ----------- | ------------------------------------------------------ |
| Waterfall   | Linear sequence of stages; easy to manage; rigid.      |
| V-Model     | Extension of Waterfall with verification & validation. |
| Incremental | Develop in small functional parts (increments).        |
| Prototyping | Quick mock-ups for feedback before actual build.       |
| Spiral      | Iterative with strong focus on risk analysis.          |
| Agile       | Adaptive, iterative, frequent customer interaction.    |

## 📌 2. Choice of Process Models

### Factors Affecting Choice:

* Project size & complexity
* Risk levels
* Time-to-market constraints
* Customer involvement
* Team experience & skill level
* Budget and deadlines

✔ Agile for rapid changes and customer collaboration
✔ Waterfall for fixed, well-defined requirements
✔ Spiral for high-risk projects
✔ Prototyping when user feedback is key

## 📌 3. Rapid Application Development (RAD)

### Features:

* Focus on rapid prototyping
* Use of CASE tools
* Emphasis on user involvement
* Short development cycles (30–90 days)

### Phases:

* Requirements planning
* User design
* Construction
* Cutover (Deployment)

✅ Useful for tight deadlines and when user feedback is frequent.

## 📌 4. Agile Methods

### Principles:

* Individuals and interactions > tools
* Working software > documentation
* Customer collaboration > contract negotiation
* Responding to change > following a plan

### Agile Techniques:

* Scrum
* Kanban
* Extreme Programming (XP)
* Feature Driven Development (FDD)

## 📌 5. Dynamic System Development Method (DSDM)

Part of Agile family, focuses on:

* Active user involvement
* Frequent delivery
* Integrated testing
* Collaborative and iterative development

### Phases:

* Feasibility & Business Study
* Functional Model Iteration
* Design and Build Iteration
* Implementation

## 📌 6. Extreme Programming (XP)

### XP Practices:

* Pair programming
* Test-Driven Development (TDD)
* Continuous integration
* Refactoring
* Short releases
* Simple design

✅ Works well in dynamic environments with rapidly changing requirements.

## 📌 7. Managing Interactive Processes

### Key Aspects:

* User feedback loops
* Incremental improvements
* Frequent reviews and interface testing
* Usability & user experience management

## 📌 8. Basics of Software Estimation

### Estimation answers:

* How long will it take?
* How much will it cost?
* What effort is required?

### Types:

* **Effort Estimation**: Person-hours/days
* **Cost Estimation**: Money
* **Time Estimation**: Project duration

✅ Accurate estimation helps prevent delays and budget overruns.

## 📌 9. Effort and Cost Estimation Techniques

| Technique                | Description                                  |
| ------------------------ | -------------------------------------------- |
| Expert Judgment          | Based on expert experience.                  |
| Delphi Technique         | Group consensus from multiple experts.       |
| Work Breakdown Structure | Divide project into small tasks and estimate |
| Analogy-Based Estimation | Use past similar project data.               |
| Algorithmic Models       | Use mathematical models like COCOMO.         |

## 📌 10. COSMIC Full Function Points (FFP)

COSMIC = Common Software Measurement International Consortium

Measures the size of software by counting functional user requirements (data movements).

### Types of Data Movements:

* **Entry (E)**: Input from user
* **Exit (X)**: Output to user
* **Read (R)**: Data read from storage
* **Write (W)**: Data written to storage

✅ Language-independent, suitable for real-time, business, and embedded systems.

## 📌 11. COCOMO II – A Parametric Productivity Model

COCOMO II (Constructive Cost Model) is a popular algorithmic model for effort estimation.

### Estimation Formula:

```text
Effort (Person-Months) = A × Size^B × M
```

Where:

* **A** = constant (e.g., 2.94)
* **Size** = in Kilo Source Lines of Code (KSLOC)
* **B** = exponent based on scale factors
* **M** = effort multipliers based on cost drivers

### COCOMO II Models:

* **Application Composition Model**: For GUI-based apps
* **Early Design Model**: When details are scarce
* **Post-Architecture Model**: Detailed estimation using 17 cost drivers

## 🧠 Summary Table

| Topic             | Key Point                                |
| ----------------- | ---------------------------------------- |
| Software Process  | Series of stages in software development |
| Process Models    | Waterfall, Agile, Spiral, etc.           |
| RAD               | Fast, user-driven, short cycles          |
| Agile             | Adaptive, iterative, collaborative       |
| DSDM              | Agile with structure and control         |
| XP                | Technical excellence and rapid response  |
| Effort Estimation | Predict people/time/resources            |
| COSMIC FFP        | Functional sizing based on data movement |
| COCOMO II         | Mathematical model for cost estimation   |
