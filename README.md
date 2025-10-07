# DemoBlaze QA Testing Project

## Project Overview
This is a **Manual QA Testing self-project** for the e-commerce website [DemoBlaze](https://www.demoblaze.com).  
The project demonstrates testing skills through **Login, Signup, and Cart/Place Order modules**, including **exploratory and regression testing**.

---

## Modules Tested
1. **Login**
   - Valid and invalid login
   - Username case sensitivity
   - Lockout / repeated login attempts
   - Browser auto-fill behavior
2. **Signup**
   - Duplicate username scenario
   - Case-sensitive username issues
   - Special character validation
3. **Cart / Place Order**
   - Adding/deleting products
   - Validation of required fields
   - Handling invalid data in credit card and other fields
   - Confirmation popup behavior
4. **Products / Categories**
   - Product listing, description, and images
   - Category filters
   - Pagination

---

## Test Coverage
- **Total Test Cases Executed:** 44  
- **Test Types:**
  - Manual Testing
  - Exploratory Testing
  - Regression Testing
- **Observations / Improvements documented in TestRail**  
- **Reports generated in Word format** 

---

## Tools Used
- **TestRail**: For tracking and executing test cases  
- **Microsoft Word**: For generating Bug/Improvement and Closing Reports  
- **Web Browser (Chrome)**: For manual testing  

---

## Key Observations / Bugs
- Login lockout not implemented for repeated invalid attempts  
- Username is case-sensitive in Login and Signup  
- Duplicate accounts allowed with case-variant usernames  
- Special characters allowed in username (`@_#`)  
- Cart / Place Order accepts invalid/dummy data  
- Confirmation popup in Place Order remains after multiple purchases  

All observations are documented and logged in **TestRail and Bug/Improvement Reports**.

---





```bash
git clone https://github.com/yourusername/DemoBlaze-QA-Project.git
