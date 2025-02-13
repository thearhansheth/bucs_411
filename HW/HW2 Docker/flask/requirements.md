
## Project Description
GiggleGit is a version control system **where merges are managed by memes**. The startup **CodeChuckle** has built a demo, but it is still unstable. The goal is to bring it to a stable alpha version so that early adopters can test it.  

SnickerSync is a **new diff tool for GiggleGit** that enhances the merge experience with "snickers". PMs are preparing to conduct user studies to refine the product.

---

## Project Requirements

### Goal:
Stabilize the GiggleGit demo into a functional alpha version that can be used by early adopters.  

### Non-Goal:
GiggleGit will not support integrations with non-Git version control systems in this phase.

---

### Non-Functional Requirement 1: Security & Access Control
#### Functional Requirements:
- **User Authentication:**  
  - The system shall enforce authentication for all users attempting to modify SnickerSync settings.  
  - Only users with **PM or Developer roles** shall have access to modify security settings.  

- **Log Encryption & Storage:**  
  - The system shall **encrypt** all logs before storing them.  
  - Only authorized users shall be able to decrypt and view logs.  

---

### Non-Functional Requirement 2: User Study Management

#### Functional Requirements:
- **Experiment Management Interface:**  
  - The system **shall** provide a UI where PMs can create and modify experiment configurations.  
  - Experiment configurations **shall not** require code changes to adjust.  

- **Automated User Group Assignment:**  
  - The system **shall** randomly assign users to experiment groups (control & variant).  
  - The assignment logic **shall** ensure a **50-50 split** unless specified otherwise.  

---
