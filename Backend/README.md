# 🌟 **Crowdfunding Platform - Backend** 💰🎯  

Welcome to the **MERN-based Crowdfunding Platform**! 🚀 This is the **backend** of the application, built using **Node.js, Express.js, and MongoDB**, designed to handle **campaigns, user authentication, donations, and secure transactions**.  

> 🏆 **This project was developed during the Edunet Internship in collaboration with EY GDS.** 💼🎓  

---

## 📁 **Project Structure** 🏗️  

```
Backend/
│── 📂 controllers/        # Handles request logic for different entities  
│── 📂 middleware/         # Authentication and request validation  
│── 📂 models/            # Database schema definitions (MongoDB)  
│── 📂 paytm/             # Paytm payment gateway integration  
│── 📂 routes/            # Express.js routes for API endpoints  
│   ├── 📄 campaign.js    # Routes for campaign management  
│   ├── 📄 donation.js    # Routes for handling donations  
│   ├── 📄 index.js       # Centralized route management  
│   ├── 📄 payment.js     # Routes for handling payments  
│   ├── 📄 query.js       # Routes for user queries  
│   ├── 📄 user.js        # Routes for user authentication & profiles  
│── 🛠️ config.js          # Configuration settings (DB, API keys, etc.)  
│── 📜 env-sample.txt     # Sample environment variables file  
│── 🚫 .gitignore         # Files to ignore in version control  
│── 📄 index.html         # Static file (if needed for API documentation or admin panel)  
│── 📦 package.json       # Project dependencies and scripts  
│── 🚀 server.js          # Main server file for Express application  
│── 🌍 vercel.json        # Deployment configuration  
│── 📖 README.md          # Project documentation  
```

---

## 🚀 **Features** 🎯  

✔ **🔐 User Authentication** – Secure login, registration, and JWT-based authentication.  
✔ **📢 Campaign Management** – Create, update, and delete crowdfunding campaigns.  
✔ **💸 Donation System** – Users can donate to campaigns securely.  
✔ **💳 Payment Gateway Integration** – Seamless Paytm integration for secure transactions.  
✔ **❓ Query Handling** – Allows users to submit queries related to campaigns.  
✔ **🛡 Secure API Endpoints** – Middleware authentication and request validation.  
✔ **🗄 Database Integration** – Uses MongoDB for efficient data storage.  

---

## 🛠️ **Tech Stack** 🔧  

| 🚀 Technology | 🔍 Description |
|------------|-------------|
| **Node.js** | JavaScript runtime for backend operations |
| **Express.js** | Lightweight and fast web framework for Node.js |
| **MongoDB** | NoSQL database for storing campaign and user data |
| **Mongoose** | ODM for interacting with MongoDB |
| **JWT (JSON Web Token)** | Secure user authentication |
| **Paytm API** | Payment gateway integration |
| **dotenv** | Environment variable management |

---

## 🔧 **Installation & Setup** ⚙️  

### **1️⃣ Clone the Repository** 🖥️  
```sh
git clone <repo-url>
cd Backend
```

### **2️⃣ Install Dependencies** 📦  
```sh
npm install
```

### **3️⃣ Set Up Environment Variables** 📝  
Create a `.env` file and add the required environment variables:  

```sh
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYTM_MERCHANT_ID=your_paytm_merchant_id
PAYTM_MERCHANT_KEY=your_paytm_merchant_key
```

### **4️⃣ Start the Server** 🚀  
```sh
npm start
```
Your API will now be running at **http://localhost:5000** 🎉  

---

## 📌 **Folder Overview** 🗂️  

### 📂 `controllers/` 🎛  
Handles the logic for API requests.  

- 📄 `campaign.js` – Manages campaign creation, updates, and deletion.  
- 📄 `donation.js` – Handles donation transactions.  
- 📄 `payment.js` – Processes payments using Paytm.  
- 📄 `query.js` – Handles user queries related to crowdfunding.  
- 📄 `user.js` – Manages authentication, registration, and user profiles.  

### 📂 `middleware/` 🛡  
- 📄 `auth.js` – JWT authentication middleware.  

### 📂 `models/` 📊  
Defines Mongoose schemas for MongoDB.  

- 📄 `Campaign.js` – Defines campaign-related data structure.  
- 📄 `Donation.js` – Stores donation transaction details.  
- 📄 `Query.js` – Stores user-submitted queries.  
- 📄 `Token.js` – Manages authentication tokens.  
- 📄 `User.js` – Stores user data.  

### 📂 `routes/` 🌍  
Contains API route definitions.  

- 📄 `campaign.js` – API endpoints for campaigns.  
- 📄 `donation.js` – API endpoints for donations.  
- 📄 `payment.js` – API endpoints for payment processing.  
- 📄 `query.js` – API endpoints for queries.  
- 📄 `user.js` – API endpoints for user authentication.  

### 📂 `paytm/` 💳  
Handles **Paytm** payment gateway integration.  

---

## 🏗 **How to Contribute?** 🤝  

We welcome contributions! Follow these steps:  

1. **🍴 Fork** the repository.  
2. **🌿 Create** a new branch for your feature (`git checkout -b feature-name`).  
3. **🛠 Make your changes** and test locally.  
4. **💾 Commit** your changes (`git commit -m "Added new feature"`).  
5. **📤 Push** to your forked repo (`git push origin feature-name`).  
6. **🔁 Submit a Pull Request** for review.  

---

## 📜 **License** 📄  

This project is open-source and available under the **MIT License**.  

---

🎯 **Ready to start?** 🚀 Clone the repo, set it up, and let’s build an amazing crowdfunding platform together! 💡💰  
