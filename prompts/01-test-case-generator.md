## Prompt: Bug Report Enhancer

**Prompt:**
You are a senior QA automation engineer.

I want you to generate automated test cases for the following login feature:

- The form has two input fields: email and password.
- Email must be in valid format.
- Password must be at least 6 characters.
- If the credentials are incorrect, the user sees an error.
- If the credentials are correct, the user is redirected to the dashboard.

Please follow these instructions:

1. Think step by step before generating the test cases.
2. Cover both positive and negative scenarios.
3. Include at least 5 test cases.
4. For each test case, provide: ID, description, input data, expected result.

Use this format for your output (in markdown table):

| ID | Description | Input | Expected Result |
|----|-------------|-------|------------------|
| TC001 | ... | ... | ... |

Example:

| ID | Description | Input | Expected Result |
|----|-------------|-------|------------------|
| TC001 | Valid login | email: user@test.com, password: pass123 | User is redirected to dashboard |

Now generate the full table.

