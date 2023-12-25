# node_js Server
 AradServerNodeJS
This Node.js project serves as a server for managing user and card collections. Users can have different roles, including Regular User, Business User, and Admin User. The server handles CRUD operations on both user and card collections, providing a seamless experience for managing users and their associated cards.

Project Structure
public/: Contains HTML error pages for user-friendly error handling.

src/

schemas/: Contains the schemas for users and cards.
index.ts: Main entry point for the application.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/your-repository.git
Navigate to the project directory:

bash
Copy code
cd your-repository
Install dependencies:

bash
Copy code
npm install
Usage
Run the application:

bash
Copy code
npm start
Open your web browser and go to http://localhost:3000 to interact with the server.

Configuration
The application uses environment variables for configuration. Create a .env file in the root directory and set the following variables:

env
Copy code
PORT=3000
DATABASE_URL=mongodb://localhost:27017/your-database
Adjust the values according to your preferences and environment.

API Endpoints
Users
GET /api/users: Get all users.
GET /api/users/:userId: Get a specific user by ID.
POST /api/users: Create a new user.
PUT /api/users/:userId: Update a user.
DELETE /api/users/:userId: Delete a user.
Cards
GET /api/cards: Get all cards.
GET /api/cards/:cardId: Get a specific card by ID.
POST /api/cards: Create a new card.
PUT /api/cards/:cardId: Update a card.
DELETE /api/cards/:cardId: Delete a card.
Roles
Regular User: Basic user with standard privileges.
Business User: User with additional privileges for business-related actions.
Admin User: User with administrative privileges.
Error Handling
The server provides user-friendly error pages located in the public folder.

Contributing
If you would like to contribute to the project, please follow our Contribution Guidelines.

License
This project is licensed under the MIT License to Arad Ariel
