# Exploratory Testing Charter

## Charter ID

ETC-001

## Mission

Explore the hotel booking application to identify functional, usability, accessibility, and validation issues in the main user flows.

## Areas to Explore

- Home page.
- Room listing.
- Room details.
- Booking flow.
- Date picker.
- Booking form.
- Contact form.
- Navigation.
- Mobile layout.
- Accessibility behavior.

## Focus Areas

### Booking Flow

- Can a user complete a valid booking?
- Are invalid dates rejected?
- Are required fields validated?
- Is the confirmation message clear?
- Does the booking flow work on different screen sizes?

### Contact Form

- Can a user submit a valid contact message?
- Are required fields validated?
- Are invalid emails rejected?
- Are validation messages clear?

### UI and Navigation

- Are buttons and links working?
- Are sections displayed correctly?
- Is the layout stable?
- Does the page behave correctly on mobile?

### Accessibility

- Are images meaningful for screen reader users?
- Are form fields labeled?
- Is keyboard navigation possible?
- Is focus visible?

## Test Data Ideas

Valid booking data:

- First name: Evelyn
- Last name: Grau
- Email: evelyn.test@example.com
- Phone: 12345678901

Invalid data examples:

- Empty first name.
- Empty last name.
- Invalid email format.
- Short phone number.
- Check-out date before check-in date.
- Empty contact message.
- Very short contact message.
- Very long contact message.

## Timebox

Initial exploratory session: 60 minutes.

## Expected Output

- Notes from exploratory testing.
- Potential bugs.
- Questions or unclear requirements.
- Candidate scenarios for manual test cases.
- Candidate scenarios for automation.