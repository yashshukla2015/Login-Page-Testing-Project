# 🧪 Login Page Testing Project  

## 📌 Project Overview  
This project demonstrates **manual testing of a Login Page**.  
The goal was to validate login functionality, input field constraints, and error handling to ensure secure and smooth user authentication.  

---

## 🎯 Objectives  
- Verify login with **valid and invalid credentials**.  
- Validate **forgot password functionality**.  
- Check **input field constraints** (length, special characters).  
- Ensure **proper error messages** are displayed.  

---

## 🔍 Scope of Testing  
- **Functional Testing** – Verify login, logout, forgot password.  
- **UI Testing** – Validate button alignment, input boxes, and error messages.  
- **Negative Testing** – Enter wrong inputs to check robustness.  
- **Boundary Value Testing** – Input length restrictions.  

---

## 📝 Test Scenarios  

| **ID** | **Scenario** | **Steps** | **Expected Result** |
|--------|--------------|-----------|----------------------|
| TC01 | Login with valid credentials | Enter correct username & password, click login | User should be redirected to dashboard |
| TC02 | Login with invalid username | Enter wrong username + correct password | Error message “Invalid Username or Password” |
| TC03 | Login with invalid password | Enter correct username + wrong password | Error message “Invalid Username or Password” |
| TC04 | Login with blank fields | Keep username/password blank & click login | Show validation “Fields cannot be empty” |
| TC05 | Forgot password flow | Click on "Forgot Password", enter registered email | Password reset link should be sent |
| TC06 | Input field length check | Enter more than 50 characters in username field | Field should restrict input / show error |
| TC07 | Special character check | Enter special chars in username | Proper validation/error message should appear |

---

## 🐞 Bug Tracking  
- Defects were logged and tracked using **Jira** (demo project).  
- Example bug: *Login button not disabled when fields are blank*.  

---

## ⚙️ Tools Used  
- **Jira / Excel** → Test case & bug tracking  
- **Browsers** → Chrome, Firefox, Edge  
- **Demo App** → [Practice Test Login Page](https://practicetestautomation.com/practice-test-login/)  

---



