# E-commerce Website

A full-stack e-commerce web application built with React (Vite, Tailwind CSS) for the frontend and Node.js/Express/MongoDB for the backend. Features include user authentication, product management, shopping cart, order processing, and admin dashboard.

## Features
- User registration & login
- Product browsing & filtering
- Shopping cart & checkout
- Order history
- Product reviews
- Admin panel for product & order management
- Responsive UI with Tailwind CSS

## Tech Stack
- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express, MongoDB
- **Authentication:** JWT
- **Payments:** PayPal integration

## Folder Structure
```
E-commerce-website/
  client/      # Frontend source code
  server/      # Backend source code
```

## Getting Started

### Prerequisites
- Node.js & npm
- MongoDB

### Setup
1. **Clone the repository:**
   ```sh
   git clone <repo-url>
   cd E-commerce-website
   ```
2. **Install dependencies:**
   - Frontend:
     ```sh
     cd client
     npm install
     ```
   - Backend:
     ```sh
     cd ../server
     npm install
     ```
3. **Configure environment variables:**
   - Create a `.env` file in `server/`:
     ```env
     DB_URL=your_mongodb_connection_string
     PAYPAL_MODE=sandbox
     PAYPAL_CLIENT_ID=your_paypal_client_id
     PAYPAL_CLIENT_SECRET=your_paypal_client_secret
     ```
4. **Start the backend server:**
   ```sh
   node server.js
   ```
5. **Start the frontend dev server:**
   ```sh
   cd ../client
   npm run dev
   ```

## Deployment
- Frontend can be deployed on Netlify/Vercel.
- Backend can be deployed on platforms like Heroku, Render, or your own server.

## License
MIT
