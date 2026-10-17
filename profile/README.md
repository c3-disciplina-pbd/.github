# Database Project - Group 4

Academic GitHub organization for **Group 4** of **INF1930 — Database Project** at
**Universidade Católica de Pernambuco (UNICAP)**, during the **2026.2 semester**.

This organization centralizes the source code, SQL scripts, documentation,
project planning, issues, tests, and collaborative development of the course project.

## About the Course

**Course:** INF1930 — Database Project  
**Institution:** Universidade Católica de Pernambuco — UNICAP  
**Semester:** 2026.2  
**Group:** 4  
**Workload:** 60 hours

The course focuses on relational database design and implementation, including:

- Conceptual, logical, and physical data modeling
- Relational database design
- Normalization
- SQL and data manipulation
- Integrity constraints
- Views
- Database security and access control
- Stored procedures and functions
- Triggers

## Project — Webdriver

The course project is based on the **Webdriver** domain: a file storage and
management platform whose database supports users, files, sharing,
institutions, plans, support requests, operations, and file version history.

The implementation combines **SQL with a supporting programming language**.

### Part 1 — Database Foundation

The first stage establishes the core database structure:

- Conceptual model
- Logical model
- Physical model
- Database creation
- Insert, search, update, and delete operations
- Users and files
- File sharing
- Institutions and plans
- Support relationships
- File operation history and versioning

### Part 2 — Security and Procedural SQL

The second stage extends the database with advanced SQL and access-control features:

- `Atividades_recentes` activity-control table
- Restricted Root access
- User and institution views
- Hidden internal IDs
- Database roles and permissions
- Stored procedures
- Database functions
- Triggers
- Security and integration testing

## Project Management

Development is organized through GitHub Issues and GitHub Projects.

Each task should contain:

- An assigned owner
- Sprint / iteration
- Priority
- Acceptance criteria
- Related implementation or Pull Request
- Review by another team member

Recommended workflow:

`Backlog → Ready → In Progress → In Review → Done`

Blocked tasks should use the dedicated `Blocked` status.

A task should only move to **Done** after implementation, testing, and review
by another team member.

## Academic Timeline

| Date | Milestone |
| --- | --- |
| Sep 4, 2026 | Project presentation and group formation |
| Sep 25, 2026 | Project Q&A |
| Oct 13, 2026 | Database security |
| Oct 16, 2026 | Views, indexes, and constraints |
| Oct 23, 2026 | Transactions and stored procedures I |
| Oct 27, 2026 | Transactions and stored procedures II |
| Oct 30, 2026 | Triggers |
| Nov 6, 2026 | Project resolution Q&A |
| Nov 10, 2026 | Project presentations |
| Nov 13, 2026 | Project presentations |
| Nov 17, 2026 | Project presentations |

> The specific presentation date assigned to Group 4 should be confirmed with
> the professor.

## Collaboration Guidelines

1. Create an Issue before starting significant work.
2. Assign the Issue to the responsible team member.
3. Work in a dedicated branch.
4. Reference the Issue in commits and Pull Requests.
5. Move completed work to `In Review`.
6. Request validation from another team member.
7. Merge only after review and successful testing.

## Repository

The main repository contains the implementation and documentation of the
Webdriver database project.

**Main repository:** `webdriver-database`

---

Built collaboratively by Group 4 for the INF1930 Database Project course.
