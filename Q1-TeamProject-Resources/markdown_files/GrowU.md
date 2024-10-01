# Grow U

## **Health & Mental Wellness Tracking App**

### **Project Description**
Create a web application that allows users to track their physical exercises, running logs, and maintain a wellness diary for activities like meditation and mood tracking. The app promotes personal well-being by enabling users to monitor and reflect on their health and mental state.

### **Key Features**
- **User Authentication:**
  - Users can sign up, log in, and manage their profiles.
- **Exercise Logging:**
  - Users can add, edit, and delete exercise entries (e.g., type of exercise, duration, intensity).
- **Running Logs:**
  - Track running activities with details like distance, time, pace, and route (optional integration with maps).
- **Wellness Diary:**
  - Users can write daily entries about their mental state, meditation sessions, sleep quality, etc.
- **Progress Tracking:**
  - Visual representations (charts/graphs) of exercise frequency, running progress, and diary trends over time.
- **Goal Setting:**
  - Users can set and monitor personal health and wellness goals.
- **Notifications & Reminders:**
  - Optional: Remind users to log activities or meditate.

### **Technical Requirements**
- **Frontend:**
  - Clean and responsive UI using HTML and CSS.
  - Forms for logging exercises, running activities, and diary entries.
  - Client-side validation using JavaScript regex for inputs like dates, times, distances, and text fields.
  - Visualization tools (e.g., Chart.js) for displaying progress charts.
- **Backend:**
  - Express.js server with RESTful API endpoints for handling user data, exercises, runs, and diary entries.
  - Data storage using JSON files managed via the `fs` module.
  - Optional integration with third-party APIs for map routes or authentication enhancements.
- **Asynchronous Operations:**
  - Use `async/await` for all fetch requests and file read/write operations.
- **Additional Features:**
  - Secure password handling (hashing).
  - Data encryption for sensitive information if applicable.
  - Responsive design for accessibility on various devices.
  - Option to export logs and diary entries (e.g., as PDF or CSV).

### **Project Milestones**
1. **Setup and Authentication:**
   - Initialize the project and implement secure user registration and login.
2. **Logging Functionalities:**
   - Develop forms and backend routes for adding, editing, and deleting exercise and running logs.
3. **Wellness Diary:**
   - Implement diary entry creation, editing, and deletion.
4. **Progress Visualization:**
   - Integrate charts/graphs to display user progress and trends.
5. **Final Enhancements:**
   - Add goal setting, notifications (if implemented), refine UI, perform testing, and prepare presentations.