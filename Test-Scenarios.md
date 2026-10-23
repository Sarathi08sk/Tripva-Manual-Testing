# Tripva.in — Test Scenarios

## Project Overview
- **Application:** Tripva.in
- **Application Type:** Bus Ticket Booking Application
- **Testing Type:** Manual Testing
- **Platforms:** Web and Mobile

## 1. User Registration
- TS-001: Verify that a user can register with valid details.
- TS-002: Verify Full Name field validation for numeric-only input.
- TS-003: Verify Date of Birth field validation for invalid dates.
- TS-004: Verify mandatory field validation when required fields are left empty.

## 2. Email Verification and Validation
- TS-005: Verify that a verification email is received after registration.
- TS-006: Verify that the email field accepts a valid email address.
- TS-007: Verify that the email field rejects an invalid email address.
- TS-008: Verify that an appropriate validation message appears for an invalid email address.

## 3. Profile Management
- TS-009: Verify that a user can upload a valid profile image.
- TS-010: Verify application behavior when a network interruption occurs during profile image upload.
- TS-011: Verify that the Gender dropdown displays correctly without overlapping other fields.
- TS-012: Verify that radio buttons respond correctly when selected.

## 4. Notification Functionality
- TS-013: Verify that notifications are triggered for the relevant user actions.
- TS-014: Verify that notification messages are displayed correctly.

## 5. Bus Booking Functionality
- TS-015: Verify that users can search for buses using valid journey details.
- TS-016: Verify that available buses are displayed for a valid search.
- TS-017: Verify seat selection functionality, where applicable.
- TS-018: Verify that booking details are displayed correctly before confirmation.
- TS-019: Verify booking confirmation after a successful booking, where applicable.

## 6. Cross-Platform and User Interface Testing
- TS-020: Verify that important application features work on supported web and mobile platforms.
- TS-021: Verify that form fields and dropdowns display correctly.
- TS-022: Verify that appropriate error messages appear for invalid inputs.

## Notes
- These scenarios cover documented observations and additional functional checks to perform where the relevant features are available.
- Execute each scenario and record the actual result in the corresponding test cases.
- Do not mark scenarios as passed or failed until they have been executed.
- Update the scenarios to match the features actually tested in the Tripva.in application.
