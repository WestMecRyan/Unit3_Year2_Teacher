# Project Roles

## **1. Suggested Roles for Each Group**

For groups of **4-6 students**, here are **four primary roles** and **two optional roles** to accommodate all group sizes:

### **Primary Roles**

1. **Project Coordinator**

   - **Responsibilities:**
     - Manages the project timeline and ensures tasks are on track.
     - Facilitates communication within the team.
     - Assists in task assignments and monitors progress.
   - **Skills Needed:**
     - Organizational and leadership skills.
     - Effective communication.

2. **Frontend Developer**

   - **Responsibilities:**
     - Designs and implements the user interface using HTML, CSS, and JavaScript.
     - Ensures responsive design and good user experience.
     - Implements client-side form validation using JavaScript regex.
   - **Skills Needed:**
     - Proficiency in HTML, CSS, JavaScript.

3. **Backend Developer**

   - **Responsibilities:**
     - Develops server-side logic using Express.js.
     - Implements RESTful API endpoints.
     - Manages data storage using JSON files and the `fs` module.
   - **Skills Needed:**
     - Knowledge of Node.js and Express.js.
     - Experience with asynchronous programming using `async/await`.

4. **Data Manager**
   - **Responsibilities:**
     - Designs data structures and manages JSON data files.
     - Ensures data integrity and handles file read/write operations.
   - **Skills Needed:**
     - Understanding of data structures and file systems.
     - Attention to detail.

### **Optional Roles**

5. **Tester/QA Specialist**

   - **Responsibilities:**
     - Tests application features and identifies bugs.
     - Ensures the application meets the project requirements.
   - **Skills Needed:**
     - Analytical skills.
     - Attention to detail.

6. **UI/UX Enhancer**
   - **Responsibilities:**
     - Improves the user interface and experience.
     - Ensures the application is user-friendly and accessible.
   - **Skills Needed:**
     - Design skills.
     - Understanding of user experience principles.

---

# Project Timeline

## **2. 7-Day Project Timeline**

### **Overview**

Given the time constraints, the focus will be on implementing core functionalities and ensuring a functional application by the end of the week. Advanced features and enhancements can be considered if time permits.

### **Daily Breakdown**

#### **Day 1: Project Kickoff and Setup**

- **Objectives:**
  - Introduce project ideas and assign roles.
  - Set up the project structure and tools.
- **Tasks:**
  - Assign roles within each group.
  - Set up a Git repository for version control.
  - Create initial project structure (folders for frontend, backend, data).
  - Set up basic Express.js server and routes.

#### **Day 2: Data Modeling and Basic Backend Routes**

- **Objectives:**
  - Design data models based on project requirements.
  - Implement basic backend routes.
- **Tasks:**
  - Data Manager designs JSON data structures.
  - Backend Developer sets up basic API endpoints (e.g., user registration, data retrieval).
  - Ensure file operations use `async/await`.

#### **Day 3: Frontend Development and Form Validation**

- **Objectives:**
  - Develop the frontend interface.
  - Implement client-side form validation using regex.
- **Tasks:**
  - Frontend Developer creates HTML and CSS for forms (e.g., registration, data entry).
  - Implement JavaScript regex validation for form inputs.
  - Set up basic navigation and UI elements.

#### **Day 4: Connecting Frontend and Backend**

- **Objectives:**
  - Integrate frontend forms with backend APIs.
  - Implement data submission and retrieval.
- **Tasks:**
  - Frontend Developer uses Fetch API with `async/await` to communicate with backend.
  - Test data flow from frontend to backend and vice versa.
  - Handle responses and errors appropriately.

#### **Day 5: Implement Core Functionalities**

- **Objectives:**
  - Develop core features specific to the project.
- **Tasks:**
  - Implement CRUD operations for main entities (e.g., flights, bank transactions, recipes, wellness logs).
  - Ensure data is correctly stored and retrieved from JSON files.
  - Backend Developer and Data Manager collaborate on data handling.

#### **Day 6: Testing and Debugging**

- **Objectives:**
  - Identify and fix any issues in the application.
- **Tasks:**
  - Tester/QA Specialist conducts thorough testing of all features.
  - Developers fix bugs and improve code based on feedback.
  - Ensure that form validations, data storage, and API endpoints are working correctly.

#### **Day 7: Final Touches and Presentation Preparation**

- **Objectives:**
  - Polish the application.
  - Prepare for the final presentation.
- **Tasks:**
  - UI/UX Enhancer improves the user interface and experience.
  - Project Coordinator ensures all requirements are met.
  - Prepare a demo and presentation showcasing the application's features.
  - Write a README file with project information and instructions.

---

## **3. Detailed Daily Breakdown**

### **Day 1: Project Kickoff and Setup**

**Time Allocation (1.5 hours):**

- **15 minutes:** Project introduction and role assignments.
- **15 minutes:** Discuss project requirements and define core features.
- **30 minutes:** Set up Git repository and project structure.
- **30 minutes:** Backend Developer sets up basic Express.js server.
- **Extra Time:** Address any questions or challenges in setup.

**Goals:**

- All team members understand the project goals and their roles.
- Project structure is in place with initial files and folders.
- Basic server is running and accessible.

### **Day 2: Data Modeling and Basic Backend Routes**

**Time Allocation (1.5 hours):**

- **30 minutes:** Data Manager designs data models (JSON structures).
- **45 minutes:** Backend Developer implements basic API endpoints.
  - **User Registration and Login Routes** (if applicable).
  - Ensure endpoints use `async/await` for file operations.
- **15 minutes:** Team reviews backend progress.

**Goals:**

- Data models are defined and documented.
- Basic backend routes are functional and tested (e.g., using Postman).

### **Day 3: Frontend Development and Form Validation**

**Time Allocation (1.5 hours):**

- **45 minutes:** Frontend Developer creates HTML/CSS for forms.
  - Registration, login, data entry forms relevant to the project.
- **30 minutes:** Implement client-side validation with JavaScript regex.
  - Validate inputs like email, passwords, dates, etc.
- **15 minutes:** Team reviews frontend progress.

**Goals:**

- Frontend forms are designed and functional.
- Form validations prevent incorrect data submission.

### **Day 4: Connecting Frontend and Backend**

**Time Allocation (1.5 hours):**

- **45 minutes:** Frontend Developer uses Fetch API to connect forms to backend.
  - Implement `async/await` in fetch requests.
- **30 minutes:** Test data submission and handle responses.
  - Display success or error messages to the user.
- **15 minutes:** Fix any issues in the integration.

**Goals:**

- Frontend and backend communicate effectively.
- Data submitted from forms is received and processed by the server.

### **Day 5: Implement Core Functionalities**

**Time Allocation (1.5 hours):**

- **30 minutes:** Backend Developer and Data Manager implement CRUD operations.
  - Create, Read, Update, Delete operations for main entities.
- **30 minutes:** Frontend Developer creates interfaces for these operations.
  - For example, pages to display data, forms to update or delete entries.
- **30 minutes:** Test CRUD functionalities end-to-end.

**Goals:**

- Core features of the application are implemented and functional.
- Users can perform main tasks (e.g., add a flight, make a transaction).

### **Day 6: Testing and Debugging**

**Time Allocation (1.5 hours):**

- **45 minutes:** Tester/QA Specialist conducts testing.
  - Test all features, form validations, data storage.
- **30 minutes:** Developers fix bugs identified during testing.
- **15 minutes:** Retest fixed issues to ensure they are resolved.

**Goals:**

- Application is stable and free of major bugs.
- All functionalities work as intended.

### **Day 7: Final Touches and Presentation Preparation**

**Time Allocation (1.5 hours):**

- **30 minutes:** UI/UX Enhancer improves the user interface.
  - Enhance aesthetics, ensure responsiveness.
- **30 minutes:** Team prepares the presentation.
  - Decide who will present which parts.
  - Prepare demonstration of key features.
- **30 minutes:** Final review and practice.
  - Run through the presentation.
  - Ensure all team members are ready.

**Goals:**

- Application is polished and ready to present.
- Team is prepared for the presentation.

---

## **Example Application of the Provided Code**

Using the sample code provided, students can:

- **Use the Express.js server setup as a starting point.**
  - They can modify the routes to fit their project's needs.
- **Understand how to perform file operations with `fs` and `async/await`.**
  - Read and write data to JSON files.
- **Implement form handling on the frontend.**
  - Use the example of form submission and Fetch API calls.
- **Handle CRUD operations.**
  - Modify the `app.post`, `app.put`, and `app.delete` routes for their specific data.

---

## **Key Points to Emphasize**

- **Time Management:**
  - With limited time, prioritize core functionalities.
  - Advanced features can be considered only if time allows.
- **Collaboration:**
  - Regular communication is essential.
  - Use tools like GitHub Issues or a shared document to track tasks.
- **Testing:**
  - Testing should be integrated throughout the development process.
  - Early identification of issues saves time in the long run.
- **Presentation:**
  - Focus on demonstrating the core features that were implemented.
  - Be prepared to discuss challenges faced and how they were overcome.

---

## **Final Notes**

- **Flexibility:** Adjust the plan as needed based on the group's progress.
- **Support:** Encourage students to help each other and share knowledge.
- **Learning Opportunity:** Emphasize that the goal is to learn and apply their skills, not just to complete the project.
