
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
## Agile  

### Theme:
Get GiggleGit demo into a stable enough alpha to start onboarding some adventurous clients.  

### Epic:
Onboarding Experience  

---

### **User Story 1: Vanilla Git Power-User Onboarding**
**As a vanilla Git power-user that has never seen GiggleGit before,**  
I want to quickly understand the basic differences between GiggleGit and traditional Git, so that I can confidently use it for version control without disrupting my workflow.  

#### Task:  
- Create an intuitive **comparison guide** highlighting key differences between GiggleGit and Git.  

#### Tickets:
- **Write Git vs. GiggleGit Documentation**  
  - Document how merges work differently in GiggleGit.  
  - Ensure users understand **meme-based merges**.  

- **Create Quickstart Guide for Git Users**  
  - Provide **step-by-step instructions** for Git users to transition.  
  - Include CLI and UI examples of key actions.  

---

### **User Story 2: Team Lead Onboarding Experienced Users**  
**As a team lead onboarding an experienced GiggleGit user,**  
I want to access detailed documentation and troubleshooting guides, so that I can efficiently support my team when they encounter issues.  

#### Task:
- Create a **troubleshooting guide** for common GiggleGit onboarding issues.  

#### Tickets:
- **Develop GiggleGit Troubleshooting Guide**  
  - List common issues (e.g., merge conflicts, meme handling failures).  
  - Provide **recommended solutions**.  

- **Implement FAQ Section for Team Leads**  
  - Address key concerns from early adopters.  
  - Include setup, performance, and workflow management topics.  

---

### **User Story 3: New User Learning Merge Process**  
**As a new GiggleGit user,**  
I want an interactive tutorial that demonstrates how merges are managed with memes, so that I can learn and use GiggleGit’s unique merge system effectively.  

#### Task: 
- **Design and implement an interactive merge tutorial.**  

#### Tickets:
- **Develop Meme-Based Merge Tutorial**
  - Implement an interactive walkthrough that visually demonstrates how GiggleGit handles merges.  
  - Include a step-by-step process where users see how meme-based merges work.  
  - Ensure the tutorial can be accessed from the onboarding dashboard.  

- **Add Sample Repository for Hands-On Practice**  
  - Create a public demo repository with pre-configured branches and conflicts.  
  - Allow new users to perform test merges within this repo.  
  - Automate meme generation based on merge conflicts.  

---

### Why is this not a user story?  
**"As a user I want to be able to authenticate on a new machine"**  
This is **not** a user story because it does not explain why the feature is needed. Instead, this would be classified as a function requirement. 



