# AutoArchive Car Rental Management System

A full-featured **Car Rental Management System** built using **ASP.NET Web API**, **React.js**, and **SQL Server**. This system is designed to automate and streamline car rental operations, allowing multiple types of users to interact with the system based on their roles.

---

## 🚗 **System Overview**

AutoArchive is a modern car rental automation platform supporting **four user roles**, each with unique permissions and capabilities:

### **1. Client (Customer)**

The person renting a car.

* Browse available cars
* View car details
* Make booking requests
* Manage profile
* View booking history

### **2. Car Owner (Provider)**

The provider who lists their car for rent.

* Register and list cars
* Update car details
* Monitor rental requests
* View earnings and reports

### **3. Manager**

Oversees daily operations.

* Manage bookings
* Approve or reject rental requests
* Monitor customer complaints
* Generate basic operational reports

### **4. Admin**

Has full privilege and full system control.

* Manage all users (create, update, deactivate)
* Manage roles & permissions
* System-wide analytics dashboard
* Security logs & backups

---

## 📁 **System Features**

### 🔐 **Authentication & Authorization**

* JWT token-based authentication
* Role-based access control (RBAC)
* Email-based authentication & verification (OTP or verification link)
* Password reset via email service
* Email notifications for account activities

### 🚗 **Car Management (Owner & Admin)**

* Add, update, delete, and view cars
* Upload vehicle documents and images
* Track availability status

### 📅 **Booking & Rental Workflow (Client, Owner, Manager)**

* Real-time booking system
* Automated booking approval workflow
* Payment status tracking (future integration: Stripe, PayPal)

### 🧑‍💻 **User Management (Admin)**

* CRUD for all users
* Assign and update roles
* Deactivate or activate accounts

### 📊 **Reporting & Analytics (Manager & Admin)**

* Earnings reports
* Rental activity insights
* Car availability summary

---

## 🏗️ **Project Architecture**

### **Backend – ASP.NET Web API**

* Clean Architecture (Controllers → Services → Repositories → SQL Server)
* Entity Framework Core
* AutoMapper for DTO mapping
* SQL Server (hosted locally or Azure SQL)

### **Frontend – React.js**

* React Router for navigation
* Axios for API communication
* Context API / Redux for state management
* TailwindCSS or Material UI for UI design

### **Database – SQL Server**

Main tables include:

* Users
* Roles
* Cars
* Bookings
* Payments
* CarOwnership
* Notifications

---

## 📦 **Folder Structure**

### **Backend (Web API)**

```
/AutoArchive.API
/AutoArchive.Core
/AutoArchive.Infrastructure
/AutoArchive.Domain
```

### **Frontend (React)**

```
/src
  /components
  /pages
  /services
  /context
  /hooks
```

---

## 🚀 **How to Run the Project**

### **1. Clone the Repository**

```
git clone https://github.com/yourusername/AutoArchive.git
```

### **2. Backend Setup**

```
cd AutoArchive.API
update appsettings.json with SQL Server connection
run: dotnet ef database update
dotnet run
```

### **3. Frontend Setup**

```
cd autoarchive-frontend
npm install
npm start
```

---

## 🤝 **Contributing**

Pull requests are welcome. For major changes, open an issue first.

---

## 📜 **License**

This project is licensed under the MIT License.

---

## 👤 **Author**

**Mazimpaka Danny**
AutoArchive System Developer
GitHub: *your-link-here*
