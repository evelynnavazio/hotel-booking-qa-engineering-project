# Sprint 1 - Manual Test Cases

## Project

Hotel Booking QA Project

## Application Under Test

https://automationintesting.online/

## Sprint Goal

Design and execute manual functional test cases for the main user flows of the hotel booking application.

## Test Case Format

Each test case includes:

- Test Case ID
- User Story
- Module
- Priority
- Preconditions
- Test Data
- Steps
- Expected Result
- Actual Result
- Status
- Evidence
- Notes

## Test Cases

| Test Case ID | User Story | Module | Priority | Status |
|---|---|---|---|---|
| TC-001 | US-001 | Room Discovery | High | Not Run |
| TC-002 | US-002 | Room Discovery | Medium | Not Run |
| TC-003 | US-003 | Booking Flow | High | Not Run |
| TC-004 | US-003 | Booking Flow | High | Not Run |
| TC-005 | US-004 | Booking Flow | High | Not Run |
| TC-006 | US-006 | Booking Validation | High | Not Run |
| TC-007 | US-006 | Booking Validation | High | Not Run |
| TC-008 | US-007 | Contact Form | Medium | Not Run |
| TC-009 | US-008 | Contact Form Validation | Medium | Not Run |
| TC-010 | US-009 | Navigation | Medium | Not Run |


---

## TC-001 - Verify available rooms are displayed

**User Story:** US-001 - View Available Rooms  
**Module:** Room Discovery  
**Priority:** High  
**Type:** Functional  
**Status:** Not Run  

### Preconditions

- The application is accessible.
- The user is on the homepage.

### Test Data

No specific test data required.

### Steps

1. Open https://automationintesting.online/
2. Scroll to the room listing section.
3. Observe the available rooms displayed on the page.

### Expected Result

The homepage should display available rooms with relevant information such as room name, image, description, and price.

### Actual Result

To be completed during execution.

### Evidence

To be added after execution.

### Notes

This test validates that users can discover available hotel rooms before starting the booking flow.

---

## TC-002 - Verify room information is visible and understandable

**User Story:** US-002 - View Room Details  
**Module:** Room Discovery  
**Priority:** Medium  
**Type:** Functional / Usability  
**Status:** Not Run  

### Preconditions

- The application is accessible.
- Available rooms are displayed.

### Test Data

No specific test data required.

### Steps

1. Open https://automationintesting.online/
2. Locate a room card.
3. Review the room name, description, price, image, and visible features.
4. Check whether the information is clear and useful for a user.

### Expected Result

Each room should provide enough visible information for the user to understand the room type, price, and main features.

### Actual Result

To be completed during execution.

### Evidence

To be added after execution.

### Notes

This test supports the room discovery flow and can also reveal usability or accessibility issues.

---

## TC-003 - Verify user can select valid booking dates

**User Story:** US-003 - Select Booking Dates  
**Module:** Booking Flow  
**Priority:** High  
**Type:** Functional  
**Status:** Not Run  

### Preconditions

- The application is accessible.
- At least one room is available for booking.

### Test Data

- Check-in date: valid future date
- Check-out date: valid future date after check-in

### Steps

1. Open https://automationintesting.online/
2. Select an available room.
3. Open the booking date picker.
4. Select a valid check-in date.
5. Select a valid check-out date after the check-in date.

### Expected Result

The selected date range should be accepted and displayed correctly in the booking flow.

### Actual Result

To be completed during execution.

### Evidence

To be added after execution.

### Notes

This test validates a critical part of the booking flow.

---

## TC-004 - Verify invalid booking date range is not accepted

**User Story:** US-003 - Select Booking Dates  
**Module:** Booking Flow  
**Priority:** High  
**Type:** Negative Testing  
**Status:** Not Run  

### Preconditions

- The application is accessible.
- The booking date picker is available.

### Test Data

- Check-in date: future date
- Check-out date: date before or equal to check-in date

### Steps

1. Open https://automationintesting.online/
2. Select an available room.
3. Open the booking date picker.
4. Try to select an invalid date range where check-out is before or equal to check-in.
5. Observe the system behavior.

### Expected Result

The system should prevent invalid date selection or display a clear validation message.

### Actual Result

To be completed during execution.

### Evidence

To be added after execution.

### Notes

This test applies negative testing and boundary validation concepts.

---

## TC-005 - Verify user can submit a valid booking

**User Story:** US-004 - Submit Booking Information  
**Module:** Booking Flow  
**Priority:** High  
**Type:** Functional / End-to-End  
**Status:** Not Run  

### Preconditions

- The application is accessible.
- A valid room and date range are selected.

### Test Data

- First name: Evelyn
- Last name: User
- Email: evelyn.test@example.com
- Phone: 12345678901

### Steps

1. Open https://automationintesting.online/
2. Select an available room.
3. Select a valid check-in and check-out date.
4. Fill in the booking form using valid data.
5. Submit the booking form.
6. Observe the result.

### Expected Result

The booking should be submitted successfully and the user should see a clear booking confirmation message.

### Actual Result

To be completed during execution.

### Evidence

To be added after execution.

### Notes

This is a critical end-to-end scenario and a strong candidate for future Playwright automation.