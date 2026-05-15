# 🛒 Aliyan Marketplace - Full Stack eCommerce

![Aliyan Marketplace Banner](assets/banner.png)

<p align="center">
  <img src="https://img.shields.io/badge/License-ISC-blue.svg" alt="License: ISC">
  <img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white" alt="React 19">
  <img src="https://img.shields.io/badge/Node.js-18.x-339933?logo=node.js&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC?logo=tailwind-css&logoColor=white" alt="Tailwind CSS 4">
</p>

A comprehensive, high-performance eCommerce marketplace built with the **MERN stack**. Features a sleek UI, robust backend, and seamless user experience tailored for modern shopping needs.

---

## 🚀 Key Features

- **🔐 Secure Authentication**: JWT-based login/signup with password encryption using Bcrypt.
- **🛍️ Product Management**: Full CRUD operations for products with an intuitive admin interface.
- **🛒 Smart Shopping Cart**: Dynamic cart with guest persistence and real-time updates.
- **📱 Responsive Excellence**: Fully optimized for mobile, tablet, and desktop using Tailwind CSS 4.
- **⚡ Fast State Management**: Ultra-lightweight and efficient state handling with Zustand.
- **☁️ Cloud Image Hosting**: Integrated with Cloudinary for fast, reliable product image management.
- **🛠️ Admin Dashboard**: Centralized hub to manage inventory and view store metrics.
- **🎉 Modern UX**: Smooth transitions, loading states, and celebration effects with React Confetti.

---

## 🛠️ Tech Stack

### **Frontend**
- **Framework**: React 19 (Modern Hooks & Functional Components)
- **Styling**: Tailwind CSS 4 & DaisyUI (Premium Design System)
- **State**: Zustand (Simple, fast, and scalable)
- **Routing**: React Router 7 (Sophisticated client-side navigation)
- **Icons**: Lucide React & React Icons (Crisp, scalable vector icons)
- **Notifications**: React Hot Toast (Elegant user feedback)

### **Backend**
- **Server**: Node.js & Express (Robust API infrastructure)
- **Database**: MongoDB & Mongoose (Flexible NoSQL data modeling)
- **Auth**: JWT & Cookie-parser (Secure session management)
- **Security**: Bcrypt (Advanced password hashing)
- **Storage**: Cloudinary (Optimized media delivery)

---

## 📂 Project Structure

```bash
.
├── backend                 # Express server & API logic
│   ├── src
│   │   ├── controllers     # Request handlers (logic)
│   │   ├── models          # Database schemas (Mongoose)
│   │   ├── routes          # API endpoints definition
│   │   └── utils           # Helper functions & middleware
│   └── .env                # Environment configurations
├── frontend                # React application
│   ├── src
│   │   ├── components      # Reusable UI components
│   │   ├── pages           # Main application views
│   │   ├── store           # Zustand state management
│   │   └── assets          # Static assets and images
└── assets                  # Global project resources (banner, logo)
```

---

## ⚙️ Getting Started

### Prerequisites
- **Node.js**: v18.x or higher
- **MongoDB**: Account on MongoDB Atlas or local installation
- **Cloudinary**: Account for image hosting

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Aliyanshaikh12/ecommerce-fullstack-design.git
   cd ecommerce-fullstack-design
   ```

2. **Setup Backend**:
   - Navigate to the `backend` folder.
   - Create a `.env` file and add your credentials:
     ```env
     PORT=5000
     MONGODB_URI=your_mongodb_uri
     JWT_SECRET=your_secret_key
     CLOUDINARY_CLOUD_NAME=your_name
     CLOUDINARY_API_KEY=your_key
     CLOUDINARY_API_SECRET=your_secret
     NODE_ENV=development
     ```

3. **Install & Build**:
   ```bash
   # From the root directory
   npm run build
   ```

4. **Launch the Application**:
   ```bash
   # Starts both backend and frontend concurrently
   npm run start
   ```

---

## 👨‍💻 Author

**Aliyan Shaikh   DHC-1598**
- GitHub: [@Aliyanshaikh12](https://github.com/Aliyanshaikh12)

---

## 📄 License

This project is licensed under the **ISC License**.

---

<p align="center">
  build by Aliyan Shaikh
  DHC-1598
</p>
