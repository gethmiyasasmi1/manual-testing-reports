# User Registration Module - Test Scripts

## Test Script for TC001: Successful Registration
1. Navigate to registration page
2. Enter valid full name, email, password
3. Submit the form
4. Verify success message and redirect to login page

## Test Script for TC002: Registration with Existing Email
1. Go to registration page
2. Enter already registered email
3. Fill other fields validly
4. Submit the form
5. Verify error message “Email already exists”

## Test Script for TC003: Password Strength Validation
1. Navigate to registration page
2. Enter password less than required criteria (e.g. "123")
3. Submit the form
4. Verify error message about password strength

## Test Script for TC004: Mandatory Fields Validation
1. Navigate to registration page
2. Submit empty form
3. Verify error messages on all mandatory fields

## Test Script for TC005: Email Format Validation
1. Navigate to registration page
2. Enter invalid email (e.g., "user@@mail")
3. Submit the form
4. Verify error message for invalid email format
