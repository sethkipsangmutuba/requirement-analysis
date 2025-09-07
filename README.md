# requirement-analysis
Repository for documenting and analyzing requirements for a Booking Management System as part of the ALX project.

# Requirement Analysis in Software Development

Welcome to the **Requirement Analysis Project** repository.  
This repository is designed to document and analyze requirements for a **Booking Management System**, simulating real-world software development practices.  

## Purpose of This Repository
The main purpose of this repository is to:
- Demonstrate the **Requirement Analysis** phase of the Software Development Lifecycle (SDLC).
- Provide a structured blueprint for understanding and documenting software requirements.
- Prepare for future development by ensuring clarity, precision, and alignment between stakeholders and developers.

## What This Repository Contains
As you go through the project, this repository will include:
- Explanations of **Requirement Analysis** and its role in SDLC.
- Documentation of **Functional and Non-Functional Requirements**.
- **Use Case Diagram** for the Booking Management System.
- Structured breakdown of **key activities** in Requirement Analysis.
- **Acceptance Criteria** examples for core features.

## What is Requirement Analysis?

**Requirement Analysis** is the discipline of discovering, eliciting, documenting, validating, and managing the needs and constraints of stakeholders for a software system. It translates business goals into clear, testable, and traceable requirements that guide design, implementation, and verification.

At its core, Requirement Analysis answers three questions:
1. **What problem are we solving?** (business goals, scope, assumptions)
2. **For whom are we solving it?** (stakeholders, users, external systems)
3. **What must the system do and how well must it perform?** (functional and non-functional requirements)

### Objectives
- **Alignment:** Establish a shared understanding between business stakeholders, product, engineering, QA, and operations.
- **Clarity:** Convert ambiguous ideas into **unambiguous**, **testable**, and **prioritized** requirements.
- **Risk reduction:** Surface constraints, dependencies, and edge cases early, when changes are cheaper.
- **Traceability:** Create a chain from business objectives → features → detailed requirements → tests → releases.

### Typical Deliverables
- Problem statement and success metrics
- Stakeholder and actor definitions
- Glossary and domain model (business entities, relationships)
- **Functional Requirements** (capabilities, behaviors, rules, workflows)
- **Non-Functional Requirements** (performance, security, availability, compliance, usability)
- Acceptance criteria and examples (Given/When/Then)
- Use cases / user stories / scenarios
- Prototypes or diagrams (e.g., use-case, context, data flow)
- Traceability matrix (requirements ↔ tests)

### Quality Criteria for Good Requirements
- **Correct** (reflect stakeholder intent)  
- **Complete** (cover necessary scenarios and constraints)  
- **Consistent** (no conflicts)  
- **Feasible** (achievable within constraints)  
- **Unambiguous** (single interpretation)  
- **Verifiable** (testable/measureable)  
- **Traceable** (linkable to business goals and tests)  
- **Prioritized** (MoSCoW or similar)

### Why Requirement Analysis Matters in the SDLC
Requirement Analysis is foundational to every subsequent SDLC phase:

- **Planning & Estimation:** Reliable requirements enable realistic timelines, budgets, and resource plans.
- **Architecture & Design:** Clear behaviors and quality attributes drive architectural choices (e.g., availability targets influence replication and failover strategies).
- **Implementation:** Developers code against well-defined inputs/outputs, states, and constraints—reducing rework.
- **Testing:** Acceptance criteria and non-functional targets become the basis for test cases, performance tests, and definition of done.
- **Deployment & Operations:** Operational requirements (SLOs, logging, monitoring, compliance) are specified up front, avoiding production gaps.
- **Change Management:** Traceability enables impact analysis when requirements evolve (inevitable in iterative/agile delivery).

### Example (Booking Management System)
- **Functional:** “A customer can search available rooms by location, date range, and occupancy; the system must prevent double-booking at confirmation time.”
- **Non-Functional:** “Search results must return within **≤2s** for 95% of requests under **10k** concurrent users; payment flows must be **PCI-DSS compliant**; availability must be **99.9%** monthly.”

> In iterative/agile contexts, Requirement Analysis is **continuous**: you refine user stories, acceptance criteria, and models as understanding grows—while preserving traceability and quality standards.

## Why is Requirement Analysis Important?

Requirement Analysis is the **cornerstone of successful software development**. Without clearly defined and validated requirements, projects risk misalignment, scope creep, budget overruns, and system failures. Its importance in the Software Development Life Cycle (SDLC) can be understood through the following key reasons:

### 1. Ensures Alignment with Business and User Goals
- Requirements act as the **bridge between business needs and technical implementation**.  
- By capturing stakeholder expectations, Requirement Analysis ensures the system delivers **real value** to users and organizations.  
- Example: In a booking management system, identifying that customers need **real-time availability checks** prevents wasted effort on irrelevant features.

### 2. Reduces Costly Errors and Rework
- Industry studies (e.g., Standish CHAOS reports) show that fixing a defect in the **requirements phase** is 10x–100x cheaper than fixing it after deployment.  
- A clear requirement specification minimizes ambiguity, **preventing rework, delays, and cost overruns** later in the SDLC.  
- Example: Specifying “search results must load within 2 seconds” early avoids late-stage performance fixes.

### 3. Provides a Foundation for Design, Testing, and Validation
- Requirements drive **architecture, design, and coding decisions**.  
- They form the basis for **test cases, acceptance criteria, and quality assurance**.  
- Example: Non-functional requirements like **security (PCI-DSS compliance)** or **availability (99.9%)** guide both system design and QA strategy.

### 4. Supports Traceability and Change Management
- Well-structured requirements enable teams to **track dependencies** across design, code, and tests.  
- When requirements evolve, traceability makes it easier to **assess the impact** of changes and maintain system integrity.  
- Example: Adding “multi-currency support” can be traced through related features (payment processing, reporting, UI changes).

### 5. Enhances Communication and Collaboration
- Requirement documents and diagrams serve as a **single source of truth** for stakeholders—business, developers, testers, and operations.  
- This shared understanding reduces misunderstandings and fosters smoother collaboration.  
- Example: A **use-case diagram** visually aligns product owners and engineers on user interactions.

---

✅ In short: Requirement Analysis is not just a preliminary step—it is the **foundation for planning, building, and validating software systems**. Projects with strong requirement practices consistently achieve **higher success rates** in terms of quality, cost, and stakeholder satisfaction.


## Key Activities in Requirement Analysis

Requirement Analysis is not a single step—it is a structured process made up of interconnected activities. Each activity ensures that requirements are **identified, clarified, documented, and validated** before moving to design and development. The five key activities are:

### 1. Requirement Gathering
- Collects raw requirements from stakeholders such as clients, end-users, business analysts, and domain experts.  
- Techniques include **interviews, questionnaires, workshops, brainstorming, and document reviews**.  
- Example: In a booking management system, gathering inputs like “users should book a room online” or “admins must view booking reports.”

### 2. Requirement Elicitation
- Goes beyond gathering—focuses on clarifying, probing, and resolving conflicts in requirements.  
- Involves active engagement with stakeholders to uncover **hidden, implied, or conflicting needs**.  
- Techniques include **prototyping, role-playing, and observation of real workflows**.  
- Example: Determining whether “real-time booking” means immediate confirmation or a delayed email notification.

### 3. Requirement Documentation
- Converts gathered and elicited requirements into **formal, structured documentation** (e.g., Software Requirement Specification – SRS).  
- Ensures requirements are **clear, concise, unambiguous, and testable**.  
- Uses formats like **user stories, use-case diagrams, process flows, and requirement matrices**.  
- Example: Documenting “The system shall allow a user to filter bookings by date and room type.”

### 4. Requirement Analysis and Modeling
- Involves **analyzing dependencies, feasibility, and priorities** of requirements.  
- Identifies overlaps, gaps, and inconsistencies.  
- Uses **models and diagrams** such as Entity-Relationship Diagrams (ERDs), Data Flow Diagrams (DFDs), and Use Case Models to visualize the system.  
- Example: Modeling the interaction between “Customer → Booking System → Payment Gateway.”

### 5. Requirement Validation
- Ensures that documented requirements accurately represent stakeholder needs and align with business goals.  
- Involves **reviews, walkthroughs, inspections, and acceptance criteria checks**.  
- Helps prevent costly rework by catching issues early.  
- Example: Validating that the requirement “system must process payments securely” meets compliance standards like **PCI-DSS**.

---

✅ Together, these activities create a **systematic approach** to defining and refining requirements. They help ensure the software being built is **feasible, aligned with business goals, user-centered, and free of ambiguities**.



## Types of Requirements

Requirements in software development are broadly classified into two categories: **Functional Requirements** and **Non-functional Requirements**. Both are essential to building a reliable, efficient, and user-friendly system. Below, we explore their definitions and examples in the context of a **Booking Management System**.

---

### 1. Functional Requirements
Functional requirements define **what the system should do**. They describe the specific behaviors, features, and operations the software must perform to meet user needs and business objectives.  

#### Key Characteristics:
- Directly tied to **system functionality**.  
- Represented as **features, interactions, or services**.  
- Must be **testable and verifiable**.  

#### Examples for the Booking Management System:
- The system shall allow users to **search for available hotels** based on location, dates, and price range.  
- The system shall allow users to **create an account, log in, and manage profiles**.  
- The system shall enable customers to **book a room online** and receive confirmation via email/SMS.  
- The system shall allow managers to **update hotel details** (e.g., room availability, pricing, and amenities).  
- The system shall integrate with a **third-party payment gateway** to process payments securely.  
- The system shall provide an **admin dashboard** to view booking reports and analytics.  

---

### 2. Non-functional Requirements
Non-functional requirements (NFRs) define **how the system should perform** rather than what it should do. They focus on the **quality attributes** of the software, ensuring scalability, usability, performance, and compliance.

#### Key Characteristics:
- Address **system constraints and quality goals**.  
- Support functional requirements by defining **standards and benchmarks**.  
- Often expressed as **measurable criteria** (e.g., response time, availability).  

#### Examples for the Booking Management System:
- **Performance**: The system shall return hotel search results within **2 seconds** for 95% of queries.  
- **Scalability**: The system shall support up to **10,000 concurrent users** during peak booking periods.  
- **Reliability**: The system shall have an uptime of **99.9%** to ensure availability for global users.  
- **Security**: All payment transactions shall comply with **PCI-DSS standards** and use **SSL encryption**.  
- **Usability**: The booking interface shall be accessible and intuitive, with support for **mobile and desktop platforms**.  
- **Maintainability**: The system shall allow administrators to apply updates with **less than 30 minutes of downtime**.  

---

✅ Together, **functional requirements** define *what the system must do*, while **non-functional requirements** ensure *the system does it well*. Both are crucial in building a successful, user-centered booking management solution.


## Use Case Diagrams

### What is a Use Case Diagram?
A **Use Case Diagram** is a visual representation of the interactions between **users (actors)** and the **system**. It helps illustrate the functional requirements of a system by showing the different ways users can interact with it.  

In software engineering, use case diagrams are part of the **Unified Modeling Language (UML)** and are particularly useful during the **requirement analysis phase**. They ensure that both developers and stakeholders share a common understanding of the system’s scope and functionality.  

---

### Benefits of Use Case Diagrams
- **Clarity**: Simplifies complex system interactions into an easy-to-understand visual model.  
- **Communication**: Serves as a bridge between technical teams and non-technical stakeholders.  
- **Validation**: Ensures that all required interactions are identified and documented.  
- **Scope Definition**: Helps in defining system boundaries and preventing scope creep.  

---

### Use Case Diagram for Booking Management System
Below is an example use case diagram for the booking system.  

#### **Actors:**
- **Customer**: Searches hotels, makes bookings, manages profile, and processes payments.  
- **Hotel Manager**: Manages hotel details (availability, pricing, amenities).  
- **Admin**: Monitors the system, generates reports, and manages users.  
- **Payment Gateway (External System)**: Handles secure online payments.  

#### **Use Cases:**
- Search Hotels  
- View Hotel Details  
- Book Room  
- Make Payment  
- Receive Booking Confirmation  
- Manage Profile  
- Update Hotel Information  
- View Reports  

---

### Diagram
The diagram has been designed using **Draw.io** and exported as `alx-booking-uc.png`.

![Booking System Use Case Diagram](./alx-booking-uc.png)

---

✅ This diagram illustrates the high-level interactions between different actors and the booking management system, providing a clear visual overview of functional requirements.

## Acceptance Criteria

### What are Acceptance Criteria?
**Acceptance Criteria (AC)** are predefined conditions that a software product or feature must meet in order to be accepted by the client, stakeholder, or end-user. They serve as a **contract** between the development team and stakeholders, ensuring that all parties have a shared understanding of what constitutes a "completed" and "successful" feature.  

Acceptance Criteria are typically written in clear, testable, and unambiguous language so they can be used as a basis for **testing, validation, and sign-off**.  

---

### Importance of Acceptance Criteria in Requirement Analysis
1. **Clarity & Alignment**: Ensures developers, testers, and stakeholders share the same understanding of the feature.  
2. **Testability**: Provides a foundation for writing test cases and verifying that the feature works as intended.  
3. **Scope Management**: Prevents scope creep by defining the exact boundaries of a requirement.  
4. **Quality Assurance**: Helps ensure that the delivered product meets user expectations and business goals.  

---

### Example: Acceptance Criteria for Checkout Feature
Below is an example of acceptance criteria for the **Checkout feature** in a hotel booking management system.  

**Feature**: Checkout  

**Acceptance Criteria:**  
- ✅ The system must allow a customer to proceed to checkout only if a room has been selected and added to the booking cart.  
- ✅ The system must display the booking summary, including hotel name, room type, check-in/check-out dates, and total cost.  
- ✅ The customer must be able to select a payment method (e.g., credit/debit card, PayPal).  
- ✅ The system must securely process the payment through the integrated payment gateway.  
- ✅ The customer must receive a confirmation page and booking reference number after successful payment.  
- ✅ An email confirmation with booking details must be automatically sent to the customer within 5 minutes of completing the transaction.  
- ✅ If the payment fails, the system must notify the customer and allow them to retry or select another payment method.  

---

✅ These criteria ensure that the checkout process is functional, secure, and user-friendly while meeting both business and customer expectations.



