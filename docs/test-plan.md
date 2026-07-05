
# Test Plan

## Project Name

Hotel Booking QA Project

## Application Under Test

**Application:** Hotel Booking Demo  
**URL:** https://automationintesting.online/

## Objective

The objective of this test plan is to define the testing strategy for a hotel booking web application.

The project simulates a real QA workflow using Agile methodology, Jira, ISTQB Foundation Level concepts, manual testing, API testing, UI automation, SQL validation, accessibility testing, performance testing, CI/CD, Docker, and AI-assisted QA documentation.

## Methodology

This project follows an Agile/Scrum-inspired approach.

Testing work is organized into sprints. Each sprint has a specific QA objective, deliverables, evidence, and Jira tracking.

## Sprint Plan

| Sprint | Focus | Main Deliverables |
|---|---|---|
| Sprint 0 | Test analysis and QA planning | Scope, risks, user stories, acceptance criteria, test plan |
| Sprint 1 | Manual testing and Jira | Manual test cases, Jira tickets, exploratory testing, bug reports |
| Sprint 2 | API testing | Postman collection, API test cases, API evidence |
| Sprint 3 | UI automation | Playwright tests, Page Object Model, automation reports |
| Sprint 4 | SQL testing | SQL schema, seed data, validation queries, SQL test scenarios |
| Sprint 5 | Accessibility testing | Accessibility checklist, axe results, accessibility bugs |
| Sprint 6 | Performance testing | k6 smoke test, k6 load test, performance summary |
| Sprint 7 | CI/CD and Docker | GitHub Actions workflow, Docker execution notes |
| Sprint 8 | Final QA report | Final summary, metrics, portfolio documentation |

## Test Basis

The test basis includes:

- Public behavior of the application
- Visible UI flows
- Available API behavior
- User stories
- Acceptance criteria
- Risk analysis
- Exploratory testing findings
- ISTQB Foundation Level concepts

## Test Object

The test object is the Hotel Booking Demo application available at:

https://automationintesting.online/

The application includes:

- Room listing
- Room details
- Booking flow
- Contact form
- Navigation sections
- API endpoints
- UI components
- Form validation behavior

## Test Scope

### In Scope

The following areas are included:

- Home page validation
- Room listing validation
- Room details validation
- Booking flow
- Booking form validations
- Contact form
- Navigation
- Responsive behavior
- API testing
- UI automation
- SQL validation using a simulated database
- Accessibility testing
- Performance testing
- CI/CD execution
- Docker execution
- Jira-based test management

### Out of Scope

The following areas are excluded:

- Real payment processing
- Real production database access
- Security penetration testing
- Production monitoring
- Native mobile app testing
- Real hotel inventory verification

## Test Levels

The project will include:

- Component-level validation through API checks
- Integration-style validation between UI behavior and API behavior where possible
- System testing from the user perspective
- Regression testing using automated UI checks

## Test Types

### Functional Testing

Functional testing validates whether the application behaves according to expected business flows.

Covered areas:

- Viewing rooms
- Selecting dates
- Completing booking form
- Submitting booking
- Submitting contact form
- Validating required fields
- Validating error messages
- Navigating main sections

### Exploratory Testing

Exploratory testing will be used to discover issues not covered by predefined test cases.

Focus areas:

- Booking edge cases
- Invalid form input
- Unexpected UI behavior
- Mobile layout issues
- Accessibility concerns
- Broken or unclear user flows

### API Testing

API testing will validate backend behavior where endpoints are available.

Covered checks:

- Status codes
- Response body structure
- Required fields
- Error handling
- Data consistency
- Positive and negative scenarios

Tool:

- Postman
- Newman, if command-line execution is added later

### UI Automation Testing

UI automation will be implemented using Playwright.

Automation priority:

1. Critical booking flow
2. Booking validation scenarios
3. Contact form submission
4. Navigation checks
5. Regression scenarios

Automation design approach:

- Stable selectors
- Page Object Model
- Reusable test data
- Clear assertions
- Screenshots and reports where useful

### SQL Testing

The application does not provide direct access to its real database.

For this reason, SQL testing will use a simulated database based on the hotel booking domain.

The SQL module will validate:

- Invalid booking dates
- Missing customer data
- Duplicate customer emails
- Bookings linked to non-existing rooms
- Bookings without customers
- Room availability consistency
- Basic reporting queries

The SQL folder will include:

```text
sql/
├── schema.sql
├── seed-data.sql
├── qa-queries.sql
└── sql-test-scenarios.md