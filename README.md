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

![Screenshot from 2024-05-09 15-06-41](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/fe5f6e2d-c3c0-4924-973e-00aa10564886)


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
   
![Screenshot from 2024-05-09 15-35-39](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/f9e441b8-3dbc-4c96-842c-f8cf9f449720)

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
  
![Screenshot from 2024-05-09 16-07-47](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/df7d6f96-3daf-4d01-b830-8a7270881046)

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

![Screenshot from 2024-05-10 11-37-01](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/5236e1a6-822a-423b-82a6-60f51e2d06fe)

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

![Screenshot from 2024-05-20 17-38-07](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/94198086-487d-4332-90f5-c22dff35d0c9)

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


 ![Screenshot from 2024-05-21 12-46-10](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/c4ff4fbf-7ab6-4dc2-a171-2064c09fbbaf)


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

![Screenshot from 2024-05-21 13-20-49](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/15ed2f07-24ef-464e-abca-4a7088904124)


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

 ![Screenshot from 2024-05-24 04-23-53](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/88b85b8f-fcb6-4613-96c2-42a010ba3aa3)

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

![Screenshot from 2024-05-24 04-26-06](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/bf7ed84d-9733-4d18-9cd0-c24e6be3f0a8)


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

![Screenshot from 2024-05-24 04-38-32](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/0af387ec-8c24-4cd8-880d-79e02431866f)

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

![Screenshot from 2024-05-24 04-40-03](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/0c611b87-cf65-4068-ab28-bf44f3c04681)

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

![Screenshot from 2024-05-24 13-02-15](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/8ef7020e-ebaa-4eb2-9488-713ff20c33d6)


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
  - The user has successfully logged in.
  - The user is redirected to the 'Quiz' home page, and the logged-in user's email is displayed at the top right.

 ![image](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/d53c8250-af64-41a3-b291-590317abfc90)

---

## Scenario: Unsuccessful Login - Invalid Email Input

**Summary:** This scenario checks if users can log in properly and if the system handles errors correctly.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the login page.
- **Chronological Tasks:**
  1. The user inputs an invalid Email.
  2. The user inputs a password.
  3. The user clicks on the Login button.
- **Conditions of Success:** 
  - The login page displays a message saying 'Invalid email or password’
    
![Screenshot from 2024-05-21 15-05-14](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/417583c5-68e5-4143-9ae8-dcb3a12d0af7)


---

## Scenario: Display Password on Login Page

**Summary:** This scenario checks if users can see their password as they type it on the Login page, ensuring the "Show Password" feature works properly.

**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the login page.
- **Chronological Tasks:**
  1. The user inputs a password.
  2. The user clicks the "Show Password" option located directly below the password input field.

 - **Conditions of Success:** 
  - The user is able to see the password displayed in the password input box.

    ![Screenshot from 2024-05-22 13-30-37](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/fd0afd82-4520-4e11-809e-92e150386b76)


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
  - The login page displays a message saying 'Invalid email or password’

![image](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/025023cc-22ec-4263-b785-038dc937dbd7)

---

## Scenario: Navigate to Forgot Password

**Summary:** This scenario checks that users can navigate to the "Forgot Password" page to initiate the password recovery process.


**Description:**
- **Environment:** 
  - Internet
  - Web browser
- **Prerequisite:** The user is on the login page.
- **Chronological Tasks:**
  -The user clicks on ‘Forgot Password?’
  
- **Conditions of Success:** 
  -The user is successfully redirected to the "Forgot Password" page.

![Screenshot from 2024-05-21 15-39-05](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/66e8a61b-b04e-46fe-a88b-694a8b98a24d)

## Scenario: Submit Email for Password Recovery

**Summary:** This scenario checks that users can successfully submit their email address on the "Forgot Password" page and receive a password reset email.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the Forgot Password page.

**Chronological Tasks:**
1. The user inputs an email.
2. The user clicks on the ‘Submit’ button.

**Conditions of Success:**
- A password reset email is sent successfully to the user's email, and a pop-up message displays: 'Password reset email sent.'
- The user received the reset password link in his email.
  
![Screenshot from 2024-05-22 16-53-40](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/83d95368-5dc1-4ea5-a4a6-e3ba0f540283)

![image](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/8350cfdf-a359-404b-b93f-1fe31c292aaf)

---

## Scenario: Submit Incorrect Email for Password Recovery

**Summary:** This scenario tests when a user submits an incorrect email address on the "Forgot Password" page for password recovery.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the Forgot Password page.

**Chronological Tasks:**
1. The user inputs an invalid email.
2. The user clicks on the ‘Submit’ button.

**Conditions of Success:**
- The user is displayed the message “User not found.”
- The user is unable to reset the password.

![Screenshot from 2024-05-22 13-16-27](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/a1431080-6698-490e-8574-463d9cd68899)


---

## Scenario: Navigate Password Reset Page

**Summary:** This scenario checks that users can successfully navigate to the password reset page by clicking the reset password link received in the email.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the password reset link email page.

**Chronological Tasks:** The user clicks on the link.

**Conditions of Success:** The user is successfully redirected to the reset password page.

![Screenshot from 2024-05-22 12-31-00](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/17e82475-6e5f-4f3a-b3d2-6c3205ad7e48)

---

## Scenario: Reset Password

**Summary:** This scenario checks that users can successfully reset their password.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the reset password page.

**Chronological Tasks:**
1. The user inputs a new password that is between 8 to 15 characters and strong enough.
2. The user inputs the confirm password, which is the same as the new password.
3. The user clicks on the ‘Reset Password’ button.

**Conditions of Success:** The user password is successfully reset, and a pop-up message displays: "Password is reset successfully.”

![Screenshot from 2024-05-22 17-26-29](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/58680719-ff9e-4076-98fc-deb4c321a6e2)

---

## Scenario: Display Password on Reset Password Page

**Summary:** This scenario checks if users can see their password as they type it on the reset password page, ensuring the "Show Password" feature works properly.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** User is on the website's Reset Password page.

**Chronological Tasks:**
1. The user inputs a password.
2. The user clicks the 'Eye Icon' located on the right side within the box.

**Conditions of Success:** The user is able to see the password displayed in the password box.

![Screenshot from 2024-05-22 12-26-46](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/968fb620-c1bc-41db-9eb4-51992a4bfaa3)

---

## Scenario: Unsuccessful Reset Password Due to Password Length

**Summary:** This test case verifies the behavior of the Reset Password process when the password provided does not meet the length requirement.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the Reset Password page.

**Chronological Tasks:**
1. The user inputs a new password of less than 8 characters.
2. The user inputs the confirm password, which is the same as the new password.

**Conditions of Success:** An error pop-up message is displayed: "Password must be between 8 and 15 characters long.”

![Screenshot from 2024-05-24 10-31-19](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/85713396-878b-4275-ac1e-07a112e2226c)

---

## Scenario: Unsuccessful Reset Password Due to Missing Upper Case Letter in Password

**Summary:** This test case verifies the behavior of the Reset Password process when the password provided does not meet strength requirements.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the Reset Password page.

**Chronological Tasks:**
1. The user inputs a new password without an upper case letter.
2. The user inputs the confirm password, which is the same as the new password.

**Conditions of Success:** An error pop-up message is displayed: "Password must contain at least one uppercase letter, one lowercase letter, one digit, and one special character.”

![Screenshot from 2024-05-24 11-02-37](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/dadb3aae-22d9-4353-bb8a-3c9d25b8e491)

---

## Scenario: Unsuccessful Reset Password Due to Missing Lower Case Letter in Password

**Summary:** This test case verifies the behavior of the Reset Password process when the password provided does not meet strength requirements.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the Reset Password page.

**Chronological Tasks:**
1. The user inputs a new password without a lower case letter.
2. The user inputs the confirm password, which is the same as the new password.

**Conditions of Success:** An error pop-up message is displayed: "Password must contain at least one uppercase letter, one lowercase letter, one digit, and one special character.”

![Screenshot from 2024-05-24 12-27-57](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/997ae98f-bbfc-4eaa-9126-4822e03b55b2)

---

## Scenario: Unsuccessful Reset Password Due to Missing Special Character in Password

**Summary:** This test case verifies the behavior of the Reset Password process when the password provided does not meet strength requirements.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the Reset Password page.

**Chronological Tasks:
1. The user inputs a new password without a special character.
2. The user inputs the confirm password, which is the same as the new password.

**Conditions of Success:** An error pop-up message is displayed: "Password must contain at least one uppercase letter, one lowercase letter, one digit, and one special character.”

![Screenshot from 2024-05-24 12-31-10](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/2c14379c-9b90-48a5-884d-d81414141d8a)

---

## Scenario: Unsuccessful Reset Password Due to Missing Digit in Password

**Summary:** This test case verifies the behavior of the Reset Password process when the password provided does not meet strength requirements.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the Reset Password page.

**Chronological Tasks:
1. The user inputs a new password without a digit.
2. The user inputs the confirm password, which is the same as the new password.

**Conditions of Success:** An error pop-up message is displayed: "Password must contain at least one uppercase letter, one lowercase letter, one digit, and one special character.”

![Screenshot from 2024-05-24 13-09-17](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/455c4087-a346-425b-be3a-7c34c0c9ba5a)

---

## Scenario: New Password and Confirm Password Mismatch

**Summary:** This scenario verifies the functionality of the new password and confirm password validation.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the Reset Password page.

**Chronological Tasks:
1. The user inputs ‘New Password’
2. The user inputs a different password in ‘Confirm Password’
3. The user clicks on the Reset Password button.

**Conditions of Success:** An error message is displayed: "Passwords do not match."

![Screenshot from 2024-05-22 12-27-44](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/f6590825-d441-48f6-b13b-07c859d41798)

---

## Scenario: Color Hover Effect of Sidebar Influencer

**Summary:** This scenario evaluates the functionality of the color hover effect of Influencer on the sidebar of the quiz homepage.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the homepage of the 'Quiz' page.

**Chronological Tasks:** The user moves the cursor over a particular name of an open source influencer in the left sidebar on the quiz homepage.

**Conditions of Success:** The color of the particular open source influencer's name changes to pink.

![Screenshot from 2024-05-20 17-49-00](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/140cf50d-084c-47f5-8796-47cab63cbd85)

![Screenshot from 2024-05-20 17-45-25](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/7d4fd650-f7d7-4cec-b197-2a5ac4247599)


---

## Scenario: The Hover Effect Color of Sidebar Influencer Reverts to Its Original State

**Summary:** This scenario evaluates the functionality of the color hover effect on the sidebar of the quiz homepage.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the homepage of the 'Quiz' page.

**Chronological Tasks:** The user moves the cursor away from the particular name of an open source influencer.

**Conditions of Success:** The color of the particular open source influencer name reverts to its original state.

![Screenshot from 2024-05-20 17-49-00](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/d8ffa1e6-cfd2-4bdb-a243-a914b2074c93)

---

## Scenario: Reading Information about Open Source Influencers

**Summary:** Test the functionality of information related to open source influencers.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the homepage of the 'Quiz' page.

**Chronological Tasks:** The user selects the name of the open source influencer from the left sidebar on the quiz homepage.

**Conditions of Success:** The user is redirected to the info page of a specific open source influencer.

![Screenshot from 2024-05-10 12-55-36](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/942c1de5-417e-4c70-8324-8e7121b98164)

---

## Scenario: User Wants to Learn More about an Open Source Influencer

**Summary:** Check if we can access more info about open source influencers.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the info page of a particular Open Source Influencer.

**Chronological Tasks:** The user clicks on the 'Read More' button situated at the bottom of the page.

**Conditions of Success:** The user is redirected to the Wikipedia page associated with the open source influencer.

![Screenshot from 2024-05-10 13-15-18](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/bd09edf3-81a4-41d5-8434-c9542bf56ddf)

![Screenshot from 2024-05-10 13-16-11](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/edeb06d1-d7ae-48d1-83cb-1ea570b42785)


---

## Scenario: User Redirects from Information Page to Home Page

**Summary:** Verify that users are correctly redirected from the information page to the quiz page upon clicking the 'Home' button.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the info page of a particular Open Source Influencer.

**Chronological Tasks:** The user clicks on the 'Home' button situated at the bottom of the information page.

**Conditions of Success:** The user is redirected to the quiz page of the website.

![Screenshot from 2024-05-10 13-15-18](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/32da238a-c89c-4a50-98e9-aa3b86534669)

![Screenshot from 2024-05-08 12-07-10](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/4b6f554f-a4ce-4dfa-9667-8899673addd7)

---

## Scenario: Quiz Boxes Zoom In Hover Effect

**Summary:** This test case verifies the functionality of the zoom-in hover effect on quiz boxes.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the quiz homepage where quiz boxes are displayed.

**Chronological Tasks:** The user moves the cursor over a particular quiz box.

**Conditions of Success:** The box gradually zooms in.
![image](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/db338cd4-4a25-44d9-bd59-93dd5f1870ee)

![image](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/6da042d0-6239-4501-aa19-2cca1ffe3946)

---

## Scenario: Quiz Boxes Return to Regular Size

**Summary:** This test case verifies the functionality of the zoom-out hover effect on quiz boxes.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user cursor is on a particular quiz box.

**Chronological Tasks:** The user moves the cursor away from the quiz box.

**Conditions of Success:** The box returns to its regular size.

![image](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/29c9e32a-c1e3-4510-bca6-e2125c76e274)

![image](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/9fbcc020-e9fd-40dd-81e0-1463c636a2ff)

---

## Scenario: Start Quiz

**Summary:** This test checks if users can begin the quiz by clicking the "Start quiz" button on the quiz page.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the quiz page of the website to initiate the test.

**Chronological Tasks:** The user clicks the "Start Quiz" button.

**Conditions of Success:** The user is directed to the "MCQ" page.

![Screenshot from 2024-05-13 11-44-42](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/781f1cc1-eb25-4d33-ac29-e8a395e9026b)

---

## Scenario: Color Hover Effect of Quiz MCQ Options

**Summary:** This scenario checks the functionality of the color hover effect on multiple-choice questions (MCQs) options displayed on the quiz page.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the MCQ quiz page.

**Chronological Tasks:** The user moves the cursor over the MCQ options.

**Conditions of Success:** The color of the multiple-choice question (MCQ) option changes to yellow.

![Screenshot from 2024-05-13 11-45-04](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/e8f9f977-51df-4d1a-9b7d-3681e40c7d23)

---

## Scenario: The Hover Effect Color of Quiz MCQ Options Reverts to Its Original State

**Summary:** This scenario checks the functionality of the color hover effect on multiple-choice questions (MCQs) options displayed on the quiz page.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the MCQ quiz page.

**Chronological Tasks:** The user moves the cursor away from the quiz MCQ options.

**Conditions of Success:** The color of the MCQ option reverts to its original state.

![Screenshot from 2024-05-13 11-44-42](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/9dd5357e-2db3-4cf8-99b0-939589b64ba3)

---

## Scenario: Attempt Multiple Choice Questions

**Summary:** This test checks if users can answer questions on the MCQ page by clicking the correct answer for each question.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the "MCQ" page of the website.

**Chronological Tasks:** User selects options for multiple-choice questions.

**Conditions of Success:** The color of the multiple-choice question (MCQ) option changes to green.

![Screenshot from 2024-05-13 11-35-56](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/76d7d1d9-b6bc-4735-8848-66b55c07a801)

---

## Scenario: Mandatory to Attempt All Questions

**Summary:** This scenario checks whether users are required to attempt all questions before submitting.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the multiple-choice question (MCQ) page of the website.

**Chronological Tasks:
1. The user does not attempt all questions in the quiz.
2. The user clicks on the submit button.

**Conditions of Success:** A pop-up appears with the message "Please answer all questions before submitting.”

![Screenshot from 2024-05-13 11-36-23](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/52b5022b-4bbc-4469-8837-7fc72b94916c)

---

## Scenario: Submit MCQ’s Response

**Summary:** This scenario checks the functionality of the MCQ page, ensuring that users can submit their answers.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the "MCQ" page.

**Chronological Tasks:
1. User selects all MCQ options.
2. User clicks on the "Submit" button located at the bottom of the page.

**Conditions of Success:**
- The user is directed to the result page.
- The user can view their score and percentage in purple color.
- The user can see their chosen correct answers in green color and wrong answers in red color.
- The user can see the correct answer displayed below the chosen answer in green color.
- The user can also view explanations related to the question in blue color.

![Screenshot from 2024-05-20 17-53-19](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/2b9248e5-52a6-45a1-be4f-f7645c051e79)

---

## Scenario: User Directs from Result Page to Home Page

**Summary:** This test makes sure that when users click the "Home" button on the result page, they are taken back to the home page.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the result page of the website.

**Chronological Tasks:** The user needs to click on the "Home" button located at the bottom of the page.

**Conditions of Success:** The user is directed to the quiz home page.

![Screenshot from 2024-05-21 14-48-38](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/cabb5f79-ac03-492c-8160-6b7caa4021f3)

---

## Scenario: Logout Option Zooms in with Yellow Color

**Summary:** This scenario verifies whether the logout button enlarges and turns yellow when the mouse is hovered over it.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the homepage of the quiz website.

**Chronological Tasks:** The user moves the cursor on the logout button located at the top right of the home page.

**Conditions of Success:** The logout button zooms in and turns yellow.

 ![Screenshot from 2024-05-22 03-21-16](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/e84de417-aba0-4089-afc0-bc0956d6c743)

![Screenshot from 2024-05-22 03-23-26](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/86403a4e-ae0a-42fc-ae60-65f5f2999f9f)

---

## Scenario: Logout Option Returns to Regular Size and Color

**Summary:** This scenario involves the logout option returning to its regular size and color.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user cursor is on ‘Logout’ button.

**Chronological Tasks:** The user moves the cursor away from the 'Logout' button.

**Conditions of Success:** The 'Logout' button reverts to its regular size and color.

![Screenshot from 2024-05-22 03-23-26](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/f5cbf0d7-0c38-47db-9dfb-7636710af1b5)

![Screenshot from 2024-05-22 03-21-16](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/d5a8beb7-a017-47bf-9c90-7ca879d3de5c)

---

## Scenario: User Logs Out from the Quiz

**Summary:** This scenario describes the process for a user to logout from the quiz website if the user does not want to take the quiz.

**Description**

**Environment:**
- Internet
- Web browser

**Prerequisite:** The user is on the homepage of quiz website.

**Chronological Tasks:** The user clicks on the logout button positioned at the top right of the homepage.

**Conditions of Success:** The user successfully logs out and is redirected to the login page.

![Screenshot from 2024-05-22 03-28-05](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/b2abde47-1cef-4b20-9534-f1978d542379)

![Screenshot from 2024-05-22 13-29-35](https://github.com/ErSachinBhati/Quiz-Project-Test-Cases/assets/158732178/53eeba55-16b7-4f61-b6f9-7246a0428fc2)

