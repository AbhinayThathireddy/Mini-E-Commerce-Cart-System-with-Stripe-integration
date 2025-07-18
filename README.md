
# Mini E-Commerce Cart System with Stripe Integration

**Mini E-Commerce Cart System** is a full-stack web application that enables users to browse products, manage their cart, and complete purchases securely using Stripe payment integration. Designed for learning and demonstration purposes, this project emulates core e-commerce functionalities including product management, cart operations, and transaction logging.

This project is ideal for developers looking to understand Spring Boot backend architecture, Stripe integration, and building production-ready shopping cart systems.

---

## Features

- **Product Management:** Add, update, and delete products (admin functionality).
- **Cart Operations:** Add/remove items, update quantities, and calculate totals.
- **Checkout System:** Seamless checkout and payment using Stripe.
- **Transaction Logs:** Keeps track of all completed transactions.
- **Professional Frontend UI:** Clean layout inspired by modern e-commerce sites like Amazon.

---

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Java, Spring Boot
- **Database:** MySQL
- **Payment Gateway:** Stripe
- **Build Tool:** Maven

---

## Installation

### Prerequisites

- Java 17+
- Maven
- MySQL (or any relational DB)
- Stripe Account & API Keys

### Setup Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/Mini-E-Commerce-Cart-System.git
cd Mini-E-Commerce-Cart-System
```

2. **Configure Database**

Update `application.properties` with your MySQL credentials:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=yourpassword
```

3. **Add Stripe Keys**

In `application.properties`:
```properties
stripe.api.key=your_stripe_secret_key
stripe.public.key=your_stripe_publishable_key
```

4. **Build and Run the Project**

```bash
mvn clean install
mvn spring-boot:run
```


## Folder Structure

```
Mini_E_commerce_Cart_System_with_Stripe_Integration/
│
├── src/
│   └── main/
│       ├── java/com/quickshop/        # Backend Java source files
│       └── resources/                 # application.properties and templates
│
├── pom.xml                            # Maven configuration
└── README.md                          # This file
```

---

## Screenshots

### 🛒 Product Listing Page
![Product Page](https://github.com/user-attachments/assets/75bcf3c9-01b5-4771-8a03-33cc4c209751)

### 🧺 Cart Page
![Cart Page](https://github.com/user-attachments/assets/df810c8b-0287-4804-8861-b93e24cdf4b8)

### 💳 Stripe Checkout
![Checkout](https://github.com/user-attachments/assets/0a5e8d63-5160-41da-80a4-71bf4a910a2d)

### ✅ Payment Success
![Success](https://github.com/user-attachments/assets/83e08c92-4e19-48bb-bbdc-a934c90b1a99)

### 📊 Stripe Dashboard - Payment Details
![Stripe Dashboard](https://github.com/user-attachments/assets/5ec3b53d-5d9e-4751-8402-0291133eb32b)


---


## Acknowledgments

- **Stripe API** for secure payments.
- **Spring Boot** for backend services.
- **MySQL** for data persistence.
- **HTML/CSS** for crafting the user interface.
