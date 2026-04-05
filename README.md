# Software-Quality-Handbook

## Purpose of this Handbook
This handbook defines best practices for ensuring software quality within our development team. As we are a fast-moving startup, inconsitstent approaches to development have resulted in upredictable progress and defect reaching production.

The goal of this handbook is to establish a clear and practical "right way" of working by providing guidelines on task estimation, code reviews, and defect management. These practices aim to improve consistentcy, reduce defects, and enhance team collaboration.

-----

## Contents of this Handbook
This handbook is split into teh following sections:

- **Task Estimation in Scrum**
  - Practical approaches to estimating work
  - Common challenges and how to avoid them

- **Code Reviews**
  - Best practices for reviewing code
  - Common mistakes and review checklists

- **Bug Tracking & Defect Management**
  - Managing defects effectively
  - Defect lifecycle and prioritisation

- **Project Plan**
  -Task breakdown, roles, and workflow

- **Retrospective**
  - Reflection on what worked well and what could be improved

- **Team Contributions**
  - *******Summary of each team member's work*******

-----

## How to Use this Handbook
Each section is designed to be easy to read and apply in practice. Rather than focusing on theory, the handbook provides:

- Key best practices
- Common mistakes to avoid
- Practical insights based on real-world developement
- Links to external resources for further reading

Team members are encouraged to use this handbook as a reference when working on projects to ensure consistency and maintain high software quality.

-----

## Development Process

This project follows a **Trunk-Base Development** approach: 

- Work is completed in **feature branches**
- Each taskis submitted via a **Pull Request (PR)**
- All PRs are **reviewed by team member before merging**
- The **'main'** branch is always kept stable and up to date

This ensures:
- High code quality
- Early defect detection
- Consistent collaboration across the team

## Quality Assurance Approach

To ensure the quality of this handbook:

- All content is reviewed through **pull requests**
- Team members provide **feedback on clarity and structure**
- Formatiing is standardised across all sections
- References are included to support all guidelines

-----

## Repository Structure
/README.md 

/PROJECT-PLAN.md

/RETROSPECTIVE.md

/images/

/research/

/sections/

----- 

## Team Contributions


This project was developed collaboratively by three team members using feature branches and pull requests. Contributions below are based on commit history, merged pull requests, and file ownership.

---

**C21392351 – Project Lead / Task Estimation**

- Created the initial `PROJECT-PLAN.md` with full project details, roles, phases, and deadlines
- Wrote and refined the task estimation research and write-up (`01-task-estimation.md`)
- Refactored the task estimation document for clarity and added sources and insights
- Merged the majority of pull requests into `main` (PRs #2, #3, #4, #9, #10, #12, #13)
- Led final handbook assembly and integration

---

**MarkHughes18 – Code Reviews / Repository Structure**

- Created the initial `README.md` with the full handbook structure and purpose (PR #1)
- Added Contents, How to Use, and Development Process sections to README
- Wrote the code reviews research notes and full write-up (`02-code-reviews.md`)
- Updated code review research to match the handbook style
- Added PR examples and supporting image to the code reviews section
- Reorganised files and folders to match the README structure
- Made peer review improvements to the task estimation section

---

**Dean-c19 – Bug Tracking / Retrospective / Diagrams**

- Created the bug tracking research file covering 5 sources with common themes
- Developed the full bug tracking write-up (`bug-tracking-writeup.md`) including best practices, checklist, further reading, and why it matters
- Renamed and restructured bug tracking files to follow the repo naming convention
- Merged and managed the bug tracking feature branch (PRs #5, #7)
- Added diagrams for each handbook topic to the `images/` folder
- Wrote and updated `RETROSPECTIVE.md` covering what went well, what did not go well, and what the team would do differently
