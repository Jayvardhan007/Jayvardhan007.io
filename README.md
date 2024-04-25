Welcome to TechTonicTales – Your Go-To Hub for Tech Stories and Updates!

**Introduction**  
TechTonicTales is a dynamic blog website crafted with the MERN stack (MongoDB, Express.js, React, Node.js). It serves as a vibrant community for tech enthusiasts to share, discover, and discuss the latest in technology.

**Features**  
- Secure user login and registration  
- Full CRUD functionality for blog entries  
- Ability to comment on posts  
- Clean, responsive, and intuitive interface  

**Technologies Utilized**  
- **MongoDB**: Serves as the backend database to store blog entries and user details  
- **Express.js**: Backend framework running on Node.js  
- **React**: Powers the frontend, creating a seamless user experience  
- **Node.js**: Provides the runtime environment for the backend  
- **Yarn**: Manages dependencies throughout the project  

**Getting Started**  
Here’s how you can get TechTonicTales up and running on your local machine.

**Installation Steps**  
1. **Clone the Repository**  
   Execute `git clone https://github.com/your-username/TechTonicTales.git` in your terminal.

2. **Project Setup**  
   Navigate to the project's root directory:  
   ```
   cd TechTonicTales
   ```

3. **Install Frontend Dependencies**  
   Switch to the client directory, and install the necessary packages:  
   ```
   cd client
   yarn install
   yarn start
   ```

4. **Install Backend Dependencies**  
   In a new terminal, move to the api directory and set up the backend:  
   ```
   cd api
   yarn install
   nodemon index.js
   ```

5. **Database Configuration**  
   Modify the `MONGODB_URL` in `index.js` to connect to your MongoDB instance.

6. **Launch the Application**  
   Open a web browser and visit `http://localhost:3000` to view the app.

**Contributing**  
We value community contributions! If you have ideas for improvements or find any issues, please feel free to fork the repository, make changes, and submit pull requests. You can also open issues for discussion.
