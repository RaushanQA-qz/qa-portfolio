## TC_01 — Login with valid credentials

### Preconditions
User is on Login page.

### Steps
1. Enter valid email.
2. Enter valid password.
3. Click Login button.

### Expected Result
User is successfully logged into the system.

---

## TC_02 — Login with invalid password

### Preconditions
User is on Login page.

### Steps
1. Enter valid email.
2. Enter invalid password.
3. Click Login button.

### Expected Result
Error message is displayed.
User remains on login page.

---

## TC_03 — Login with empty fields

### Preconditions
User is on Login page.

### Steps
1. Leave email field empty.
2. Leave password field empty.
3. Click Login button.

### Expected Result
Validation messages are displayed.
Login is not performed.
