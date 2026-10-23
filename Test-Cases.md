# Tripva.in — Test Cases

## Project Details
- **Application:** Tripva.in
- **Testing Type:** Manual Testing
- **Module:** Registration and Profile Management
- **Platform:** Web and Mobile

## TC-001: Full Name Field Validation

**Precondition:** Registration page is open.

**Test Steps:**
1. Enter numeric-only values in the Full Name field.
2. Submit the form.

**Expected Result:** The application should reject invalid numeric-only input or display an appropriate validation message.

**Actual Result:** The field accepted numeric values.

**Status:** Fail

---

## TC-002: Date of Birth Validation

**Precondition:** Registration page is open.

**Test Steps:**
1. Enter an invalid date in the Date of Birth field.
2. Submit the form.

**Expected Result:** The application should reject invalid dates and display a validation message.

**Actual Result:** Invalid input was accepted.

**Status:** Fail

---

## TC-003: Email Verification

**Precondition:** A valid email address is available.

**Test Steps:**
1. Enter a valid email address.
2. Submit the registration form.
3. Check the email inbox for a verification message.

**Expected Result:** A verification email should be received.

**Actual Result:** The verification email was not received.

**Status:** Fail

---

## TC-004: Profile Image Upload

**Precondition:** The user is on the profile page.

**Test Steps:**
1. Select an image for the profile.
2. Interrupt the network during upload.
3. Observe the application's response.

**Expected Result:** The application should handle the network interruption gracefully and display an appropriate message.

**Actual Result:** Profile image upload failed during a network error.

**Status:** Fail

---

## TC-005: Gender Dropdown Display

**Precondition:** Registration page is open.

**Test Steps:**
1. Click the Gender dropdown.
2. Observe the dropdown's position relative to the Age field.

**Expected Result:** The dropdown should display correctly without overlapping other fields.

**Actual Result:** The Gender dropdown overlapped the Age field.

**Status:** Fail

---

## TC-006: Radio Button Functionality

**Precondition:** The relevant form is open.

**Test Steps:**
1. Click the radio button.
2. Observe whether the selection changes.

**Expected Result:** The radio button should respond correctly to user interaction.

**Actual Result:** The radio button did not work when clicked.

**Status:** Fail

---

## TC-007: Invalid Email Address Validation

**Precondition:** Registration page is open.

**Test Steps:**
1. Enter an invalid email address.
2. Submit the form.

**Expected Result:** The application should reject the invalid email address.

**Actual Result:** The email field accepted an invalid address.

**Status:** Fail

---

## TC-008: Email Validation Message

**Precondition:** Registration page is open.

**Test Steps:**
1. Enter an invalid email address.
2. Submit the form.
3. Check whether a validation message appears.

**Expected Result:** An appropriate validation message should be displayed.

**Actual Result:** No validation error was displayed.

**Status:** Fail

---

## TC-009: Notification Functionality

**Precondition:** The application is in a state where a notification should be triggered.

**Test Steps:**
1. Perform an action that should trigger a notification.
2. Observe the application's response.

**Expected Result:** The expected notification should be displayed or delivered.

**Actual Result:** Notification functionality was not working.

**Status:** Fail

---

## Notes
- These test cases document the observed defects identified during testing.
- Confirm each result by repeating the test.
- Update actual results and status if retesting produces a different outcome.
- Add screenshots where available, without exposing personal information.
