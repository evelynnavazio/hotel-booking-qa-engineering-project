# Test Plan

## Project

Hotel Booking QA Engineering Project

## Application Under Test

https://automationintesting.online/

## Objective

The objective of this test plan is to define the testing approach for a hotel booking web application, covering manual testing, API testing, UI automation, accessibility testing, performance testing, CI/CD integration, and AI-assisted QA workflows.

## Test Levels

- Functional testing.
- Regression testing.
- API testing.
- UI automation testing.
- Accessibility testing.
- Performance testing.
- Smoke testing.

## Test Types

### Manual Functional Testing

Manual tests will validate the main user flows and business rules before automation.

Covered areas:

- Room listing.
- Room details.
- Booking flow.
- Contact form.
- Navigation.
- Form validation.
- Responsive behavior.

### API Testing

API testing will validate backend behavior, including:

- Status codes.
- Response bodies.
- Required fields.
- Error handling.
- Data consistency.

### UI Automation

UI automation will cover stable and high-value regression scenarios using Playwright.

Priority flows:

- Booking creation.
- Booking validation.
- Contact form submission.
- Navigation checks.
- Critical UI validations.

### Accessibility Testing

Accessibility testing will include:

- Alternative text review.
- Form labels.
- Keyboard navigation.
- Focus indicators.
- Basic WCAG-based checks.
- Axe-based automated checks where applicable.

### Performance Testing

Performance testing will include:

- Smoke test.
- Basic load test.
- Response time thresholds.
- Failure rate monitoring.

### CI/CD

GitHub Actions will be used to run automated tests on repository events such as push or pull request.

## Entry Criteria

Testing can begin when:

- Application is accessible.
- Main flows are available.
- Scope has been defined.
- User stories and acceptance criteria are documented.
- Test environment is available.

## Exit Criteria

Sprint testing can be considered complete when:

- Planned test cases have been executed.
- Critical and high-priority bugs are documented.
- Automation candidates are identified.
- Test evidence is saved.
- Test summary is documented.

## Test Environment

| Item | Description |
|---|---|
| Application | Hotel Booking Demo |
| URL | https://automationintesting.online/ |
| Browser | Chrome |
| OS | Windows |
| API Tool | Postman |
| Automation Tool | Playwright |
| Performance Tool | k6 |
| Accessibility Tool | Manual checklist and axe-core |
| CI/CD | GitHub Actions |

## Roles and Responsibilities

| Role | Responsibility |
|---|---|
| QA Engineer | Test analysis, manual testing, bug reporting, automation, API testing, documentation |
| Product Owner simulation | Requirements interpretation and acceptance criteria definition |
| Developer simulation | Defect analysis and technical validation |

## Deliverables

- Project overview.
- Test scope.
- User stories.
- Acceptance criteria.
- Risk analysis.
- Manual test cases.
- Bug reports.
- API test collection.
- Playwright automated tests.
- Accessibility report.
- Performance test scripts.
- CI/CD workflow.
- Final QA summary report.