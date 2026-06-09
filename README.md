#  Electricity Billing System

##  About

The **Electricity Billing System** is a desktop-based application developed using **Java Swing, JDBC, and MySQL** that automates electricity bill management and customer record maintenance. The system provides separate functionalities for **Administrators** and **Customers**, enabling efficient management of electricity billing operations.

The application allows administrators to add customers, manage meter information, calculate electricity bills, and monitor payment records. Customers can view their information, generate bills, check bill details, and pay electricity bills through the system.

---

# Project Objectives

* Automate electricity billing operations.
* Manage customer information digitally.
* Store and maintain meter details.
* Calculate electricity bills based on electricity consumption.
* Generate monthly electricity bills.
* Track bill payment status.
* Reduce manual calculation errors.
* Improve billing efficiency and record management.

---

#  Features

### Customer Management

* Add New Customer
* View Customer Details
* Update Customer Information
* Customer Registration
* Customer Login

### Meter Management

* Meter Registration
* Meter Location Management
* Meter Type Selection
* Phase Code Management
* Bill Type Configuration

### Billing Management

* Calculate Electricity Bills
* Monthly Bill Generation
* Electricity Usage Tracking
* Automatic Tax Calculation
* Service Charge Calculation
* Fixed Tax Calculation
* Meter Rent Calculation

### Payment Management

* View Bill Details
* Pay Electricity Bills
* Track Payment Status
* Update Paid/Unpaid Records

### Reports & Records

* View Customer Records
* View Deposit Details
* Generate Electricity Bills
* Print Records
* Bill History Management

### Security Features

* Login Authentication
* Role-Based Access (Admin / Customer)
* Account Creation and Management

---

#  Administrator Functionalities

The Administrator has access to:

* Login
* Add New Customers
* Register Meter Information
* View Customer Details
* View Deposit Details
* Calculate Electricity Bills
* Manage Billing Records
* Generate Reports
* Logout

---

#  Customer Functionalities

The Customer has access to:

* Signup
* Login
* View Personal Information
* Update Personal Information
* View Bill Details
* Generate Monthly Bills
* Pay Electricity Bills
* Logout

---

#  System Modules

### 1. Login Module

Provides secure authentication for:

* Admin
* Customer

### 2. Customer Management Module

Handles:

* Customer Registration
* Customer Information Storage
* Customer Information Updates

### 3. Meter Information Module

Handles:

* Meter Location
* Meter Type
* Phase Code
* Bill Type

### 4. Bill Calculation Module

Handles:

* Unit Consumption
* Cost Per Unit Calculation
* Tax Calculations
* Service Charges
* Total Bill Calculation

### 5. Bill Generation Module

Generates detailed monthly electricity bills.

### 6. Payment Module

Handles:

* Bill Payments
* Payment Status Updates
* Paid / Unpaid Tracking

### 7. Reports Module

Displays:

* Customer Records
* Deposit Records
* Bill Records

### 8. Database Module

Responsible for:

* Database Connectivity
* Query Execution
* Data Storage and Retrieval

---

# 💻 Technologies Used

## Frontend

* Java Swing
* Java AWT

## Backend

* Java
* JDBC

## Database

* MySQL

## Libraries

* rs2xml.jar (DbUtils)

---

# 🛠️ Software and Tools Required

### Development Tools

* NetBeans IDE 8.2 or Above
* Git

### Programming Language

* Java JDK 8 or Above

### Database

* MySQL Server 8.0+
* MySQL Workbench

### JDBC Driver

* MySQL Connector/J

### External Libraries

* rs2xml.jar

### Operating System

* Windows 10 / 11
* Linux
* macOS

---

# 📂 Project Structure

```text
Electricity-Billing-System
│
├── BillDetails.java
├── CalculateBill.java
├── Conn.java
├── CustomerDetails.java
├── DepositDetails.java
├── GenerateBill.java
├── Login.java
├── MeterInfo.java
├── NewCustomer.java
├── PayBill.java
├── Project.java
├── Signup.java
├── Splash.java
├── UpdateInformation.java
├── ViewInformation.java
│
├── icon/
│   ├── bill.png
│   ├── hicon1.jpg
│   ├── hicon2.jpg
│   ├── i2.jpg
│   ├── i3.jpg
│   ├── second.jpg
│   ├── signupImage.png
│   ├── update.jpg
│   └── viewcustomer.jpg
│
└── README.md
```

---

# 🗄️ Database Tables Used

The project uses the following database tables:

```text
customer
login
meter_info
bill
tax
```

---

# 🚀 How to Run the Project in NetBeans

### Step 1

Install the following software:

* Java JDK 8+
* NetBeans IDE
* MySQL Server
* MySQL Workbench

### Step 2

Clone the repository:

```bash
git clone https://github.com/your-username/Electricity-Billing-System.git
```

### Step 3

Open NetBeans IDE.

### Step 4

Click:

```text
File → Open Project
```

### Step 5

Select the project folder.

### Step 6

Add the required libraries:

```text
mysql-connector-java.jar
rs2xml.jar
```

### Step 7

Create the MySQL database.

### Step 8

Update database credentials inside:

```java
Conn.java
```

Example:

```java
DriverManager.getConnection(
"jdbc:mysql:///ElectricityBS",
"root",
"your_password"
);
```

### Step 9

Clean and Build the project.

```text
Right Click Project
→ Clean and Build
```

### Step 10

Run:

```text
Splash.java
```

or

```text
Login.java
```

---

# 🔄 System Workflow

### Step 1

Launch Application

```text
Splash Screen
```

⬇

### Step 2

Login

```text
Admin
or
Customer
```

⬇

### Step 3

Admin Operations

```text
Add Customer
Add Meter Information
Calculate Bills
View Records
```

⬇

### Step 4

Customer Operations

```text
View Information
Update Information
Generate Bill
Pay Bill
```

⬇

### Step 5

Bill Status Updated

```text
Paid
or
Not Paid
```

---

# 🌟 Key Highlights

✅ User-Friendly GUI using Java Swing

✅ Secure Login System

✅ Customer and Meter Management

✅ Automated Bill Calculation

✅ Monthly Bill Generation

✅ Payment Status Tracking

✅ MySQL Database Integration

✅ Print Functionality for Records

✅ Separate Admin and Customer Access

---

# The Screenshots of some of the webPages of this project are Here:

1. Login Page
   
   <img width="787" height="360" alt="login" src="https://github.com/user-attachments/assets/25728ee4-7955-4128-8d46-a7496237b6f1" />

2. Signup Page

   <img width="860" height="482" alt="singup" src="https://github.com/user-attachments/assets/4c3db598-2afb-4d7e-bbf8-222889f8d6f7" />

3. AddCustomer

   <img width="837" height="615" alt="addCust" src="https://github.com/user-attachments/assets/9e09f63f-58ee-4373-9435-daddf4eb8b92" />

4. Customer Details

   <img width="1487" height="772" alt="custDetails" src="https://github.com/user-attachments/assets/e943798f-8827-4208-83ec-6bda815badd4" />

5. Calculate Bill

   <img width="863" height="618" alt="calculatebill" src="https://github.com/user-attachments/assets/80dc4680-dc7f-4178-9b99-d3d4e5a7d5e4" />

6. Meter Info

    <img width="827" height="610" alt="meterInfo" src="https://github.com/user-attachments/assets/31bd1b96-98c7-4678-b449-bf6304441433" />

7. Pay Bill

   <img width="1110" height="722" alt="payBill" src="https://github.com/user-attachments/assets/e288fba4-8587-4315-8189-e3daf2c1864b" />

8. View Info

   <img width="1018" height="812" alt="viewInfo" src="https://github.com/user-attachments/assets/7d092be8-f312-4417-904d-08c5e12178f3" />


# Future Enhancements

* Online Payment Gateway Integration
* PDF Bill Generation
* Email Notifications
* SMS Alerts
* Electricity Consumption Analytics
* Cloud Database Integration
* Web-Based Version
* Mobile Application
* Dashboard and Reporting System

---

# Author

**Vaishnavi Suryavanshi**

Bachelor of Technology (Computer Science Engineering)

# Skills

* Java
* JDBC
* MySQL
* HTML
* CSS
* JavaScript
* Web Development
* Data Structures & Algorithms

---

⭐ If you found this project useful, consider giving it a star on GitHub.

