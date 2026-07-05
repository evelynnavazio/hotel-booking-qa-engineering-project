# Hotel Booking QA Project

End-to-end QA portfolio project based on a hotel booking web application.

This project simulates a real QA workflow using Agile methodology, Jira, ISTQB Foundation Level concepts, manual testing, API testing, UI automation, SQL validation, accessibility testing, performance testing, CI/CD, Docker, and AI-assisted QA documentation.

## Application Under Test

Website: https://automationintesting.online/

The application simulates a hotel booking platform where users can view rooms, create reservations, submit contact messages, and interact with different hotel-related features.

## Project Objective

The objective of this project is to demonstrate a complete QA process from test analysis to automated validation.

This project covers:

- Requirement analysis
- Risk-based testing
- Manual test design
- Defect reporting
- Jira workflow management
- API testing
- UI automation
- SQL-based data validation
- Accessibility testing
- Performance testing
- CI/CD execution
- Docker-based test environment
- AI-assisted QA documentation and reporting

## Methodology

This project follows an Agile/Scrum-inspired workflow.

The work is divided into sprints:

| Sprint | Focus |
|---|---|
| Sprint 0 | Test analysis, scope, risks, user stories, acceptance criteria, and test planning |
| Sprint 1 | Manual test cases, exploratory testing, and Jira tickets |
| Sprint 2 | API testing with Postman |
| Sprint 3 | UI automation with Playwright |
| Sprint 4 | SQL testing and backend data validation practice |
| Sprint 5 | Accessibility testing |
| Sprint 6 | Performance testing with k6 |
| Sprint 7 | CI/CD with GitHub Actions and Docker |
| Sprint 8 | Final QA report and portfolio polish |

## Tools and Technologies

| Area | Tool |
|---|---|
| Test Management | Jira |
| Documentation | Markdown |
| Manual Testing | Test cases and exploratory testing |
| API Testing | Postman / Newman |
| UI Automation | Playwright |
| SQL Practice | SQLite / SQL scripts |
| Accessibility Testing | Manual WCAG checklist / axe-core |
| Performance Testing | k6 |
| CI/CD | GitHub Actions |
| Containerization | Docker |
| Version Control | Git / GitHub |
| AI Assistance | ChatGPT / AI-assisted QA workflows |

## ISTQB Concepts Applied

This project applies ISTQB Foundation Level concepts, including:

- Test basis
- Test object
- Test analysis
- Test design
- Test conditions
- Test cases
- Test data
- Expected results
- Defect reporting
- Risk-based testing
- Functional testing
- Non-functional testing
- Regression testing
- Confirmation testing
- Exploratory testing
- Static review
- Test automation
- Test execution
- Test reporting

## Project Structure

hotel-booking-qa-project/
- .github/
- accessibility/
- api/
- automation/
- ci-cd/
- docker/
- docs/
- evidence/
- manual-testing/
- performance/
- sql/
- README.md

## Folder Description

| Folder | Purpose |
|---|---|
| .github/ | GitHub Actions workflows |
| accessibility/ | Accessibility checklist, axe results, and evidence |
| api/ | Postman collections, environments, and API evidence |
| automation/ | Playwright UI automation tests |
| ci-cd/ | CI/CD notes and pipeline evidence |
| docker/ | Docker configuration and execution notes |
| docs/ | Project documentation, test plan, user stories, risks, and acceptance criteria |
| evidence/ | Screenshots, videos, Jira captures, reports, and execution evidence |
| manual-testing/ | Manual test cases, exploratory notes, and bug reports |
| performance/ | k6 scripts and performance reports |
| sql/ | SQL schema, seed data, QA queries, and SQL validation scenarios |

## Testing Scope

### In Scope

- Room listing
- Room details
- Booking flow
- Booking form validations
- Contact form
- Navigation
- Responsive behavior
- API validation
- SQL validation using a simulated hotel booking database
- Accessibility checks
- Performance checks
- UI regression automation
- CI/CD execution

### Out of Scope

- Real payment processing
- Real production database validation
- Security penetration testing
- Real hotel inventory validation
- Native mobile application testing
- Production monitoring

## SQL Testing Scope

The application under test is a public demo environment and does not provide direct database access.

For this reason, SQL testing is implemented using a simulated relational database based on the hotel booking domain.

The goal is to demonstrate QA backend validation skills, including:

- Booking consistency checks
- Duplicate data detection
- Missing data validation
- Referential integrity checks
- Invalid date validation
- Reporting queries
- Test data preparation

## Jira Workflow

Jira is used to simulate real test management and Agile execution.

The project includes:

- Epics
- User stories
- Tasks
- Bugs
- Sprint planning
- Ticket prioritization
- Evidence attachment
- Defect lifecycle tracking

Example Jira structure:

EPIC-001 — Booking Flow  
STORY-001 — As a user, I want to create a room booking  
TASK-001 — Design booking flow test cases  
BUG-001 — Booking form accepts invalid phone number  

Jira evidence will be stored in:

evidence/jira/

## Current Status

Sprint 0 is in progress.

Current deliverables:

- Project overview
- Test scope
- User stories
- Acceptance criteria
- Risk analysis
- Test plan
- Exploratory testing charter
- Traceability matrix
- Bug report template

## Next Steps

The next sprint is:

Sprint 1 — Manual Test Design + Jira Setup

Sprint 1 will include:

- Creating Jira project and board
- Creating epics and user stories
- Designing manual test cases
- Executing exploratory testing
- Reporting first bugs
- Capturing evidence
- Mapping test cases to acceptance criteria