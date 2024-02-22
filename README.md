# Test Cases

Below are some Test Case samples that I wrote working on previous projects.

---

**Title**: Login with correct credentials

**Description:** Check if the login works when a person uses a correct Username/Password.

**Steps to reproduce**:
1. Go to www.website.com/login
2. Add correct Username/Password
3. Click "Login" button

**Expected result:**
User should be able to login and is taken to his profile page.

**Test data:**
User: alina & Pass: 123456


---

**Title**: Invalid login attempt

**Description**: Check if the login doesn't work when a person uses a wrong Username/Password.

**Steps to reproduce**:
1. Go to www.website.com/login
2. Enter invalid credentials (incorrect Username or Password)
3. Click "Login" button

**Expected result:**
User should receive an error message indicating that the login attempt failed due to invalid credentials. \
The error message should guide the user on the nature of the issue, such as "Invalid username or password."


---

**Title**: Empty credentials login attempt

**Description:** Check if the system appropriately handles login attempts with empty or missing credentials.

**Steps to reproduce:**
1. Go to www.website.com/login
2. Leave the "Username" and/or "Password" fields blank
3. Press the "Login" button

**Expected result:**
The system should display an error message indicating that both the username and password are required for login.

---

**Title**: Forget password functionality

**Description:** Check if forget passsword functionality works as expected and an email with reset password link is sent.

**Steps to reproduce:**
1. Go to www.website.com/login
2. Press "Forgot Password" button
3. Add an email address
4. Press "Recover" button

**Expected result:**
User should receive an email with a reset password link. That link should allow the user to create a new password.


---

**Title**: Search functionality

**Description:** Check if the search functionality is working correctly by validating that it returns relevant results based on user queries

**Steps to reproduce:**
1. Go to www.website.com/search
2. Enter a valid search query
3. Press the "Search" button

**Expected result:**
System should display a list of results matching the entered search query. \
Each result should contain relevant information, and the displayed items should be consistent with the search criteria.

---

**Title:** Autocomplete functionality in Search

**Description:** Check if system's search feature provides autocomplete suggestions as the user types.

**Steps to reproduce:**
1. Go to www.website.com/search
2. Begin typing a search query with a minimum number of characters
3. Observe the system's response for autocomplete suggestions

**Expected result**: As the user types, the system should dinamically display autocomplete suggestions based on the entered characters. \
Autocomplete suggestions should appear after a reasonable number of characters have been entered (e.g., three characters) to provide meaningful suggestions. \
Suggestions should be relevant and related to the existing data within the system.

---

**Title:** Non-existing query handling in search

**Description:** Check if system gracefully handles searches for non-existing or unmatched queries without generating errors.

**Steps to reproduce:**
1. Go to www.website.com/search
2. Enter an invalid search query, data that is known not to exist in the system
3. Press the "Search" button

**Expected result:** 
The system should respond to the non-existing query without generating an error. \
Instead of an error message, the system should display a message indicating that no results were found.

---



