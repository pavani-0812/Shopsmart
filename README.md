# 🛒 ShopSmart: Your Digital Grocery Store Experience  

Welcome to **ShopSmart**, your modern grocery web app!  
It’s built to offer a smooth, secure, and scalable experience for both customers and admins.

## 📂 Project Structure

```bash
Shopsmart/
├── Backend/                  # Express + MongoDB backend
│   ├── db/                   # Database connection logic
│   ├── index.js              # Server entry point
│   ├── package.json
│   └── ...
├── Frontend/                # React frontend
│   ├── public/
│   ├── src/
│   │   ├── admin_components/ # Admin dashboard components
│   │   ├── components/       # Reusable UI components
│   │   ├── context/          # Context API for global state
│   │   ├── App.js
│   │   ├── index.js
│   │   ├── App.css, index.css
│   └── package.json
├── .gitignore


⚙️ Technologies Used
Layer	Tech Stack
Frontend-React, Context API
Backend-Node.js, Express.js
Database-MongoDB (with Mongoose)
Tools	Git, VS Code

✨ Features
🛍️ Customer:
Browse grocery items by categories
View product details
Add to cart and place orders
View past orders and status

🛠️ Admin:
Add/Edit/Delete products
Manage categories and orders
Access admin dashboard


✅ Prerequisites
Node.js & npm — Install
MongoDB — Install
Git — Install

Code Editor (VS Code recommended) — Download
📦 Git Setup Notes
If you see large file warnings (node_modules, .cache, etc.), make sure your .gitignore looks like this:
bash
Copy
Edit
node_modules/
.cache/
dist/
build/
*.log
