# 🚀 Advanced Business Process Modeling Portfolio (BPMN 2.0 & EPC)

This portfolio showcases two complex process models developed for an advanced Business Process Management (BPM) course. Both models were graded with a **perfect score of 30/30**, demonstrating mastery in process analysis, standard adherence, and advanced modeling logic.

---

## 🛠 Core Competencies Demonstrated

* **Standards Mastery:** Full adherence to **BPMN 2.0** (for executable processes) and **EPC** (for high-level descriptive modeling).
* **Complex Logic Handling:** Expert use of **Parallel Gateways, Looping Sub-Processes,** and multi-way **Exclusive Gateways (XOR)**.
* **Tool Proficiency:** Expertise in process design, validation, and documentation using **ARIS Cloud**.
* **Business Context:** Ability to model diverse scenarios, from customer-facing transactions (EPC) to manufacturing workflows (BPMN).

---

## 📂 Model Index and Documentation

| Process Name | Standard | Business Context | Key Element Focus |
| :--- | :--- | :--- | :--- |
| **Bicycle Production** | **BPMN 2.0** | Manufacturing/Supply Chain | Parallelism, Looping, Synchronization 
| **Hotel Booking** | **EPC** | Customer Service/E-commerce | Event/Function Sequence, Organizational Handoffs

---

### 1. Model Spotlight: Customized Bicycle Production (BPMN 2.0)

This model illustrates a complex *As-Is* manufacturing process, specifically focusing on optimizing inventory management and production prep.



**Key Modeling Features:**

* **Concurrency:** A **Parallel Gateway** ensures the Warehouse work (parts management) and Production work (area preparation) run simultaneously, minimizing idle time.
* **Iteration:** The iterative "check and re-order" requirement is captured using a **Looping Sub-Process**, the canonical BPMN solution for repeated checks until a condition is met (all parts available).
* **Source File:** The included **.bpmn** file confirms the model's structure is machine-readable and executable.

---

### 2. Model Spotlight: Online Hotel Booking (EPC)

This model focuses on the descriptive flow of a customer transaction, clearly mapping the sequence of steps and key organizational involvement.



**Key Modeling Features:**

* **Flow Logic:** Every step strictly alternates between an **Event** (state change) and a **Function** (activity), demonstrating core EPC principles.
* **Decision Handling:** Multiple **XOR connectors** manage all potential user choices, including the critical abort options, ensuring the process path is defined at every step.
* **Context:** The model clearly links organizational units (Booker, Website, IT Application) to the relevant functions.


---
