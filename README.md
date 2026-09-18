# AI_Projects
Access to other AI models

# Code Review Repository


## Purpose


This repository is used to store, review, analyse, and improve source code across multiple technologies, including:


- SQL

- JavaScript

- HTML

- CSS

- JSON

- PowerShell

- Other application source code


The primary objective is to ensure code quality, security, maintainability, performance, and consistency with organisational development standards.


---


## Review Objectives


All code submitted to this repository should be reviewed against the following criteria:


### Security


Review for:


- SQL injection vulnerabilities

- Cross-site scripting (XSS)

- Cross-site request forgery (CSRF)

- Authentication weaknesses

- Authorisation issues

- Hardcoded credentials

- Exposure of sensitive information

- Insecure API usage


### Performance


Review for:


- Inefficient SQL queries

- Unnecessary loops

- Excessive API calls

- Large DOM operations

- Poor database indexing

- Memory leaks


### Maintainability


Review for:


- Code readability

- Naming conventions

- Reusable functions

- Modular design

- Documentation quality

- Error handling

- Logging practices


### Standards Compliance


Review for adherence to:


- Organisational coding standards

- Security policies

- Architecture standards

- Industry best practices

- Regulatory and compliance requirements


---


## Repository Structure


```text

/

├── SQL/

│   ├── StoredProcedures/

│   ├── Queries/

│   └── Scripts/

│

├── JavaScript/

│   ├── Frontend/

│   ├── Backend/

│   └── APIs/

│

├── HTML/

│   ├── Pages/

│   └── Components/

│

├── Reviews/

│   ├── Approved/

│   ├── RequiresChanges/

│   └── SecurityFindings/

│

└── Documentation/

    └── Standards/

```


---


## Review Workflow


### Step 1 – Submit Code


Create a new branch and commit your code.


Example:


```bash

git checkout -b feature/new-report

git add .

git commit -m "Added reporting functionality"

git push origin feature/new-report

```


### Step 2 – Create Pull Request


Include:


- Purpose of the change

- Business requirement

- Expected outcome

- Dependencies

- Testing completed


### Step 3 – Review


Reviewers should assess:


- Security

- Functionality

- Code quality

- Performance

- Maintainability


### Step 4 – Feedback


Review feedback should be categorised as:


| Severity | Description |

|-----------|-------------|

| Critical | Security or production risk |

| High | Significant defect or design issue |

| Medium | Improvement recommended |

| Low | Minor enhancement |

| Informational | Suggestion only |


### Step 5 – Approval


Code can be approved when:


- Review comments addressed

- Testing complete

- Security concerns resolved

- Documentation updated


---


## SQL Review Checklist


- [ ] Query uses appropriate indexes

- [ ] No SELECT *

- [ ] Proper parameterisation

- [ ] Error handling present

- [ ] Transactions managed correctly

- [ ] Performance considered

- [ ] Security reviewed


---


## JavaScript Review Checklist


- [ ] Input validation implemented

- [ ] No hardcoded secrets

- [ ] Proper
 
