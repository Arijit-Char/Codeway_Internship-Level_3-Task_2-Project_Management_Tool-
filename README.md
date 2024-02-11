Codeway Internship Level 3 - Task 2: Product Management Tool
This Product Management Tool is developed as part of the Codeway Internship Level 3 Task 2. It provides a platform for managing products efficiently using the MERN stack (MongoDB, Express.js, React.js, Node.js).

Description
The Product Management Tool allows users to perform various operations related to product management, including adding new products, updating existing ones, and deleting products. It offers a user-friendly interface designed to streamline product management tasks.

Features
User Authentication: Secure user authentication system with login and registration functionality.
Product CRUD Operations: Create, Read, Update, and Delete operations for managing products effectively.
Dashboard: Provides a dashboard view with summary statistics and insights on product data.
Responsive Design: Responsive layout ensuring optimal user experience across different devices.
Data Persistence: Utilizes MongoDB as the database backend for reliable data storage and retrieval.
Technologies Used
Frontend:
React.js
React Router
Axios (for HTTP requests)
Material-UI (for UI components)
Backend:
Node.js
Express.js
MongoDB (with Mongoose ORM)
Authentication:
JSON Web Tokens (JWT) for user authentication
bcrypt.js for password hashing
Installation
Clone the repository:

bash
Copy code
git clone <repository-url>
Navigate to the project directory:

bash
Copy code
cd product-management-tool
Install dependencies:

bash
Copy code
cd client && npm install
cd ../server && npm install
Create a .env file in the server directory and configure environment variables:

makefile
Copy code
PORT=5000
MONGODB_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
Start the server:

bash
Copy code
cd ../server && npm start
Start the client:

bash
Copy code
cd ../client && npm start
Open your browser and navigate to http://localhost:3000 to access the application.

Usage
Register a new account or log in with an existing account.
Access the dashboard to view summary statistics and insights.
Perform CRUD operations on products, including adding, editing, and deleting products.
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any bug fixes, improvements, or feature requests.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
This Product Management Tool is developed as part of the Codeway Internship Level 3 program. Special thanks to the Codeway team for their guidance and support throughout the development process.

