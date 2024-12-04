# Diagramming Guide

## 1. **Requirements Gathering**

- **Functional Requirements:** Specific functionalities that the system must perform.
- **Non-Functional Requirements:** Characteristics such as performance, security, usability, etc.
- **Business Rules:** Standards and policies that govern the system's behavior and ensure it meets business objectives.

## 2. **Requirements Analysis**

- Validation and prioritization of the gathered requirements.
- Identification of potential conflicts or inconsistencies.
- Clear definition of business rules and their integration into the requirements.

## 3. **System Design**

### C4 Diagrams

- Context Diagram (C4)
- Container Diagram (C4)
- Component Diagram (C4)
- Code Diagram (C4) (Optional)

### UML Diagrams

- Use Case Diagram (UML)
- Sequence Diagrams (UML)
- Class Diagrams (UML)
- State Diagrams (UML) (Optional)

### Data Model

- Entity-Relationship Model (Figures)
- Relational Model (Tables)
- Data Flow Diagram (DFD) (Optional but recommended since we are talking about inventories)

## 4. **Development and Implementation**

- Deployment Diagrams (Infrastructure and network) (UML)

## 5. **Testing**

- **Unit Testing:** Verification of each individual component.
- **Integration Testing:** Ensuring that components work correctly together.
- **System Testing:** Validation of the complete system against requirements.
- **Acceptance Testing:** Confirmation by the end user that the system meets their expectations.

## 6. **Deployment**

- Installation of the system in the production environment.
- Configuration and final adjustment for operational readiness.

## 7. **Maintenance and Support**

- Correction of errors detected post-deployment.
- Updates and improvements based on user feedback and changes in requirements.

## 8. **Documentation**

- **Technical Documentation:** Details about architecture, design, code, and APIs.
- **User Documentation:** Guides and manuals for end users.
- **Updating Diagrams and Models:** Maintain UML, C4 diagrams, and others updated as the system evolves.

## 9. **Configuration and Version Management**

- Source code and documentation version control.
- Structured change and maintenance management.

# Standard Diagram Types in System Design

## **C4 Model:**

- _Context Diagram:_ Macro view of the system and its external interactions.
- _Container Diagram:_ Decomposition of the system into high-level containers.
- _Component Diagram:_ Detail of the components within each container.
- _Code Diagram:_ Detail of the components' implementation.

## **UML (Unified Modeling Language):**

### - **Structural Diagrams:**

- _Use Case Diagram:_ Representation of interactions between actors and the system in the model's context.
- _Sequence Diagrams:_ Dynamic interactions between objects.
- _State Diagrams:_ Representation of the states an object goes through during its lifecycle.
- _Activity Diagrams:_ Flow of activities within the system.
- _Collaboration Diagrams:_ Show interactions between objects and their organization.

### - **Behavioral Diagrams:**

- _Class Diagrams:_ Static structure of the system.
- _Component Diagrams:_ Organization and dependencies of components.
- _Object Diagrams:_ Instances of classes and their relationships.
- _Deployment Diagrams:_ Distribution of components on hardware.
- _Package Diagrams:_ Grouping of model elements.

## **Data Model:**

- _Entity-Relationship Model:_ Diagram that shows entities and the relationships between them. (Figures)
- _Relational Model:_ Representation of the logical structure of the database, including tables and relationships.
