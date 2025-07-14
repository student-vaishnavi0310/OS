🛒 A virtual online shopping simulator that mimics the customer journey — from product browsing to cart and checkout. Built with Python and front-end tools, it simulates user behavior and helps test e-commerce workflows, recommendation logic, and UI flows.

🛒 Online Shopping Simulator – ShopSim Overview: SmartCart is an interactive online shopping simulator that replicates the typical user experience of an e-commerce platform — from product browsing to adding items to the cart, applying filters, and completing a mock checkout. This project is designed to help understand the core workflow behind modern online shopping systems, including user interaction, backend logic, session handling, and UI/UX design.

🔍 Core Features: Homepage with Product Gallery: Displays a list of products fetched from a static or dynamic database. Users can view details like name, price, rating, and availability.

Search and Filters: Users can search products by name or category. Filters like price range, rating, or brand help simulate real e-commerce filtering logic.

Shopping Cart:

Add/remove items

View cart summary

Calculate subtotal, tax, and total

Quantity adjustments

Mock Checkout Page: Accepts user details, shipping method, and a simulated payment (no real transaction). Shows order summary and confirmation.

Session Handling: User actions like adding items to cart are preserved using sessions, simulating logged-in behavior.

Optional: Recommendation Section Show similar or “frequently bought together” items using simple logic or ML if extended.

🧠 How It Works: Frontend (User Interface):

Built using HTML, CSS, Bootstrap, and optionally JavaScript or React

Dynamic product display using templates

Responsive design for mobile and desktop

Backend (Business Logic):

Developed using Python (Flask/Django) or Node.js

Handles product routing, cart logic, price calculations, etc.

Database (Product Storage):

SQLite/MySQL stores product info, cart items, user data

You can also use static JSON/CSV for simple simulation

Extras:

Login system (optional)

Order summary PDF generation

Wishlist or save-for-later

🛠️ Tech Stack Layer Tools Used Frontend HTML, CSS, Bootstrap, JS Backend Python (Flask or Django) Database SQLite / MySQL / Firebase Optional React (UI), Pandas (data logic), Matplotlib (purchase analytics)

🎯 Goals and Learning Outcomes Simulate a real-world shopping platform

Practice full-stack development

Understand cart and session logic

Explore user experience and UI flow

Build a foundation for future e-commerce or inventory-based apps

💡 Future Scope Integrate a recommendation engine using ML

Add payment gateway APIs (for real e-commerce use)

Build user accounts and order history

Admin dashboard to manage products
