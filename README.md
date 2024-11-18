# Personal Finance Tracking System  
 
The **Personal Finance Tracking System** is a web-based application that helps users manage their personal finances. It provides basic **Create, Read, and Delete (CRD)** operations for managing financial records, powered by **PostgreSQL** and **pgAdmin**. 

While the current version offers essential functionality, it lacks an **Update (U)** feature and user authentication. Additionally, it does not yet include advanced features like data visualization. 

Future updates will address these gaps to improve user experience and security.


---

## 👥 Team Members  

- [**Aryan Jain**](https://github.com/08-Aryan)
- [**Prabhmeet Singh**](https://github.com/prabhmeet-kira)  

---

## ✨ Features  

- **Dashboard Interface**: A user-friendly dashboard to manage and view financial data.  
- **CRD Operations**: Supports creating, viewing, and deleting financial records.  
- **Database Management**: Uses pgAdmin for database interactions and management.  

---

## 🛠️ Technologies Used  

- **Frontend**: React.js  
- **Backend**: Node.js with Express.js  
- **Database**: PostgreSQL with pgAdmin  

---
## Screenshots

![Screenshot (316)](https://github.com/user-attachments/assets/6b13c3b3-2760-4f27-8b4f-d3b7e8157465)

## ⚙️ Setup and Installation  

### Prerequisites  

- **Node.js** installed on your machine  
- **PostgreSQL** installed and configured
- **pgAdmin** set up for managing the PostgreSQL database  

### Steps  

1. **Clone the repository**:  
   ```bash  
   https://github.com/prabhmeet-kira/Finance-Tracker.git
2. **Navigate to the project directory**:  
   ```bash  
   cd personal-finance-tracking-system  
3. **Install backend dependencies**:  
   ```bash  
   cd backend
   npm install  
4. **Install frontend dependencies**:  
   ```bash  
   cd frontend
   npm install  
5. **Set up environment variables**:
   Create a .env file in the backend directory with the following content:
   ```bash  
   DATABASE_URL=your-postgresql-connection-url  
6. **Start the backend server**:  
   ```bash  
   cd backend
   node server.js
7. **Start the frontend development server**:  
   ```bash  
   cd frontend
   npm start
## 🌐 Accessing the Application
   Open your browser and navigate to:
   ```bash
   http://localhost:3000
   ```
## 🚀 Future Plans
   ```bash
   Add update (U) functionality to complete CRUD operations.
   Include user authentication for personalized dashboards.
   Add data visualization features for better financial insights.
   ```
