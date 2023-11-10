# Employee-Review-System
A FullStack, app used for reviewing co-employees in an organisation.


### Description
A FullStack app, it lets the Admin assign to employees to review their co-employees on the basis of their work. The Admin can add new employee, assign the reviewer and reviewee, see the list of all the employee current in the organisation. On the basis of the reviews admin can also remove or make an employee an admin.

### Tech Stack

 Mongodb , ExpressJS , EJS , javaScript ,HTML, css, NodeJS

### How to setup the project on local system
#### Prerequisite 
  Node js Should be installed 

  1. Clone this project
  2. Navigate to Project Directory.
  3. Open the project in VS Code or your preffered code viewer
  4. Go to the terminal in code viewer and type
  
      ```
        npm install 
        npm start
     ```
  5. Open browser after running the server and type
  
      ```
      localhost:5000
      ```
  6. Admin Code is `1234`

## Folder Structure
   ```
   Habit Tracker
    |
    |                  |--->css
    |--->assets------->|--->img
    |                  |---> js|-->home.js
    |                          |-->noty.js
    |
    |                  |--->flash_middleware.js
    |--->config------->|--->mongoose.js
    |                  |--->passport-local-stargety.js
    |
    |                  |-->adminController.js
    |                  |-->homeController.js
    |--->controllers-->|-->reviewController.js
    |                  |-->userController.js
    |
    |--->models------->|-->review.js
    |                  |-->user.js
    |
    |              
    |                  |-->admin.js
    |--->routes------->|-->index.js
    |                  |-->review.js
    |                  |-->user.js
    |
    |
    |              
    |                  |--->_footer.ejs
    |                  |--->_header.ejs
    |                  |--->addEmployee.ejs
    |                  |--->assignTask.ejs
    |                  |--->employee_list.ejs
    |--->views-------->|--->home.ejs
    |                  |--->layout.ejs
    |                  |--->user_sign_in.ejs
    |                  |--->user_sign_up.ejs
    |
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
   ```

## Live Demo
https://employee-review-system-by-ritesh.onrender.com
  
  

  

