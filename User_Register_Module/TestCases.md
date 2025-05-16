# User Registration Module - Test Cases

| TC ID  | Title                          | Description                                | Pre-Conditions           | Test Steps                            | Input Data                            | Expected Result                         | Status |
|--------|--------------------------------|--------------------------------------------|-------------------------|--------------------------------------|--------------------------------------|----------------------------------------|--------|
| TC001  | Successful Registration         | User registers with valid data              | None                    | Fill registration form and submit    | Valid name, email, password           | Registration successful message shown  | Pass   |
| TC002  | Registration with Existing Email| User tries to register with an already used email | None             | Fill form with existing email         | Existing email                       | Show error “Email already exists”      | Pass   |
| TC003  | Password Strength Validation    | Password must meet minimum criteria          | None                    | Enter weak password                   | Password: "123"                     | Show error “Password too weak”          | Pass   |
| TC004  | Mandatory Fields Validation     | Ensure all mandatory fields are validated    | None                    | Submit empty registration form        | Empty fields                        | Show errors for required fields         | Pass   |
| TC005  | Email Format Validation         | Check invalid email format                     | None                    | Enter invalid email format            | Email: "user@@mail"                 | Show error “Invalid email format”       | Pass   |
