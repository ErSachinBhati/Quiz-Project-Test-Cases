# Quiz-Project-Test-Cases
Test cases of open-source programming influencers Quiz

## Scenario: Access to the Login Page

**Summary:** This scenario checks if users can easily go to the login page on a quiz website and access it without any issues.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:**
  - Access the browser.
  - The user has a valid URL.
- **Chronological Tasks:**
  1. Launch a web browser.
  2. Type the URL into the address bar.
  3. The user presses the enter button.
- **Conditions of Success:** 
  - The user is successfully directed to the website's Login Page.

---

## Scenario: Access to the Registration Page

**Summary:** This scenario checks if clicking the "Register" button on the homepage takes users to the registration page as expected.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** User is on the login page of the website.
- **Chronological Tasks:**
  1. User clicks on the "Register" button provided on the homepage.
- **Conditions of Success:** 
  - The user is successfully redirected to the registration page of the website.

---

## Scenario: Display Password on Registration Page

**Summary:** This scenario checks if users can see their password as they type it on the registration page, ensuring the "Show Password" feature works properly.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** User is on the website's registration page.
- **Chronological Tasks:**
  1. The user inputs Password.
  2. The user clicks the "Show Password" option located directly below the password input field.
- **Conditions of Success:** 
  - The user is able to see the password displayed in the password input box.

---

## Scenario: User Registration

**Summary:** This scenario checks if user registration works correctly.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the website's registration page.
- **Chronological Tasks:**
  1. The user inputs Name.
  2. The user inputs Email.
  3. The user inputs Password.
  4. The user inputs the same password in Confirm Password.
  5. The user clicks on the "Register" button.   
- **Conditions of Success:** 
  - The user is successfully registered, and a message appears saying "User registered successfully."

---

## Scenario: User Tries to Register Again with an Email Already Used Before

**Summary:** In this scenario, the user tries to register using an email address that's already in the database. This scenario addresses how to manage duplicate email registrations.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** User is on the registration page.
- **Chronological Tasks:**
  1. User inputs his name.
  2. User enters an Email that is already registered.
  3. The user inputs Password.
  4. The user inputs the same password in Confirm Password.
  5. User clicks on the register button.
- **Conditions of Success:** 
  - An error message is displayed in red color: "This email is already registered."

---

## Scenario: Password and Confirm Password Mismatch

**Summary:** This scenario verifies the functionality of password and confirm password validation.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the registration page.
- **Chronological Tasks:**
  1. User inputs his name.
  2. User enters an email.
  3. The user inputs Password.
  4. The user inputs a different Password in the ‘Confirm Password’ box.
  5. User clicks on the register button.
- **Conditions of Success:** 
  - An error message is displayed in red color: "Passwords do not match."

---

## Scenario: Unsuccessful Registration Due to Password Length

**Summary:** This test case verifies the behavior of the registration process when the password provided does not meet the length requirement.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the registration page.
- **Chronological Tasks:**
  1. User inputs his name.
  2. User inputs an email.  
  3. The user inputs a password less than 8 characters.
  4. User inputs Confirm Password that is the same as the Password.
  5. User clicks on the register button.
- **Conditions of Success:** 
  - An error message is displayed in red color: "Password must be 8-15 characters long, and include at least one uppercase letter, one lowercase letter, one numeric digit, and one special character."

---

## Scenario: Unsuccessful Registration Due to Password Length

**Summary:** This test case verifies the behavior of the registration process when the password provided does not meet the length requirement.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the registration page.
- **Chronological Tasks:**
  1. User inputs his name.
  2. User inputs an email.  
  3. The user inputs a password of more than 15 characters.
  4. User inputs Confirm Password that is the same as the Password.
  5. User clicks on the register button.
- **Conditions of Success:** 
  - An error message is displayed in red color: "Password must be 8-15 characters long, and include at least one uppercase letter, one lowercase letter, one numeric digit, and one special character."

---

## Scenario: Unsuccessful Registration Due to Missing Uppercase Letter in Password

**Summary:** This test case verifies the behavior of the registration process when the password provided does not meet strength requirements.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the registration page.
- **Chronological Tasks:**
  1. User inputs his name.
  2. User inputs an email.  
  3. The user inputs a password without an uppercase letter.
  4. User inputs Confirm Password that is the same as the Password.
  5. User clicks on the register button.
- **Conditions of Success:** 
  - An error message is displayed in red color: "Password must be 8-15 characters long, and include at least one uppercase letter, one lowercase letter, one numeric digit, and one special character."

---

## Scenario: Unsuccessful Registration Due to Missing Lowercase Letter in Password

**Summary:** This test case verifies the behavior of the registration process when the password provided does not meet strength requirements.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the registration page.
- **Chronological Tasks:**
  1. User inputs his name.
  2. User inputs an email.  
  3. The user inputs a password without a lowercase letter.
  4. User inputs Confirm Password that is the same as the Password.
  5. User clicks on the register button.
- **Conditions of Success:** 
  - An error message is displayed in red color: "Password must be 8-15 characters long, and include at least one uppercase letter, one lowercase letter, one numeric digit, and one special character."

---

## Scenario: Unsuccessful Registration Due to Missing Special Character in Password

**Summary:** This test case verifies the behavior of the registration process when the password provided does not meet strength requirements.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the registration page.
- **Chronological Tasks:**
  1. User inputs his name.
  2. User inputs an email.  
  3. The user inputs a password without a special character.
  4. User inputs Confirm Password that is the same as the Password.
  5. User clicks on the register button.
- **Conditions of Success:** 
  - An error message is displayed in red color: "Password must be 8-15 characters long, and include at least one uppercase letter, one lowercase letter, one numeric digit, and one special character."

---

## Scenario: Unsuccessful Registration Due to Missing Numeric in Password

**Summary:** This test case verifies the behavior of the registration process when the password provided does not meet strength requirements.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the registration page.
- **Chronological Tasks:**
  1. User inputs his name.
  2. User inputs an email.  
  3. The user inputs a password without a numeric digit.
  4. User inputs Confirm Password that is the same as the Password.
  5. User clicks on the register button.
- **Conditions of Success:** 
  - An error message is displayed in red color: "Password must be 8-15 characters long, and include at least one uppercase letter, one lowercase letter, one numeric digit, and one special character."

---

## Scenario: Successful Login

**Summary:** This scenario verifies the functionality of successful user login.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the website's login page with valid credentials (email, password, etc.).
- **Chronological Tasks:**
  1. The user inputs email.
  2. The user inputs password.
  3. The user clicks on the Login button.
- **Conditions of Success:** 
  - The user is successfully logged in and redirected to the dashboard.

---

## Scenario: Invalid Email During Login

**Summary:** This scenario checks if an appropriate error message is displayed when the user attempts to log in with an invalid email format.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the login page.
- **Chronological Tasks:**
  1. The user inputs an email with an invalid format.
  2. The user inputs a password.
  3. The user clicks on the Login button.
- **Conditions of Success:** 
  - An error message is displayed indicating that the email format is invalid.

---

## Scenario: Incorrect Password During Login

**Summary:** This scenario verifies the behavior of the system when the user enters an incorrect password.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the login page.
- **Chronological Tasks:**
  1. The user inputs a registered email.
  2. The user inputs an incorrect password.
  3. The user clicks on the Login button.
- **Conditions of Success:** 
  - An error message is displayed indicating that the password is incorrect.

---

## Scenario: Resetting the Password

**Summary:** This scenario checks if the user can successfully reset their password via the "Forgot Password" functionality.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the login page.
- **Chronological Tasks:**
  1. The user clicks on the "Forgot Password" link.
  2. The user is redirected to the password reset page.
  3. The user inputs a registered email.
  4. The user clicks on the "Reset Password" button.
- **Conditions of Success:** 
  - The user receives an email with password reset instructions.

---

## Scenario: Start Quiz

**Summary:** This scenario verifies that a user can start a quiz successfully from the dashboard.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is logged in and on the dashboard.
- **Chronological Tasks:**
  1. The user clicks on the "Start Quiz" button on the dashboard.
- **Conditions of Success:** 
  - The user is redirected to the quiz page and the quiz starts.

---

## Scenario: Submit Quiz

**Summary:** This scenario checks if the user can successfully submit a quiz and view the results.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is taking the quiz.
- **Chronological Tasks:**
  1. The user answers all questions in the quiz.
  2. The user clicks on the "Submit Quiz" button.
- **Conditions of Success:** 
  - The quiz is submitted successfully, and the user is shown the results.

---

## Scenario: View Quiz Results

**Summary:** This scenario verifies that the user can view their quiz results after submission.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user has completed and submitted a quiz.
- **Chronological Tasks:**
  1. The user clicks on the "View Results" button.
- **Conditions of Success:** 
  - The user can see a detailed view of their quiz results.

---

## Scenario: Log Out

**Summary:** This scenario checks if the user can log out successfully from the website.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is logged in.
- **Chronological Tasks:**
  1. The user clicks on the "Log Out" button.
- **Conditions of Success:** 
  - The user is logged out and redirected to the login page.

---

## Scenario: Resuming an Interrupted Quiz

**Summary:** This scenario verifies that the user can resume a quiz if their session was interrupted.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user had started a quiz but did not submit it.
- **Chronological Tasks:**
  1. The user logs back in.
  2. The user is prompted to resume the interrupted quiz.
- **Conditions of Success:** 
  - The user is able to resume the quiz from where they left off.

---

## Scenario: View Quiz History

**Summary:** This scenario verifies that the user can view their past quiz attempts and results.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is logged in and has completed at least one quiz.
- **Chronological Tasks:**
  1. The user navigates to the "Quiz History" section.
  2. The user views their past quiz attempts and results.
- **Conditions of Success:** 
  - The user can see a list of their previous quizzes with scores and details.

---

## Scenario: Navigation to Profile Settings

**Summary:** This scenario verifies that the user can access their profile settings from the dashboard.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is logged in.
- **Chronological Tasks:**
  1. The user clicks on the "Profile Settings" link/button.
- **Conditions of Success:** 
  - The user is redirected to the profile settings page.

---

## Scenario: Update Profile Information

**Summary:** This scenario verifies that the user can update their profile information.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the profile settings page.
- **Chronological Tasks:**
  1. The user updates their profile information (e.g., name, email, etc.).
  2. The user clicks on the "Save Changes" button.
- **Conditions of Success:** 
  - The profile information is updated successfully, and a confirmation message is displayed.

---

## Scenario: Change Password

**Summary:** This scenario checks if the user can change their password from the profile settings page.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the profile settings page.
- **Chronological Tasks:**
  1. The user inputs the current password.
  2. The user inputs a new password.
  3. The user confirms the new password.
  4. The user clicks on the "Change Password" button.
- **Conditions of Success:** 
  - The password is changed successfully, and a confirmation message is displayed.

---

## Scenario: Delete Account

**Summary:** This scenario checks if the user can delete their account from the profile settings page.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the profile settings page.
- **Chronological Tasks:**
  1. The user clicks on the "Delete Account" button.
  2. The user confirms the account deletion.
- **Conditions of Success:** 
  - The account is deleted successfully, and the user is redirected to the homepage with a confirmation message.

---
