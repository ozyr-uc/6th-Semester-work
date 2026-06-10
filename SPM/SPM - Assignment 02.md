# Software Project Management
## Assignment 02 — Resource, Risk & Team Management

---

# Project Title
## Cloud-Based Student Assignment Submission and Management System

---

# Group Information

| Name        | Roll No | Email                   |
| ----------- | ------- | ----------------------- |
| Uzair Ahmad | 913     | ozyr.uc@gmail.com       |
| Haroon Ahmad | 914 | haroonahmad121314@gmail.com | 
| Fayaz Ahmad | 924     | fayazahmaddev@gmail.com |

---

# Part A — Resource Planning

# 1. Human Resources

| Resource | Responsibilities |
|---|---|
| Project Manager | Planning, scheduling, monitoring progress |
| System Analyst | Requirement gathering and analysis |
| UI/UX Designer | Interface and user experience design |
| Frontend Developer | Develop client-side application |
| Backend Developer | Develop server-side logic and APIs |
| Database Administrator | Database design and management |
| QA/Test Engineer | Testing and bug reporting |
| Documentation Manager | Prepare reports and documentation |

---

# 2. Technical Resources

| Resource | Purpose |
|---|---|
| Laptop/Computer | Development and testing |
| Internet Connection | Communication and cloud access |
| Cloud Platform | Hosting and storage |
| Git & GitHub | Version control |
| VS Code / IntelliJ | Code development |
| MySQL / PostgreSQL | Database management |
| Browser Testing Tools | Testing compatibility |
| Communication Tools | Team coordination |

---

# 3. Critical/Scarce Resources

| Resource | Reason |
|---|---|
| Stable Internet Connection | Required for cloud access and collaboration |
| Cloud Hosting Credits | Limited availability for deployment |
| Experienced Backend Developer | Critical for system integration |
| Testing Devices | Limited systems for testing |

---

# Part B — RACI Matrix & Team Structure

# 1. RACI Matrix

- **R** = Responsible
- **A** = Accountable
- **C** = Consulted
- **I** = Informed

| Activity | Project Manager | Analyst | Developer | Tester | Documentation Manager |
|---|---|---|---|---|---|
| Requirement Gathering | A | R | C | I | I |
| Project Planning | A | C | I | I | I |
| System Design | C | A | R | I | I |
| Development | I | C | A/R | I | I |
| Testing | I | I | C | A/R | I |
| Documentation | I | I | C | C | A/R |
| Deployment | A | I | R | C | I |

---

# 2. Team Structure

## Hierarchical Team Structure

```text
                    Project Manager
                           |
        -------------------------------------
        |                  |                |
   System Analyst   Development Team   QA Team
	                        |
               -------------------------
               |            |          |
        Frontend Developer  |   Backend Developer
                            |
                  Database Administrator
```

---

# 3. Communication Flow

| Communication Type | Participants | Frequency |
|---|---|---|
| Team Meetings | All Members | Weekly |
| Progress Updates | Developers → Project Manager | Daily |
| Requirement Discussion | Analyst ↔ Client/Instructor | As Needed |
| Bug Reporting | Tester ↔ Developers | Daily During Testing |
| Documentation Review | Documentation Manager ↔ Team | Weekly |

---

# Part C — Risk Management

# 1. Project Risks

| Risk ID | Risk Description | Probability | Impact | Mitigation Strategy |
|---|---|---|---|---|
| R1 | Requirement changes during development | Medium | High | Freeze requirements after approval |
| R2 | Internet connectivity issues | Medium | Medium | Use backup internet connection |
| R3 | Team member absence | Medium | High | Share knowledge among team |
| R4 | Data loss | Low | High | Regular backups and version control |
| R5 | Delays in development | High | High | Weekly progress monitoring |
| R6 | Cloud service downtime | Low | Medium | Choose reliable cloud provider |
| R7 | Security vulnerabilities | Medium | High | Apply authentication and encryption |
| R8 | Lack of communication among team | Medium | Medium | Conduct regular meetings |

---

# 2. Risk Analysis Summary

- High-impact risks mainly relate to development delays and security issues.
- Medium risks involve communication and resource availability.
- Preventive planning and regular coordination can reduce most project risks.

---

# Part D — Conflict & Coordination

# 1. Possible Conflict

A communication conflict may occur between frontend and backend developers due to unclear API requirements and integration delays.

---

# 2. Practical Solution

- Conduct regular coordination meetings
- Maintain proper API documentation
- Use GitHub issues/project boards for task tracking
- Clearly define responsibilities before development begins
