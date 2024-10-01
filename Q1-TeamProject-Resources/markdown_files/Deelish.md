# DEELISH

## **Recipe Sharing Platform**

### **Project Description**
Build a web application where users can create accounts to share, search, and manage recipes. Users can add new recipes, edit or delete their own recipes, and browse or search for recipes shared by others.

### **Key Features**
- **User Authentication:**
  - Users can sign up, log in, and manage their profiles.
- **Recipe Management:**
  - Create new recipes with details like ingredients, instructions, and images.
  - Edit or delete their own recipes.
- **Search and Browse:**
  - Search for recipes by name, ingredients, or categories.
  - Browse recipes by categories or popularity.
- **Favorites:**
  - Users can mark recipes as favorites and view their favorite list.
- **Comments and Ratings:**
  - Allow users to comment on and rate recipes.

### **Technical Requirements**
- **Frontend:**
  - Responsive design with intuitive navigation using HTML and CSS.
  - Forms for recipe creation, editing, and user authentication.
  - Client-side validation using JavaScript regex for inputs like recipe titles, ingredient lists, and instructions.
- **Backend:**
  - Express.js server with RESTful routes for handling recipes and user data.
  - Store data in JSON files managed via the `fs` module.
  - Handle image uploads (could be stored as URLs or base64 strings for simplicity).
- **Asynchronous Operations:**
  - Use `async/await` for all fetch requests and file operations.
- **Additional Features:**
  - Implement search functionality with filters.
  - Ensure users can only modify their own recipes.
  - Provide pagination for recipe listings if necessary.

### **Project Milestones**
1. **Setup and Authentication:**
   - Initialize project and implement user registration and login.
2. **Recipe CRUD Operations:**
   - Develop functionality to create, read, update, and delete recipes.
3. **Search and Browse Features:**
   - Implement search functionality and category browsing.
4. **Favorites and Comments:**
   - Allow users to favorite recipes and add comments/ratings.
5. **Final Enhancements:**
   - Improve UI/UX, optimize search, perform testing, and prepare presentations.

---