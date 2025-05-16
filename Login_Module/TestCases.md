# Login Module - Test Cases

| TC ID  | Title                      | Description                       | Pre-Conditions | Test Steps               | Input Data                   | Expected Result                    | Status |
|--------|----------------------------|---------------------------------|----------------|--------------------------|------------------------------|----------------------------------|--------|
| TC001  | Valid Login                | User logs in with valid details  | User registered| Enter username/password   | username, password           | Redirect to dashboard             | Pass   |
| TC002  | Invalid Login              | User tries wrong credentials     | User registered| Enter wrong password      | username, wrong password     | Show error message                | Pass   |
