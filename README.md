MERN Stack E-Commerce Website
This is an e-commerce website built using the MERN stack (MongoDB, Express, React, Node). It includes a user interface, admin panel, and backend server. You can manage products, handle user authentication, and process payments using Stripe.


Here’s a concise and descriptive version for your README file:

---

## How to Run the Project

To set up and run the project, follow these steps:



### 1. Create the `.env` File
- Navigate to the `backend` folder and create a file named `.env`.
- Add the following variables to the `.env` file:
  ```plaintext

  
 # MongoDB connection string ( your mongodb url )
MONGODB_URI="YOUR_MONGODB_URL"

# Secret key for JWT authentication (any secret key)
JWT_SECRET="ANY_RANDOM_KEY"

# Stripe secret key for payment processing (your stripe url)
STRIPE_SECRET_KEY="YOUR_STRIPE_SECRET_KEY"

  ```

### 2. Start the Applications
You will need **three separate terminals** to run the server, admin panel, and frontend.

#### Terminal 1: Backend Server

  cd backend
  npm run server


#### Terminal 2: Admin Panel
- Navigate to the `admin` directory:

  cd admin
  npm run dev

#### Terminal 3: Frontend Application
- Navigate to the `frontend` directory:

  cd frontend
  npm run dev

