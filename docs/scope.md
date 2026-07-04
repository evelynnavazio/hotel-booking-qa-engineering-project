# Test Scope

## In Scope

The following areas are included in the testing scope:

### Functional Testing

- Home page content and navigation.
- Room listing.
- Room details.
- Booking flow.
- Date selection.
- Guest information form.
- Contact form.
- Form validations.
- Confirmation messages.
- Error messages.

### API Testing

- Booking-related endpoints.
- Room-related endpoints.
- Contact/message endpoints if available.
- Status codes.
- Response body validation.
- Required fields.
- Error handling.

### UI Automation

- Critical user flows.
- Booking creation flow.
- Contact form submission.
- Navigation checks.
- Form validation checks.
- Regression checks.

### Accessibility Testing

- Alternative text for images.
- Form labels.
- Keyboard navigation.
- Color contrast.
- Focus visibility.
- Semantic structure.
- Basic WCAG checks.

### Performance Testing

- Basic response time checks.
- Smoke performance test.
- Simple load test.
- Threshold validation.
- Failure rate monitoring.

### CI/CD

- Automated test execution using GitHub Actions.
- Test report generation.
- Regression suite execution on push or pull request.

### AI-assisted QA

- Bug summary generation.
- Test case improvement.
- Risk analysis support.
- QA documentation support.

## Out of Scope

The following areas are not included in the current scope:

- Payment processing.
- Real hotel inventory validation.
- Real user account management.
- Database-level testing.
- Security penetration testing.
- Cross-browser testing beyond the selected automation configuration.
- Mobile native application testing.
- Production monitoring.

## Assumptions

- The application is a demo/testing environment.
- Data may reset or change without notice.
- Some API behavior may not be fully documented.
- The project is intended for portfolio demonstration, not for production certification.
- UI or backend changes may affect automated test stability.

## Constraints

- No access to internal requirements.
- No access to database logs.
- No access to production analytics.
- Testing is based on publicly visible behavior and available API responses.