# 🌟 **MERN Crowdfunding Platform with Secure Transactions** 💰🚀  

Welcome to the **MERN Crowdfunding Platform**, a **secure and user-friendly web application** designed to help individuals and organizations raise funds for various causes. This platform provides a **trustworthy space** where donors and campaign creators can interact with confidence. Built with **cutting-edge web technologies and blockchain integration**, it ensures **transparency, security, and efficiency** in fundraising.  

> 🏆 **This project was developed by Akash Aryan under the guidance of Neethu Ma’am during the Edunet Internship in collaboration with EY GDS.** 💼🎓  

---

## 🌍 **Project Overview**  

This **MERN-based crowdfunding platform** empowers users to **create fundraising campaigns**, accept **secure donations**, and manage funds transparently. It is designed for:  

- **Startups & Entrepreneurs** – Raise funds for business ideas.  
- **Nonprofits & NGOs** – Securely collect donations for social causes.  
- **Students & Educators** – Fund academic projects or research.  
- **General Users** – Easily donate and support causes they believe in.  

💡 **Key Features:**  
✔ **User Authentication** – Secure login & signup via JWT 🔐  
✔ **Campaign Creation** – Start a fundraising initiative in seconds 🚀  
✔ **Secure Donations** – Integrated **Paytm Payment Gateway** for transactions 💳  
✔ **Blockchain Transparency** – Future implementation of smart contracts for trust & security 🔗  
✔ **Real-time Updates** – Live progress tracking of campaign donations 📊  
✔ **Admin & User Roles** – Role-based access control for enhanced security 🔏  
✔ **Fraud Prevention** – Ensuring authenticity through user verification ✅  

---

## 📁 **Project Structure** 🏗  

The project is structured into **Backend (Node.js, Express, MongoDB)** and **Frontend (React.js, REST APIs, Axios)**, ensuring a **robust** and **scalable** architecture.  

```
Crowdfunding-Platform/
│── 📂 Backend/        # Server-side logic & APIs  
│── 📂 Frontend/       # User interface built with React  
│── 📜 README.md       # Documentation (this file)  
```

---

## 📂 **Backend Architecture (Node.js + Express + MongoDB)** 🛠  

The **backend** is responsible for handling **authentication, campaign management, payments, and user interactions**.  

### **Folder Structure:**  
```
Backend/
│── controllers/       # API logic (campaign, donations, payments, etc.)
│── middleware/        # Authentication & security middlewares
│── models/           # Database models (User, Campaign, Donations, etc.)
│── routes/           # API routes
│── paytm/            # Paytm Payment Gateway integration
│── config.js         # Configuration settings
│── server.js         # Main backend server file
│── .gitignore        # Files to be ignored in version control
│── package.json      # Backend dependencies
```

### **Backend Technologies Used:**  
- **Node.js & Express.js** – Scalable backend framework.  
- **MongoDB + Mongoose** – NoSQL database for efficient data storage.  
- **JWT Authentication** – Secure token-based authentication system.  
- **Paytm API** – Seamless and secure payment transactions.  
- **Middleware (Auth & Validation)** – Ensures security and request validation.  

---

## 📂 **Frontend Architecture (React.js, Axios, React Router)** 🎨  

The **frontend** provides a modern, intuitive, and responsive user experience, making crowdfunding **accessible** and **engaging**.  

### **Folder Structure:**  
```
Frontend/
│── public/          # Static assets
│── src/            # Source code
│   │── Components/  # Reusable UI components
│   │── Routes/      # Page routing configuration
│   │── services/    # API service functions
│   │── utils/       # Helper functions
│── App.jsx         # Main React component
│── index.js        # Application entry point
│── config.js       # Frontend configuration settings
│── package.json    # Frontend dependencies
```

### **Frontend Technologies Used:**  
- **React.js** – Component-based frontend framework.  
- **React Router** – Smooth navigation between pages.  
- **Axios** – API communication between frontend & backend.  
- **CSS Modules / Tailwind CSS** – Clean and maintainable styling.  
- **State Management** – Efficient handling of user interactions.  

---

## 🔧 **Installation & Setup**  

### **1️⃣ Clone the Repository** 🖥️  
```sh
git clone <repo-url>
cd Crowdfunding-Platform
```

### **2️⃣ Install Dependencies** 📦  
For Backend:  
```sh
cd Backend
npm install
```
For Frontend:  
```sh
cd Frontend
npm install
```

### **3️⃣ Start the Development Servers** 🚀  
Backend:  
```sh
npm start
```
Frontend:  
```sh
npm start
```

Your application will now be running at **http://localhost:3000** 🎉  

---

## 🏗 **How It Works?** 💡  

🔹 **Sign Up / Login** – Users register and log in securely.  
🔹 **Create a Campaign** – Start a new fundraising campaign with title, description, and goal amount.  
🔹 **Share the Campaign** – Spread the word via social media or direct links.  
🔹 **Receive Donations** – Users can donate via a secure **Paytm payment gateway**.  
🔹 **Track Progress** – Campaign creators can monitor the amount raised in real-time.  
🔹 **Withdraw Funds** – Campaign owners can request fund withdrawals upon reaching their goal.  

---

## 🛠️ **Tech Stack**  

| 🚀 Technology | 🔍 Description |
|------------|-------------|
| **MongoDB** | NoSQL database for storing campaign & user data |
| **Express.js** | Backend framework for handling API requests |
| **React.js** | Frontend library for building UI |
| **Node.js** | Server-side JavaScript runtime |
| **Paytm API** | Payment gateway integration |
| **JWT (JSON Web Token)** | Secure user authentication |
| **Mongoose** | MongoDB ORM for easy database operations |
| **Axios** | Handles API requests in the frontend |
| **React Router** | Enables seamless page navigation |

---

## 🚀 **Future Enhancements & Scope**  

- 🖼 **Support for multiple image formats & higher resolution images** for campaigns.  
- 🎥 **Extension to video steganography** – dynamic data hiding for more secure transactions.  
- 🔒 **Incorporation of advanced encryption algorithms** for enhanced security.  
- 📱 **Development of a mobile/web-based app** for broader accessibility.  
- 🎭 **Integration of AI-based fraud detection** to ensure campaign authenticity.  
- 🔗 **Blockchain & Smart Contracts for transparency** in crowdfunding transactions.  

---

## 👥 **Contributors**  

| Name          | Role                                      |
|--------------|------------------------------------------|
| **Akash Aryan**  | Developer & Project Lead |
| **Neethu Ma’am**  | Mentor & Guide |

A special thanks to **Edunet Foundation & EY GDS** for providing this amazing learning opportunity! 🎓🚀  

---

## 📜 **License** 📄  

This project is open-source and available under the **MIT License**.  

---

🎯 **Want to contribute?** 💡 Fork the repo, make your changes, and submit a PR! Let’s build the future of crowdfunding together! 🚀💰  
