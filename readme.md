# 🚀 Blockchain-Powered Hospital Management System 🏥🔗

## 📌 Project Overview
I am **starting this project** to develop a **Hospital Management System** that integrates **blockchain technology** to securely store patient medical records. Built using **Java (Spring Boot, JDBC, MySQL)** for the backend and **HTML, CSS, JavaScript** for the frontend, this system ensures **efficient, secure, and scalable** hospital operations.

## 🔥 Features
✅ **Patient Management** – Add, update, and delete patient records.  
✅ **Doctor Management** – Assign doctors to patients.  
✅ **Appointment Scheduling** – Manage patient appointments.  
✅ **Blockchain Storage** – Store patient medical records securely on **Ethereum**.  
✅ **Secure Authentication** – Implement JWT authentication for secure access.  
✅ **Cloud Deployment** – Deployed on **AWS/Render/Netlify** for accessibility.  

## 🛠️ Tech Stack
### **Frontend:**
- HTML, CSS, JavaScript (VanillaJS or React.js for UI enhancements)
- Bootstrap / Tailwind CSS for responsive design

### **Backend:**
- Java (Spring Boot + JDBC)
- MySQL for structured data storage
- Web3j for blockchain integration

### **Blockchain:**
- Ethereum Smart Contracts (Solidity)
- Ganache / Infura for blockchain transactions
- MetaMask for authentication

### **Deployment:**
- **Backend:** AWS EC2 / Render
- **Database:** AWS RDS / Railway.app
- **Frontend:** Netlify / Vercel

## 🏗️ Installation & Setup
### **1️⃣ Backend Setup**
```sh
# Clone the repository
git clone https://github.com/your-repo/hospital-management.git
cd hospital-management/backend

# Set up MySQL database
CREATE DATABASE hospital_db;

# Run the Spring Boot application
mvn spring-boot:run
```

### **2️⃣ Frontend Setup**
```sh
cd hospital-management/frontend

# Open index.html in browser (for VanillaJS)
# OR
# Install dependencies & run React app
npm install
npm start
```

### **3️⃣ Blockchain Setup**
```sh
# Deploy Smart Contract using Remix IDE or Hardhat
npx hardhat run scripts/deploy.js --network goerli
```

## 📌 API Endpoints
| Method | Endpoint                 | Description              |
|--------|-------------------------|--------------------------|
| POST   | `/patients`             | Add a new patient       |
| GET    | `/patients`             | Get all patients        |
| GET    | `/patients/{id}`        | Get patient by ID       |
| PUT    | `/patients/{id}`        | Update patient details  |
| DELETE | `/patients/{id}`        | Delete a patient        |
| POST   | `/patients/blockchain`  | Store record on blockchain |
| GET    | `/patients/blockchain/{id}` | Retrieve blockchain record |

## 🚀 Future Enhancements
🔹 **AI-Powered Disease Prediction** 📊  
🔹 **Doctor-Patient Chat System** 💬  
🔹 **Decentralized Data Storage (IPFS)** 🔗  

## 👨‍💻 Author
**Chinmay Duse** – [GitHub](https://github.com/in/psyphon1) | [LinkedIn](https://linkedin.com/in/chinmayduse)

💡 **Contributions & Feedback are Welcome!** 🚀

