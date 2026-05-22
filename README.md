# WanderLust 🌍

WanderLust is a full-stack web application designed for travelers to discover, list, and book unique accommodations around the world. Built using the robust **MVC (Model-View-Controller)** architecture, the platform allows users to seamlessly browse destinations, host their own places, leave reviews, and manage travel listings.

---

## 🚀 Features

- **User Authentication & Authorization:** Secure signup and login functionality. Users can only edit/delete their own listings and reviews.
- **Listing Management:** Full CRUD (Create, Read, Update, Delete) operations for travel listings including titles, images, pricing, and locations.
- **Review System:** Interactive rating and review system for users to share their experiences on specific listings.
- **Cloud Image Storage:** Seamless image uploads powered by **Cloudinary**.
- **Robust Validation:** Strict server-side and client-side data validation using **Joi schemas** to ensure data integrity.
- **Flash Messages:** Instant, user-friendly feedback alerts for successful actions or error handlings.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript, EJS (Embedded JavaScript templates)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas (Mongoose ODM)
- **Cloud Storage:** Cloudinary (for listing images)

---

## 📂 Project Structure

```text
├── controllers/      # Handles application logic and links models with views
├── init/             # Sample data and database initialization scripts
├── models/           # Mongoose schemas (Listing, Review, User)
├── public/           # Static assets (CSS, JS, Images)
├── routes/           # Express router endpoints split by resource
├── utils/            # Helper functions and custom error handling classes
├── views/            # EJS templates for rendering the user interface
├── app.js            # Main entry point of the application
├── cloudConfig.js    # Cloudinary storage integration setup
├── middleware.js     # Custom authentication and authorization middlewares
└── schema.js         # Joi validation schemas
