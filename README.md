# Supermall-Fullstack-Platform
A production-grade full-stack mall management platform built with React, Django REST Framework, and MySQL, featuring role-based access, offers management, product discovery, analytics, Docker, and CI/CD.

## 🚀 Overview
SuperMall is a full-stack platform designed to manage multi-floor malls, shops, products, and offers with modern performance and production-ready engineering practices.  
This project demonstrates end-to-end full-stack development using **React + Django REST + MySQL**, fully containerized with **Docker**, automated via **GitHub Actions CI/CD**, and deployed on modern cloud platforms.

---

## ⭐ Key Features
### 🔐 **Authentication & Authorization**
- JWT Authentication (Login, Refresh, Logout)
- Role-based access (Admin, Shop Owner, Customer)

### 🛍️ **Mall & Shop Management**
- Multi-floor mall structure  
- Manage shops, products, categories & offers  
- Product comparison system  
- Advanced filtering & sorting (category, price, rating, floor)

### 📊 **Analytics API**
- Revenue analysis  
- Top-selling products  
- Offer performance insights  
- Campaign analytics endpoint

### ⚡ **Performance & Background Tasks**
- Redis caching for heavy endpoints  
- Celery background jobs  
- Optimized queries using `select_related` / `prefetch_related`

### 🐳 **DevOps & Deployment**
- Dockerized backend & services  
- GitHub Actions CI/CD pipeline  
- Frontend deployed on Vercel  
- Backend deployed on Render / AWS  
- Environment-based configuration

---

## 🧱 Tech Stack

### **Frontend**
- React.js  
- TailwindCSS  
- Redux Toolkit  
- Axios  

### **Backend**
- Django  
- Django REST Framework  
- MySQL  
- Redis (caching)  
- Celery (background workers)

### **DevOps**
- Docker  
- GitHub Actions  
- Vercel (Frontend Deployment)  
- Render / AWS (Backend Deployment)



  <img width="1186" height="651" alt="products list page" src="https://github.com/user-attachments/assets/6033971c-2531-44ce-ab47-d4b5628001f3" />

About_this_App

An Ecommerce app where users can purchase products by using their stripe card. Users are allowed to visit our website and free to look any product details. User needs to create an account on our website to proceed with the payment section. If a user want they can also delete their account anytime (NOTE: With the deletion of a user account all their info like Account details, Address details, Card details will be deleted as well)

The website also provides the flexibility to create a new stripe card if they do not have one, the user can also pay with other user stripe card (if they provide the right email address linked with the card and other card details like Card Number, Exp Month, Exp Year and CVC). The user can also detete their stripe card if they like (Caution: With the deletion of their stripe card their account related to that card will also be deleted as well).

App_Overview

Products_List_Page

This page displays all the available products on the website.
<img width="1186" height="651" alt="products list page" src="https://github.com/user-attachments/assets/783b1eaf-357e-412f-b25a-dad127ee5e65" />

Product_Details_Page


This page displays the details of the Product which user has selected from the products list page. Here, the user can see all the info of the Product such as product name, description, in stock or out of stock and pay with stripe button. For Admins, the website provides two more functionalities such as Updating the product and secondly deleting the product.

<img width="1180" height="594" alt="product details page" src="https://github.com/user-attachments/assets/1a4c7591-3000-435f-925a-6e93ceda197a" />


Product_Edit_Page
Only admins can visit this page, the page handles the editing of the Product in terms of image, name , description, price and in stock status.

<img width="1167" height="648" alt="product edit page" src="https://github.com/user-attachments/assets/bd678f62-293e-4ad0-8900-1afb9385b7be" />

Add_Product_Page

Only admins can visit this page, the pages handles the creation of product (requires product name, image, description, price and in stock status.

<img width="1176" height="516" alt="add product page" src="https://github.com/user-attachments/assets/85bc69f6-2d82-4b4b-bc28-a0760287feb6" />

Checkout_Page

This page displays the info of the product which user has selected for the purchase. The page Contains the product information and provides pay with stripe card option. The user can also save their card for future payments. The user can also select or edit their address from the page.

<img width="1158" height="634" alt="checkout page" src="https://github.com/user-attachments/assets/622916fd-35f9-44ab-b930-e63784e80bf3" />

Payment_Confirmation_Page

The page displays total amount info, the address selected by the user for delivery and the card number used for the purchase. The user can also select a different card and address from the same page if something wents wrong.

<img width="1219" height="625" alt="payment confirmation page" src="https://github.com/user-attachments/assets/81c00f33-ae6f-4d8a-bf69-8b3e47b101f8" />

Payment_Successfull_Page

The Page displays the confirmation of the product purchase. Also, provides info like which product is bought and how much amount was paid for it. Go to orders page is also provided to see the order details.

<img width="1202" height="299" alt="payment successfull page" src="https://github.com/user-attachments/assets/9f71036e-c327-42c4-b5eb-0e22e532a36d" />

Orders_Page_For_User

The page displays the list of all the orders made by user, with the details like their name, card number used, date of purchase, address etc.

<img width="1183" height="386" alt="ecommerce  orders page for normal user" src="https://github.com/user-attachments/assets/80957cac-3d2b-47ea-962c-686606edcf2e" />

Orders_Page_For_Admin

For admin user the page display the list of all users order information. The admin can change the status of product delivery status as well. A search bar is also provided to locate the orders with more flexibility (can search the orders by customer name, address and product name)

<img width="1239" height="542" alt="orders page for admin" src="https://github.com/user-attachments/assets/ec732492-b9f9-470f-8b05-9e7d34154042" />

Address_Create_Page

Here, the user can create their new address.


<img width="505" height="591" alt="address create page" src="https://github.com/user-attachments/assets/aaa88e50-1cf9-4cf9-8067-cb850819aa8d" />

Login_Page

Requires an Account on the Website

<img width="1150" height="452" alt="sign in page" src="https://github.com/user-attachments/assets/011734ce-2d06-40db-8e83-e9f5dee23702" />

Register_Page
<img width="1149" height="612" alt="sign up page" src="https://github.com/user-attachments/assets/748646b9-b593-4c07-8242-a9ea2ebbb49c" />

Delete_User_Account_Page

Here, the user can Delete their account (requires password confirmation)

<img width="1164" height="370" alt="delete account page" src="https://github.com/user-attachments/assets/f25f603e-9155-4a19-bd69-e207ed63343b" />
