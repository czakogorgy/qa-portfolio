Login Test Cases

TC-001: Successful login

Steps:

1. Go to login page
2. Enter valid email
3. Enter valid password
4. Click login

Expected Result:
User is redirected to dashboard

---

TC-002: Invalid password

Steps:

1. Enter valid email
2. Enter wrong password
3. Click login

Expected Result:
Error message appears

---

TC-003: Empty fields

Steps:

1. Leave email and password empty
2. Click login

Expected Result:
Validation messages appear

---

TC-004: Invalid email format

Steps:

1. Enter "test123" as email
2. Enter password
3. Click login

Expected Result:
Email format error shown
