# Laravel Coffee Shop Lab

This project is a **step-by-step Laravel Lab** designed to help students learn how to build a complete Laravel application from scratch. A part of [Advanced Web Development - CSB35050](https://docs.google.com/document/d/1jWUGN0ePdt4_Mx--ZT9UvC19EsemxtyYdjH2c7mggjc) course.
The lab simulates a simple **Coffee Shop** system where learners gradually implement database design, APIs, user interface, security, and testing.

![image](https://github.com/nghuuquyen/coffee-app/assets/14355905/7b6575b7-3097-4ab3-96b8-263f3dbf0624)

> If you're new to PHP or Laravel, it's recommended to review the [PHP for Beginners (2023 Edition)](https://www.youtube.com/watch?v=U2lQWR6uIuo&list=PL3VM-unCzF8ipG50KDjnzhugceoSG3RTC) before starting the lab.

---

## 📌 Overview

- **Framework:** Laravel version 12
- **Project Type:** Coffee Shop Application  
- **Goal:** Learn Laravel fundamentals through a guided hands-on project  

The lab is divided into **following sections**, each focusing on a core aspect of web application development.  

---

## 📖 Sections

### Section 1 – Working with Database
Learn how to:
- Configure database connection
- Define migrations and seeders
- Work with Eloquent models
- Establish relationships between entities

👉 [Detailed Guide for Section 1](https://docs.google.com/presentation/d/1IQnqzBe-kMASDrICltffJVBc286n-oGAR2o8RrQXOfY/edit?slide=id.g2928d8f033d_0_90#slide=id.g2928d8f033d_0_90)

---

### Section 2 – Build a REST API
Learn how to:
- Define API routes
- Implement controllers and services
- Return JSON responses
- Handle API resource transformations

👉 [Detailed Guide for Section 2](https://docs.google.com/presentation/d/1IQnqzBe-kMASDrICltffJVBc286n-oGAR2o8RrQXOfY/edit?slide=id.g2928d8f033d_0_103#slide=id.g2928d8f033d_0_103)

---

### Section 3 – Error Handling & Logging
Learn how to:
- Manage exceptions
- Customize error pages
- Configure logging channels
- Debug common issues

👉 [Detailed Guide for Section 3](https://docs.google.com/presentation/d/1IQnqzBe-kMASDrICltffJVBc286n-oGAR2o8RrQXOfY/edit?slide=id.g2953383ad5d_0_0#slide=id.g2953383ad5d_0_0)

---

### Section 4 – Build the User Interface
**Part 1: Build the Homepage**  
**Part 2: Build the Add to Cart**  
**Part 3: Build the Checkout Process**  
**Part 4: Multiple Languages Support**

Learn how to:
- Build Blade templates
- Implement shopping cart logic
- Create a checkout workflow
- Add i18n (multi-language support)

👉 [Detailed Guide for Section 4](https://docs.google.com/presentation/d/1IQnqzBe-kMASDrICltffJVBc286n-oGAR2o8RrQXOfY/edit?slide=id.g2928d8f033d_0_153#slide=id.g2928d8f033d_0_153)

---

### Section 5 – Testing
Learn how to:
- Write unit tests for models and services
- Create feature tests for APIs and UI
- Use Laravel’s testing utilities
- Ensure application reliability

👉 [Detailed Guide for Section 5](https://docs.google.com/presentation/d/1IQnqzBe-kMASDrICltffJVBc286n-oGAR2o8RrQXOfY/edit?slide=id.g25ceb007f0a_0_0#slide=id.g25ceb007f0a_0_0)

---

### Section 6 – Security
**Part 1: Implement Authentication Features**  
**Part 2: User Profile Feature**  
**Part 3: Two Factor Authentication (2FA)**  
**Part 4: Secure API Routes with API Token**  
**Part 5: Update UI Navigation Links and Dashboard**

Learn how to:
- Implement authentication and authorization
- Build secure user profile management
- Enable 2FA for enhanced security
- Protect API endpoints with tokens
- Improve UI with authenticated navigation

👉 [Detailed Guide for Section 6](https://docs.google.com/presentation/d/1IQnqzBe-kMASDrICltffJVBc286n-oGAR2o8RrQXOfY/edit?slide=id.g2928d8f033d_0_136#slide=id.g2928d8f033d_0_136)

---

## 🚀 Outcome
By completing this lab, students will have learned how to:
- Design and connect databases in Laravel  
- Build and secure REST APIs  
- Develop a dynamic UI with Blade and localization  
- Implement authentication and authorization  
- Write automated tests  
- Deploy a secure, fully functional Laravel Coffee Shop application  

---

## 📂 Repository Structure
```
.
├── app/ # Application logic (Models, Controllers, Services)
├── database/ # Migrations and seeders
├── resources/views/ # Blade templates
├── routes/ # Web and API routes
├── tests/ # Unit and feature tests
└── ...
```

## ⚙️ Installation & Setup Final Lab Source Code

### 1. Prerequisites
Make sure you have the following installed:
- **PHP ≥ 8.2**
- **Composer** (dependency manager for PHP)
- **MySQL** or another supported database

### 2. Pull Source Code
```bash
git clone git@github.com:nghuuquyen/coffee-app.git
```

### 3. Install Dependencies
```bash
cd coffee-app
composer install
```

### 4. Configure Environment
```bash
cp .env.example .env
```
Update the `.env` file with your database credentials:
```
DB_CONNECTION=mysql
DB_HOST=
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password
```
Or if you are using SQLite, set it up like this:
```
DB_CONNECTION=sqlite
DB_DATABASE=/absolute/path/to/database.sqlite
```

### 5. Generate Application Key
```bash
php artisan key:generate
```

### 6. Run Migrations and Seeders
```bash
php artisan migrate --seed
```

### 7. Start the Development Server
```bash
php artisan serve
```

The application will be accessible at `http://localhost:8000`.

## 🖼️ Screenshots

Below are sample screenshots for the Laravel Coffee Shop Lab.

### 1. The Homepage
The homepage displays a list of coffee products with options to view details and add to cart.
![image](https://github.com/nghuuquyen/coffee-app/assets/14355905/7b6575b7-3097-4ab3-96b8-263f3dbf0624)

### 2. The Food Detail Popup / Add to Cart Button
The product detail popup allows users to note options and add items to their cart.
![image](https://github.com/nghuuquyen/coffee-app/assets/14355905/61e4c03e-ca28-486f-9715-02e69d445377)

### 3. The Bottom Cart Bar
The bottom cart bar allows users to view their selected items and proceed to checkout.
![image](https://github.com/nghuuquyen/coffee-app/assets/14355905/df12686e-5507-4cfe-926a-cc1831d0ab22)

### 4. The Checkout Page
The checkout page enables users to review their order and enter payment information.
![image](https://github.com/nghuuquyen/coffee-app/assets/14355905/199b1055-2bcd-4c7b-91aa-7ae103eaff3b)

### 5. The Thank You Page
The thank you page confirms the order has been placed successfully.
![image](https://github.com/nghuuquyen/coffee-app/assets/14355905/c32f0347-412c-4e53-94e0-873d9e6d5477)

### 6. The Invoice Page
The invoice page displays the order details and payment information.
![image](https://github.com/nghuuquyen/coffee-app/assets/14355905/f48a6e54-a16c-4c68-9741-b192024f548f)

### 7. The Email of the Invoice
The email of the invoice is sent to the user after successful payment.
![image](https://github.com/nghuuquyen/coffee-app/assets/14355905/2c627a0d-99a7-4f11-8d81-beb83accd845)

### 8. The Profile Page
The profile page allows users to view and update their personal information.
![image](https://github.com/user-attachments/assets/f03dadea-5220-4802-954a-6f3417edd68b)

### 9. The API Token Management Page
The API token management page enables users to create and manage their API tokens for secure access.
![image](https://github.com/user-attachments/assets/6aa1f0e3-f71a-43b6-8a72-735642415eb0)

## 📝 Notes
- Follow the detailed guides for each section to complete the lab.
- Ensure you have a working [knowledge of PHP and basic Laravel concepts](https://docs.google.com/presentation/d/1IQnqzBe-kMASDrICltffJVBc286n-oGAR2o8RrQXOfY/edit?slide=id.g2928d8f033d_0_62#slide=id.g2928d8f033d_0_62).
- Feel free to reach out if you encounter any issues or have questions.
- Happy coding and enjoy building your Laravel Coffee Shop application!


## 🎉 Conclusion
Thank you for participating in the Laravel Coffee Shop Lab! By completing this lab, you have gained practical experience in building a full-featured Laravel application. We hope this hands-on approach has solidified your understanding of Laravel and web development concepts. Keep practicing and exploring more advanced topics to further enhance your skills. Happy coding!

Code with ❤️ by [nghuuquyen](https://github.com/nghuuquyen)