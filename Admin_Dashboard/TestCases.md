# Admin Dashboard - Test Cases

| TC ID  | Title                      | Description                       | Pre-Conditions     | Test Steps                      | Input Data                            | Expected Result                               | Status |
|--------|----------------------------|---------------------------------|--------------------|--------------------------------|--------------------------------------|----------------------------------------------|--------|
| TC001  | Admin Login                | Login with valid admin credentials| Admin account active| Enter admin username/password   | admin username, password             | Redirect to admin dashboard                    | Pass   |
| TC002  | Unauthorized Access        | Block non-admin access           | User logged in     | Try access admin URL            | N/A                                  | Show “Access denied” message                   | Pass   |
