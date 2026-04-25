# Login Page Test Cases

Project: Sample Login Page  
Tester: David Bajus  
Date: April 2026  

## Test Cases

| Test ID | Test Scenario | Steps | Expected Result |
|---|---|---|---|
| TC-LOGIN-001 | Login with valid email and valid password | 1. Open login page 2. Enter valid email 3. Enter valid password 4. Click Login | User is logged in successfully and redirected to the dashboard |
| TC-LOGIN-002 | Login with valid email and invalid password | 1. Open login page 2. Enter valid email 3. Enter invalid password 4. Click Login | Error message is shown and login is not successful |
| TC-LOGIN-003 | Login with invalid email format | 1. Open login page 2. Enter invalid email format 3. Enter any password 4. Click Login | Validation message is shown for email format |
| TC-LOGIN-004 | Login with empty email field | 1. Open login page 2. Leave email empty 3. Enter password 4. Click Login | Validation message is shown for required email field |
| TC-LOGIN-005 | Login with empty password field | 1. Open login page 2. Enter email 3. Leave password empty 4. Click Login | Validation message is shown for required password field |