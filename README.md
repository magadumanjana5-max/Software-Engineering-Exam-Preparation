# Software-Engineering-Exam-Preparation

## Important 5-Mark Questions and Answers

### 1. What is Software Engineering? Explain its importance.

**Answer:**

Software Engineering is the systematic, disciplined, and measurable application of engineering principles to develop, operate, and maintain software.

- **Need:** Software projects can be large, complex, expensive, and may change over time.
- **Importance:** It improves software quality, cost control, delivery time, reliability, maintainability, security, and customer satisfaction.
- **Activities:** Requirement analysis, design, coding, testing, deployment, project management, and maintenance.
- **Discipline:** It uses standards, models, methods, tools, documentation, and professional practices.

**Conclusion:** Software Engineering converts informal ideas into a dependable software system while managing technical and organizational risks.

### 2. Explain the Software Development Life Cycle (SDLC).

**Answer:**

The Software Development Life Cycle (SDLC) is a systematic process for building software from initial need to final maintenance.

1. **Requirement analysis:** Understand and document what users need.
2. **Feasibility study:** Check technical, economic, and operational feasibility.
3. **Design:** Create software architecture, database, modules, and interfaces.
4. **Implementation:** Write and integrate program code.
5. **Testing:** Detect defects and verify that requirements are satisfied.
6. **Deployment:** Install and release the system for users.
7. **Maintenance:** Fix defects and improve or adapt the system.

**Conclusion:** SDLC provides process control and helps reduce cost and project failure.

### 3. Compare the Waterfall and Spiral models.

**Answer:**

| Waterfall Model | Spiral Model |
|---|---|
| Sequential and phase-oriented | Iterative and risk-oriented |
| Works well with clear, stable requirements | Suitable for changing or uncertain requirements |
| Requirements are gathered at the beginning | Requirements become more detailed in iterations |
| Testing is performed mainly after implementation | Testing and review occur in every cycle |
| Suitable for small or simple projects | Suitable for large and complex projects |
| Lower process cost but difficult to change | More expensive and requires risk expertise |

**Conclusion:** Use Waterfall for stable requirements and Spiral when risk analysis and gradual development are important.

### 4. What are functional and non-functional requirements?

**Answer:**

**Functional requirements** describe operations or behavior the system must provide.

- Examples: Login, search, registration, report generation, and payment processing.
- They describe **what** the system should do.

**Non-functional requirements** describe quality and operational constraints.

- Examples: Performance, usability, security, reliability, scalability, portability, and maintainability.
- They describe **how well** the system performs its functions.

Both are essential because correct functions may still fail if the system is slow, insecure, or difficult to use.

### 5. What is Software Requirement Specification (SRS)?

**Answer:**

An SRS is a formal document that describes the intended behavior and constraints of a software system.

- Identifies the system scope and objectives.
- Defines functional and non-functional requirements.
- Describes users, assumptions, interfaces, and constraints.
- Acts as an agreement between users and developers.
- Helps in design, estimation, testing, and future maintenance.

A good SRS should be complete, consistent, clear, verifiable, unambiguous, and modifiable. It reduces misunderstanding and prevents unnecessary rework.

### 6. Explain cohesion and coupling in software design.

**Answer:**

**Cohesion** is the degree of relationship between elements within one module.

- High cohesion means a module performs one closely related task.
- It improves readability, reuse, testing, and maintainability.

**Coupling** is the degree of dependency between two modules.

- Low coupling means modules depend on one another as little as possible.
- It reduces the effect of changes in one module on another.

**Design goal:** High cohesion and low coupling.

**Example:** An authentication module should contain related login and password functions, while avoiding direct dependence on reporting or database presentation code.

### 7. What is modularization? What are its advantages?

**Answer:**

Modularization is the division of a software system into independent, well-defined modules.

- Each module has a specific responsibility and interface.
- Modules can communicate through controlled parameters or APIs.

**Advantages:**

- Easier understanding and implementation.
- Parallel development by different teams.
- Better testing and debugging.
- Improved reuse and maintainability.
- A fault in one module may affect less of the overall system.
- Simple modules are easier to replace or enhance.

**Conclusion:** Modularization reduces complexity and supports independent software development.

### 8. Explain black-box and white-box testing.

**Answer:**

| Black-Box Testing | White-Box Testing |
|---|---|
| Tests behavior from the user's interface | Tests internal code and logic |
| Internal implementation is not required | Source code and structure are known |
| Based on specifications and inputs/outputs | Based on paths, branches, and statements |
| Examples: equivalence partitioning, boundary-value analysis | Examples: statement, branch, and path coverage |
| Often performed by testers | Often performed by developers |

**Conclusion:** Black-box testing verifies **what** the system does, while white-box testing verifies **how** it is implemented. Both complement one another.

### 9. What are unit, integration, system, and acceptance testing?

**Answer:**

- **Unit testing:** Tests individual functions or modules in isolation.
- **Integration testing:** Checks communication and data exchange between modules.
- **System testing:** Tests the complete system against specified requirements.
- **Acceptance testing:** Confirms that the system is acceptable to the customer or end user.

Examples of system-level checks include security, performance, usability, recovery, and compatibility. Acceptance testing is often performed in a staging or real environment before final deployment.

**Conclusion:** Testing progresses from small components to the complete user-accepted system.

### 10. Define software maintenance and explain its types.

**Answer:**

Software maintenance is modification of software after delivery to correct defects or improve the system.

- **Corrective:** Fixes errors found during use.
- **Adaptive:** Updates software for a new platform, hardware, OS, database, or business environment.
- **Perfective:** Improves performance, usability, or adds enhancements.
- **Preventive:** Improves structure or updates components to prevent future defects.

Maintenance is often costly because legacy code may have poor documentation, changing teams, or changing requirements. Good design and documentation reduce this cost.

### 11. What is a DFD? Explain its levels and symbols.

**Answer:**

A Data Flow Diagram (DFD) is a graphical model showing how data moves through a system.

**Common symbols:**

- **Process:** A circle or rounded box that transforms data.
- **Data flow:** An arrow showing the movement of data.
- **External entity:** A source or destination outside the system.
- **Data store:** A place where data is stored, such as a database or file.

**Levels:**

- **Level 0:** One process represents the entire system and its major external entities.
- **Level 1:** Shows major processes and data flows.
- **Next levels:** Decompose processes into more detailed subprocesses.

DFD is useful for understanding system boundaries, inputs, outputs, storage, and processing logic.

### 12. What is UML? Explain use-case and class diagrams.

**Answer:**

Unified Modeling Language (UML) is a standard language for specifying, visualizing, and documenting software designs.

**Use-case diagram:**

- Shows users (actors) and functions (use cases).
- Represents system behavior from a user's viewpoint.
- Useful for requirement communication and scope identification.

**Class diagram:**

- Shows classes, attributes, operations, and relationships.
- Relationships include association, inheritance, aggregation, and composition.
- Useful for object-oriented design and database mapping.

**Conclusion:** Use-case diagrams describe external interaction, while class diagrams describe the system's static structure.

### 13. What are verification and validation?

**Answer:**

- **Verification:** Checks whether the product is being built correctly.
- **Validation:** Checks whether the correct product is being built for the user.

A common difference is:

- **Verification:** "Are we building the product right?" It includes reviews, inspections, and static checking.
- **Validation:** "Are we building the right product?" It includes testing and acceptance by users.

**Examples:**

- Checking an SRS against standards is verification.
- Executing software and demonstrating that it meets customer needs is validation.

Both are needed to detect defects early and deliver an acceptable product.

### 14. What is risk management in software projects?

**Answer:**

Risk management identifies, analyzes, prioritizes, and controls events that could harm project objectives.

**Main steps:**

1. **Risk identification:** Find possible technical, schedule, cost, resource, and requirement risks.
2. **Risk analysis:** Estimate probability and impact.
3. **Risk prioritization:** Address the most serious risks first.
4. **Risk planning:** Use avoidance, reduction, transfer, or acceptance strategies.
5. **Risk monitoring:** Track changes and update plans.

**Examples:** Shortage of skilled developers, uncertain requirements, supplier delay, and technology failure.

**Conclusion:** Proactive risk management increases the probability of completing the project successfully.

### 15. What is software quality? Explain quality assurance and quality control.

**Answer:**

Software quality means the degree to which software meets stated and implied customer requirements.

Important characteristics include correctness, reliability, efficiency, usability, security, maintainability, portability, and performance.

- **Software Quality Assurance (SQA):** Process-oriented prevention of defects through standards, reviews, audits, training, and process monitoring.
- **Software Quality Control (QC):** Product-oriented detection of defects through testing and inspection.

**Difference:** SQA ensures the right process is followed; QC verifies the resulting product is acceptable.

**Conclusion:** Quality assurance and quality control together reduce defects and build customer confidence.