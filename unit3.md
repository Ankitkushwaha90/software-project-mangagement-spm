## 📌 1. Objectives of Activity Planning

Activity planning aims to:

* Break down the project into manageable tasks
* Sequence tasks and assign timelines
* Identify dependencies
* Estimate resources (time, cost, people)
* Ensure project completion on time & within budget
* Support monitoring & control

---

## 📌 2. Project Schedules

**Definition:**
A project schedule is a timeline for each task/activity with start and end dates.

**Includes:**

* Task list
* Milestones
* Resource allocation
* Dependencies
* Deliverables

✅ Helps in tracking progress and managing deadlines.

---

## 📌 3. Activities, Sequencing, and Scheduling

* **Activity:** A task or work item required to complete the project.
* **Sequencing:** Identifying the logical order of tasks using dependencies:

  * Finish-to-Start (FS)
  * Start-to-Start (SS)
  * Finish-to-Finish (FF)
  * Start-to-Finish (SF)
* **Scheduling:** Assigning start/end times and resources to each activity.

---

## 📌 4. Network Planning Models

Used to visualize task sequences, dependencies, and timelines.

**Types:**

* CPM (Critical Path Method)
* PERT (Program Evaluation Review Technique)

Represented via **Network Diagrams (Nodes and Arrows)**.

---

## 📌 5. Formulating Network Models

**Steps:**

1. List all activities
2. Identify dependencies
3. Create nodes (activities) and arrows (dependencies)
4. Add duration/time estimates
5. Apply Forward Pass and Backward Pass

---

## 📌 6. Forward Pass Technique

Used to compute **Earliest Start (ES)** and **Earliest Finish (EF)** times.

**Formula:**

* ES = Max(EF of predecessor)
* EF = ES + Duration

✅ Determines project start to end timeline.

---

## 📌 7. Backward Pass Technique

Used to compute **Latest Start (LS)** and **Latest Finish (LF)** times.

**Formula:**

* LF = Min(LS of successor)
* LS = LF - Duration

✅ Helps in calculating float/slack and identifying the critical path.

---

## 📌 8. Critical Path Method (CPM)

**Definition:**
The longest duration path through a project with zero float.

**Importance:**

* Determines minimum project duration
* Activities on this path are critical
* Delays here affect the entire project

**Slack:**

* Slack = LS - ES or LF - EF
* If slack = 0 → Critical Activity

---

## 📌 9. Risk Management

### 📍 a) Risk Identification

Find possible risks like:

* Technical risks
* Cost & schedule risks
* Human resource risks
* External risks

### 📍 b) Risk Assessment

Evaluate:

* Probability (Low/Medium/High)
* Impact (Low/Medium/High)

**Risk Exposure** = Probability × Impact

### 📍 c) Risk Planning

Plan for:

* Avoidance (change the plan)
* Mitigation (reduce impact/probability)
* Contingency (prepare backup)

### 📍 d) Risk Monitoring

Continuously watch for new or changing risks during project lifecycle.

---

## 📌 10. PERT (Program Evaluation and Review Technique)

Used for uncertain durations. Involves 3-time estimates:

* Optimistic (O)
* Most Likely (M)
* Pessimistic (P)

**Expected Time (TE):**

* TE = (O + 4M + P) / 6

✅ Useful for R\&D, innovation, and uncertain projects

---

## 📌 11. Monte Carlo Simulation

**Purpose:**
To analyze risk and uncertainty in schedules and cost estimates using probability distribution.

**How it works:**

* Use random sampling (thousands of simulations)
* Create a range of possible outcomes
* Identify probabilities for schedule delays or cost overruns

✅ Useful in complex risk analysis

---

## 📌 12. Resource Allocation

**Key Aspects:**

* Assign right resources to right tasks
* Avoid overallocation or idle time
* Track availability, cost, and skill level
* Use tools like Resource Histogram

---

## 📌 13. Creation of Critical Paths

**Steps:**

1. List activities and dependencies
2. Estimate duration
3. Build network diagram
4. Apply Forward Pass & Backward Pass
5. Identify the critical path (longest path with zero float)

---

## 📌 14. Cost Schedules

Shows the **cost vs. timeline** view of the project.

**Components:**

* Planned Value (PV)
* Earned Value (EV)
* Actual Cost (AC)

Used in **Earned Value Management (EVM):**

* Cost Variance (CV) = EV - AC
* Schedule Variance (SV) = EV - PV

✅ Helps monitor budget and time performance

---

## 🧠 Summary Table

| Concept               | Description                                   |
| --------------------- | --------------------------------------------- |
| Activity Planning     | Structuring, sequencing, and scheduling tasks |
| Network Models        | CPM and PERT used to visualize tasks          |
| Forward/Backward Pass | Techniques to calculate ES/EF and LS/LF       |
| Critical Path         | Longest path with zero slack                  |
| Risk Management       | Identify, assess, plan, and monitor risks     |
| PERT                  | Time estimates using probability              |
| Monte Carlo           | Simulation-based risk modeling                |
| Resource Allocation   | Managing team and tools efficiently           |
| Cost Schedules        | Managing time vs. cost effectively            |
