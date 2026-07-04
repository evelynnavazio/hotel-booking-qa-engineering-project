# Risk Analysis

## Risk Matrix

| ID | Risk | Area | Impact | Probability | Priority | Mitigation |
|---|---|---|---|---|---|---|
| R-001 | Users cannot complete a booking | Booking | High | Medium | High | Prioritize booking flow testing and automation |
| R-002 | Invalid bookings are accepted | Booking validation | High | Medium | High | Test required fields, invalid dates, invalid email and phone |
| R-003 | Booking confirmation appears when booking failed | Booking | High | Low | High | Validate success and failure states |
| R-004 | Contact form accepts invalid data | Contact form | Medium | Medium | Medium | Test validation rules and API responses |
| R-005 | Users cannot navigate main sections | Navigation | Medium | Medium | Medium | Test links, buttons, and responsive behavior |
| R-006 | Poor mobile usability blocks booking | Responsive UI | High | Medium | High | Test critical flows on mobile viewport |
| R-007 | Accessibility issues affect users using assistive technology | Accessibility | Medium | Medium | Medium | Run accessibility checklist and axe-based checks |
| R-008 | Slow response time impacts user experience | Performance | Medium | Medium | Medium | Run k6 smoke and load tests |
| R-009 | Automated tests become flaky due to dynamic data | Automation | Medium | Medium | Medium | Use stable selectors, test isolation, and clear test data strategy |
| R-010 | Demo environment changes without notice | Environment | Medium | High | High | Document assumptions and keep tests maintainable |

## Highest Priority Risks

The highest priority risks are related to the booking flow because booking is the core business functionality of the application.

Critical risks include:

- A user cannot complete a valid booking.
- The system accepts invalid booking data.
- The system displays incorrect confirmation messages.
- The booking flow breaks on mobile devices.

## Testing Strategy Based on Risk

The project will prioritize:

1. Booking flow.
2. Form validations.
3. API validation.
4. Contact form.
5. Responsive behavior.
6. Accessibility.
7. Performance.
8. CI/CD regression checks.