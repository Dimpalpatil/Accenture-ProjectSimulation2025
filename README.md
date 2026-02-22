# Accenture-ProjectSimulation2025
Full-stack MEAN project implementing a pizza ordering platform with Angular, Node.js, Express, and MongoDB. Built during Accenture project simulation to demonstrate end-to-end web application development.

This repository contains the Pizzeria full-stack web application built using the MEAN stack (MongoDB, Express.js, Angular, Node.js) as part of an Accenture project simulation.
The project demonstrates REST API integration, CRUD operations, user authentication, and component-based frontend development in Angular.


## Features
- User registration and login
- Pizza menu listing
- Add to cart and place order
- Backend REST APIs
- MongoDB database integration
- Angular-based responsive UI


# 1. Prerequisites
node -v
npm -v
npm install -g @angular/cli
ng version

# 2. Clone the project
git clone https://github.com/your-username/pizzeria.git
cd pizzeria

# 3. Start MongoDB
mongod
# (In another terminal, optional)
mongosh

# 4. Backend setup & run
cd backend
npm install
npm start
# OR (if using nodemon)
npm run dev

# 5. Frontend setup & run
cd ../frontend
npm install
ng serve

# 6. Open app in browser
# http://localhost:4200
