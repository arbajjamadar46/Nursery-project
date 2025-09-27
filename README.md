# Nursery Management System 🌱

A web-based system to manage plant nursery operations — handling inventory, orders, plant details, and more. Built with a full-stack approach to provide an intuitive interface for administrators, staff, and customers.

---

## Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Installation & Setup](#installation--setup)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Future Enhancements](#future-enhancements)  
- [Contributing](#contributing)  
- [Contact](#contact)  

---

## Features

- CRUD operations for plants, categories, suppliers, and orders  
- Inventory tracking (stock levels, restocking alerts)  
- Order management (create, view, update, delete)  
- Role-based access (admin, staff)  
- Search, filter, and sort capabilities  
- Responsive UI for desktop and mobile  
- Export/report functionality (e.g. inventory reports)  
- Basic authentication & authorization  

---

## Tech Stack

| Layer | Technologies |
|-------|--------------|
| Frontend | JavaScript / HTML / CSS |
| Backend | PHP |
| Database | MySQL |
| Styling / UI | Bootstrap |

---

## Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/arbajjamadar46/Nursery-project.git
   cd Nursery-project

   Install dependencies
Navigate into the frontend/backend folder (if you have a monorepo or split)

npm install
# or
yarn install

Configure environment variables
Create a .env file based on .env.example (if present) and set variables like:

DB_HOST=…
DB_USER=…
DB_PASSWORD=…
DB_NAME=…
JWT_SECRET=…
PORT=…


Run database migrations / seeders

npm run migrate
npm run seed


Start the application

npm run dev


Open in browser
Visit http://localhost:3000 (or whichever port you have configured)

## Usage

Admin Dashboard: manage plants, inventory, orders, categories, users

Search & Filter: find plants by category, name, availability

Order Management: add, edit, cancel orders

Inventory Alerts: see warnings when stock is low

Reports & Exports: generate CSV / PDF reports of inventory & orders

Project Structure

Here’s a rough outline of how your project is organized:

Nursery-project/
├── backend/           # server-side code (API, database models, controllers)
├── frontend/          # client-side / UI code
├── assets/            # static assets (images, CSS, fonts)
├── config/            # configuration files
├── migrations/        # database migration scripts
├── seeders/           # database seeders
├── routes/            # route definitions
└── README.md


## Future Enhancements

Here are some ideas/plans you might implement later:

Add user registration & profiles

More user roles & permissions (e.g. viewer, manager)

Real-time stock updates via websockets

Notification / alert system (email or SMS)

Analytics dashboard (sales trends, inventory turnover)

Mobile app or PWA version

Image upload & gallery for plants

Internationalization / multi-language support

## Contributing

Contributions are welcome! If you want to add a feature, fix bugs or improve documentation:

Fork the repository

Create a new branch: git checkout -b feature/YourFeature

Make your changes and test

Commit your changes: git commit -m "Add: Description of change"

Push to your branch: git push origin feature/YourFeature

Open a Pull Request, describing what you changed and why

## Contact

Developed by Arbaj Jamadar
GitHub: arbajjamadar46

Email: (arbajjamadar46@gmail.com)
