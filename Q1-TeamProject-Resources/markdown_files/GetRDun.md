# GetRDun

## **Task Management Application**

### **Project Description**
Create a task management web app where users can create accounts to manage their to-do lists. Users can add, edit, delete, and categorize tasks, as well as mark them as complete.

### **Key Features**
- **User Authentication:**
  - Users can sign up, log in, and manage their profiles.
- **Task Management:**
  - Create new tasks with details like title, description, due date, and category.
  - Edit or delete existing tasks.
  - Mark tasks as complete or incomplete.
- **Categorization and Filtering:**
  - Assign categories to tasks (e.g., Work, Personal, Urgent).
  - Filter and sort tasks based on status, category, or due date.
- **Progress Tracking:**
  - Display statistics like total tasks, completed tasks, and pending tasks.
- **Notifications:**
  - Optional: Notify users of upcoming deadlines or overdue tasks.

### **Technical Requirements**
- **Frontend:**
  - User-friendly interface with HTML and CSS.
  - Forms for task creation, editing, and user authentication.
  - Client-side validation using JavaScript regex for inputs like task titles, dates, and categories.
- **Backend:**
  - Express.js server with RESTful API endpoints for handling tasks and user data.
  - Data storage using JSON files managed via the `fs` module.
- **Asynchronous Operations:**
  - Use `async/await` for all fetch requests and file read/write operations.
- **Additional Features:**
  - Implement search and filter functionality for tasks.
  - Ensure users can only access and modify their own tasks.
  - Responsive design for accessibility on various devices.

### **Project Milestones**
1. **Setup and Authentication:**
   - Initialize the project and implement secure user registration and login.
2. **Task CRUD Operations:**
   - Develop functionality to create, read, update, and delete tasks.
3. **Categorization and Filtering:**
   - Implement task categorization and filtering options.
4. **Progress Tracking and Notifications:**
   - Add progress tracking features and optional notification system.
5. **Final Enhancements:**
   - Refine UI, ensure data integrity, perform testing, and prepare presentations.

---