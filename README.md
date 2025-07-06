# CARTX 🛒

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen.svg)](https://redeemx-rho.vercel.app/)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![MERN Stack](https://img.shields.io/badge/stack-MERN-orange.svg)](https://www.mongodb.com/mern-stack)

## 🚀 [Live Demo](https://redeemx-rho.vercel.app/)

CARTX is a modern, full-featured e-commerce platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). Experience seamless shopping with a sleek, responsive interface powered by Tailwind CSS and secure payment processing through Stripe integration.


## ✨ Features

### User Experience
- **Intuitive Authentication** - Simple sign up, sign in, and sign out processes
- **Product Discovery** - Browse products with advanced filtering by category, price, and ratings
- **Detailed Product Views** - Comprehensive product information with high-quality images
- **Shopping Cart Management** - Add, remove, and update items with real-time cart total
- **Secure Checkout** - Streamlined payment process with Stripe integration
- **Order Tracking** - View order history and current order status
- **Responsive Design** - Optimized for all devices from mobile to desktop

### Admin Features
- **Dashboard Analytics** - Track sales, user engagement, and inventory
- **Product Management** - Add, edit, and remove products easily
- **Order Management** - Process orders and update shipping status
- **User Management** - View and manage user accounts

### Technical Highlights
- **RESTful API** - Well-structured backend with comprehensive endpoints
- **JWT Authentication** - Secure user authentication and authorization
- **Database Integration** - Efficient MongoDB data management
- **Performance Optimized** - Fast loading times and smooth user experience
- **Error Handling** - Robust error management and user feedback

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI components and state management
- **Redux Toolkit** - Global state management
- **Tailwind CSS** - Responsive styling
- **Axios** - API requests

### Backend
- **Node.js** - Server runtime
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - Authentication
- **Stripe** - Payment processing

## 📋 Installation

### Prerequisites
- Node.js (v14 or later)
- MongoDB
- npm or yarn

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/cartx.git
   cd cartx
   ```

2. **Backend Setup**
   ```bash
   cd server
   npm install
   
   # Create a .env file with the following variables:
   # PORT=5000
   # MONGODB_URI=your_mongodb_connection_string
   # JWT_SECRET=your_jwt_secret
   # STRIPE_SECRET_KEY=your_stripe_secret_key
   
   npm start
   ```

3. **Frontend Setup**
   ```bash
   cd ../client
   npm install
   
   # Create a .env file with:
   # VITE_API_URL=http://localhost:5000/api
   # VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
   
   npm run dev
   ```

4. **Access the application**
   - Frontend: http://localhost:5173
   - Backend API: http://localhost:5000/api

## 🚀 Deployment

The application is currently deployed at:
- Frontend: [https://redeemx-rho.vercel.app/](https://redeemx-rho.vercel.app/)
- Backend API: [https://cartx-api.vercel.app](https://cartx-api.vercel.app)

## 🤝 Contributing

We welcome contributions to CARTX! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Contact & Support

- **Website:** [Visit our live demo](https://redeemx-rho.vercel.app/)
- **Issue Tracker:** [GitHub Issues](https://github.com/yourusername/cartx/issues)
- **Email:** support@cartx.com

## 📃 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Stripe](https://stripe.com/)
- [Vercel](https://vercel.com/) for hosting

---

Happy shopping with CARTX! 🛍️
