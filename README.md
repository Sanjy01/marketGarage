# marketGarage

🚀 Material Garage
Material Garage is a simple, OLX-style web marketplace where users can sign in, browse products by location, post listings, and leave reviews. Built using HTML, CSS, and Firebase for authentication, this project is perfect for anyone looking to understand the basics of front-end web design and user login systems.

📁 Project Structure
bash
Copy
Edit
.
├── about.html        # About the platform
├── create.html       # Page to create a product listing
├── index.html        # Home page
├── loaction.html     # Product listings by location
├── login.html        # Login and signup using Firebase
├── products.html     # Product gallery with images and prices
├── review.html       # Star-based review system
└── assets/           # Images used across pages (add this directory)
🔑 Features
🔐 User Authentication with Firebase (Sign Up / Sign In)

🛒 Product Listings across major Indian cities

🎨 Clean and responsive UI with custom CSS

⭐ Review System with 5-star ratings

📍 Location-based product cards

🛠️ Setup Instructions
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/material-garage.git
cd material-garage
Add your Firebase configuration in login.html: Replace the following placeholders with your actual Firebase project values:

javascript
Copy
Edit
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};
Open index.html in your browser to get started.
