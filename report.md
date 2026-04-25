# Software Development Models – Assignment 01

## Task 1 – Model Explanations

### 1. Waterfall Model
**What it is:**  
A linear, sequential model where each phase (requirements → design → implementation → testing → deployment → maintenance) must be completed before the next begins. Changes are difficult once a phase is finished.

**When to use it:**  
Projects with fixed, clear requirements that will not change, such as government or banking systems.

**Real-world example:**  
NASA’s Space Shuttle software — requirements are stable and safety is critical.

---

### 2. Agile Methodology
**What it is:**  
A mindset that delivers software in small, incremental releases (1–4 weeks). It prioritizes customer feedback and adapting to change over following a rigid plan.

**When to use it:**  
Projects with unclear or constantly changing requirements, like startups or internet products.

**Real-world example:**  
Spotify — releases new features every two weeks based on user feedback.

---

### 3. Scrum Framework
**What it is:**  
A concrete framework under Agile with fixed roles (Product Owner, Scrum Master, Team), fixed events (daily stand-up, sprint planning, review, retrospective), and fixed timeboxes called Sprints (1–4 weeks).

**When to use it:**  
Projects that need a regular rhythm, close team collaboration, and clear responsibility.

**Real-world example:**  
Google uses Scrum in many internal teams to develop Gmail and Google Drive.

---

### 4. Kanban
**What it is:**  
A visual workflow method using a board (To Do / Doing / Done). It limits work-in-progress (WIP) and has no fixed iterations — you release whenever a task is completed.

**When to use it:**  
Maintenance or operations projects where requirements come randomly, or support teams.

**Real-world example:**  
Toyota production line (origin), and now many IT operations teams use Kanban to manage bug fixes.

---

### 5. DevOps
**What it is:**  
A culture and set of practices that combines development and operations. It focuses on automation (CI/CD), fast deployment, and continuous monitoring to ship code reliably and quickly.

**When to use it:**  
Cloud-native or microservices projects that need frequent releases and high stability.

**Real-world example:**  
Netflix — deploys thousands of times per day with automated testing, deployment, and monitoring.

---

### 6. Spiral Model
**What it is:**  
A risk-driven model that combines waterfall, prototyping, and risk analysis. Each “loop” goes through: define goals → identify risks → develop prototype → review.

**When to use it:**  
Large, complex, high-risk projects such as military, aerospace, or large enterprise systems.

**Real-world example:**  
Microsoft used the Spiral model for early large-scale system projects to manage risks before they became failures.

---

## Task 2 – Comparison Table

| Model | Flexibility to changing requirements | Customer involvement | Documentation level | Best suited project type |
|-------|--------------------------------------|----------------------|---------------------|---------------------------|
| Waterfall | Very low | Low (involved only at the beginning) | High | Fixed-requirement, safety-critical systems |
| Agile | Very high | High (every iteration) | Low | Fast-changing internet / startup products |
| Scrum | High | High (every Sprint review) | Medium | Team-based projects with fixed rhythm |
| Kanban | Very high | Medium (on-demand feedback) | Low | Maintenance / support work with random requests |
| DevOps | High | Medium (more focus on automation & monitoring) | Medium (scripts & configs) | Cloud / microservices needing frequent releases |
| Spiral | Medium (changes allowed but risk evaluated) | Medium (review after each loop) | High | Large, high-risk, long-cycle projects |