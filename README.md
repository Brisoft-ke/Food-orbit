# 🍽️ Food Orbit – Smart Food Ordering System



---

![Status](https://img.shields.io/badge/Status-Under%20Development-orange)
![Backend](https://img.shields.io/badge/Backend-Node.js-green)
![Database](https://img.shields.io/badge/Database-MySQL-blue)
![Frontend](https://img.shields.io/badge/Frontend-HTML%2FCSS%2FJS-yellow)

## Overview

**Food Orbit** is a smart food ordering web application that connects customers with restaurants or food vendors through a seamless digital experience. It features a RESTful API backend, role-based access control, and a dedicated admin dashboard for complete business management.

> ⚠️ This project is currently **under active development**. Core features are being built and iterated on. Contributions and feedback are welcome.

---

## Features (Planned & In Progress)

### Customer
- [ ] Browse menu and place orders
- [ ] Real-time order status tracking
- [ ] Secure account registration and login

### Admin
- [ ] Dashboard to manage users, orders, and menu items
- [ ] Order lifecycle management (pending → confirmed → delivered)
- [ ] Analytics overview (orders, revenue, popular items)

### Backend / API
- [x] REST API architecture
- [x] Role-based authentication (Customer, Admin)
- [ ] Order processing logic
- [ ] Menu CRUD operations

---

## Tech Stack

| Layer      | Technology              |
|------------|-------------------------|
| Backend    | Node.js                 |
| Database   | MySQL / PostgreSQL       |
| Frontend   | HTML, CSS, JavaScript   |
| Auth       | JWT (Role-based)        |
| Tools      | Git, GitHub, VS Code    |

---

## Project Structure

```
food-orbit/
├── backend/
│   ├── routes/         # API route handlers
│   ├── controllers/    # Business logic
│   ├── models/         # Database models
│   └── middleware/     # Auth & validation
├── frontend/
│   ├── index.html
│   ├── css/
│   └── js/
└── README.md
```

---

## Getting Started

> Setup instructions will be added as the project matures. Stay tuned.

```bash
# Clone the repo
git clone https://github.com/Brisoft-ke/food-orbit.git
cd food-orbit

# Install dependencies (backend)
npm install

# Start the development server
npm run dev
```

---

## Author

**Brian Wamalwa**
Full-Stack Software Engineer | Backend-Focused
[GitHub](https://github.com/Brisoft-ke) · wamalwabrian337@gmail.com

---

## License

This project is under active development and not yet licensed for public use.
