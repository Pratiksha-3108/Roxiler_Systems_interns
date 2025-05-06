# Store Rating Web App

A full stack web application where users can rate stores. Admins, Store Owners, and Normal Users have different features and access.

## Tech Stack

- Frontend: React.js
- Backend: Express.js
- Database: PostgreSQL
- Authentication: JWT
- ORM: Sequelize

## User Roles

### Normal User
- Register and log in
- View all stores
- Submit or update ratings (1 to 5)
- Search and filter stores

### Store Owner
- Log in
- View users who rated their store
- View average rating of their store

### Admin
- Add stores and users (Admin or Normal)
- View dashboard with:
  - Total users
  - Total stores
  - Total ratings
- Filter and view user/store details

## Form Validation Rules

- Name: 20–60 characters
- Address: Max 400 characters
- Password: 8–16 characters, must include one uppercase letter and one special character
- Email: Must be a valid format

## Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/fullstack-react-app.git
cd fullstack-react-app

# 2. Setup backend
cd backend
npm install
# Add .env file with PostgreSQL credentials
npm start

# 3. Setup frontend
cd ../frontend
npm install
npm start
