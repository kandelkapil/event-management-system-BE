Event Management Project

Description

This is an Event Management project built using the Model-View-Controller (MVC) design pattern. The project is implemented in Node.js and uses PostgreSQL as the database. Sequelize is employed as the ORM, JWT is used for token authentication, Multer handles image uploads, and TypeScript enhances code maintainability.

Routes

Auth Route:

Login: Endpoint for user login.
Logout: Endpoint for user logout.
Signup: Endpoint for user registration.
Refresh Token: Endpoint to refresh JWT tokens.

Event Route:

Get Event by ID: Retrieve event details by ID.
Create Event: Create a new event.
Update Event: Update existing event details.
Delete Event: Delete an event.
Register Event: Register for an event.

User Route:

Get User List: Retrieve a list of users.
Get User by ID: Retrieve user details by ID.
Update User: Update user details.

Util Route:

Upload Image: Post an image to the backend.
Get Image by Name: Retrieve an image by its name.

Models

User Schema:

Username
First Name
Last Name
Email
Password
Profile Picture
Address
Phone Number
Description
Followers

Event Schema:

Location
Picture
Created By
Attendees
Description
Venue Time
Name

Middleware:

Middleware to check the validity of JWT tokens.

Controllers
Auth Controller

SignUp: Register a new user.
Login: Authenticate and log in the user.
Refresh: Refresh JWT tokens.
Logout: Log out the user.

Events Controller

Get Event by ID: Retrieve event details.
Events List: Retrieve a list of events.
Delete Event by ID: Delete an event.
Update User by ID: Update user details.
Create Event: Create a new event.
Register Event: Register for an event.

User Controller

Users List: Retrieve a list of users.
Update User by ID: Update user details.
Get User by ID: Retrieve user details.

Util Controller

Upload Image: Handle image uploads.

Project Installation

Clone the repository: git clone <repository_url>
Navigate to the project directory: cd event-management
Install dependencies: npm install

Running the Project

To start the project,

Create a .env file from .env.example.

npm install

npm start

The server will be running at http://localhost:8000.