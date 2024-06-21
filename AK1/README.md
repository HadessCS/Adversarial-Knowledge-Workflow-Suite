#### Password Spray (AK1)

1. **Load Configuration**
    - Load target accounts and common passwords from `ak1_password_spray_config.json`.

2. **Simulate Password Spray Attack**
    - For each password in the list:
        - For each account in the target accounts:
            - Attempt login using the password.
            - Record and report successful attempts.

3. **Log and Report**
    - Generate a log of the attack attempts and successful logins.
    - Create a report summarizing the findings.
