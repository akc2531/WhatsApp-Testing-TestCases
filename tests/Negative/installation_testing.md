### Negative Installation Testing

#### Test Case: Invalid Registration Attempts
- **Description:** Verify that the application handles invalid registration attempts gracefully.
- **Steps:**
  1. Enter an invalid mobile number or format during registration.
  2. Attempt to proceed with registration.
- **Expected Result:** The application displays an appropriate error message indicating that the registration attempt is invalid.

#### Test Case: Duplicate Mobile Number Registration
- **Description:** Verify that the application does not allow registration with a mobile number that is already registered.
- **Steps:**
  1. Attempt to register with a mobile number that is already registered on WhatsApp.
  2. Proceed with the registration process.
- **Expected Result:** The application prevents registration with a mobile number that is already associated with an existing account.
