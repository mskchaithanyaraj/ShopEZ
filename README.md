
# ShopEZ - MERN Stack Application

ShopEZ is a full-stack e-commerce application built using the MERN stack (MongoDB, Express, React, Node.js) as part of the Smart Bridge project. This application provides a seamless shopping experience for users, allowing them to browse, filter, and purchase products, as well as manage orders. It includes both user and admin functionalities.

## Table of Contents
1. [Project Structure](#project-structure)
2. [Installation](#installation)
3. [Environment Variables](#environment-variables)
4. [Usage](#usage)
5. [Features](#features)
   - [User Features](#user-features)
   - [Admin Features](#admin-features)
6. [Tech Stack](#tech-stack)
7. .[Project Report](#project-report)
8. [Demo Video](#demo-video)

---

## Project Structure

The project is organized into two main folders:
- *client/* - Contains the front-end React code for the application.
- *server/* - Contains the back-end Node.js and Express code.

## Installation

### 1. Clone the Repository
 bash
git clone https://github.com/SnehaYadavWorld11/Mern_Stack-ShopEZ.git
cd Mern_Stack-ShopE


### 2. Install Dependencies
IGNORE THE ERRORS WHILE INSTALLING, CONTINUE TO RUN THE APPLICATION
#### Server
 bash
cd server
npm install


#### Client
 bash
cd client
npm install


## Environment Variables

Add your own configuration in server.js in the root of the *server* folder. 

mongoose.connect(mongodb+srv://username:password@url/ShopEZ?retryWrites=true&w=majority&appName=Cluster)


## Usage
IF YOU STILL ENCOUNTER ANY ERRORS WHILE RUNNING THE SERVER OR CLIENT, REMOVE THE NODE_MODULES FOLDER AND RUN npm install. NOW TRY AGAIN, IT WILL WORK
### Running the Server
The server runs on port 5000.
 bash
cd server
node index.js || npm run dev


### Running the Client
The client will start on port 3000 by default.
 bash
cd client
npm run dev


## Features

### User Features
1. *User Registration and Login*:
   - Register as a new user or log in with existing credentials.
     
![Screenshot 2025-04-11 142955](https://github.com/user-attachments/assets/508ad3a0-6334-4e09-b2ba-b9338c30fd56)

![Screenshot 2025-04-11 143135](https://github.com/user-attachments/assets/adc9955b-619b-49eb-9b80-c19a0f006f3d)

![Screenshot 2025-04-11 142834](https://github.com/user-attachments/assets/2e4bfcdd-1343-45bc-9270-4f91321ec0e4)

2. *Product Browsing and Filtering*:
   - Filter products by categories, gender, popularity, price (low to high or high to low).
     
![Screenshot 2025-04-11 143402](https://github.com/user-attachments/assets/67dbaee7-13a6-48ee-ba5a-59ea050d6cd2)

3. *Shopping Cart*:
   - Add products to the cart and proceed to checkout.

![Screenshot 2025-04-11 164804](https://github.com/user-attachments/assets/85609028-bc6c-44ac-bcb2-465151a9ba5c)
![Screenshot 2025-04-11 170609](https://github.com/user-attachments/assets/136f11ff-c3bb-4dda-a278-861dd072d6de)

4. *Checkout and Order Placement*:
   - Provide details such as address, city, pincode, mobile number, notesto place an order.
     
![Screenshot 2025-04-11 143534](https://github.com/user-attachments/assets/a81295aa-db83-4cee-9596-78e293e220b6)

![Screenshot 2025-04-11 143633](https://github.com/user-attachments/assets/3b393591-da0a-43b3-b717-34533cfdf8de)

5. *Order Details*:
   - View orders from the user profile page.

![Screenshot 2025-04-11 143947](https://github.com/user-attachments/assets/abc996ef-efdb-4921-adf2-b89761228c9d)


### Admin Features
1. *Admin Login*:
   - Login using admin credentials:
     - *Email*: admin@gmail.com
     - *Password*: admin

![Screenshot 2025-04-11 144043](https://github.com/user-attachments/assets/9d1689e7-1457-4a11-b247-4472dde8741f)

2. *Order Management*:
   - View the total number of orders and their details, including the number of orders placed by each user.

![Screenshot 2025-04-11 144144](https://github.com/user-attachments/assets/6983805c-c3d8-43f1-a247-2431491adc39)

![Screenshot 2025-04-11 144245](https://github.com/user-attachments/assets/ae4b46a4-5309-4484-8934-3086603c26f6)


3. *Product Management*:
   - Add, update, or remove products.
   - Add products with categories, images, brands, etc.

![Screenshot 2025-04-11 144110](https://github.com/user-attachments/assets/70d43c2d-fb2d-4fba-9d36-4bc96edfde1f)

![image](https://github.com/user-attachments/assets/4b4df83d-5ff2-471f-869a-8019e9455a2e)

4. *Order Management*:
   - View all placed orders, update their status (e.g., Order Placed, In Transit, Delivered), and cancel orders if necessary.

![Screenshot 2025-04-11 144245](https://github.com/user-attachments/assets/b6387410-bd27-4c96-aeeb-8b28f5c170fc)![image](https://github.com/user-attachments/assets/e0a86630-c973-4c9f-8116-bbd0b5a69668)

## Tech Stack
- *Frontend*: React, CSS, Redux Toolkit
- *Backend*: Node.js, Express.js
- *Database*: MongoDB

## Project Report
https://drive.google.com/drive/folders/14kvTuDGft9AUMGe1DLKJdONmnJO80D-q?usp=sharing

## Demo Video
- Watch a quick demo showcasing the installation process, as well as the features and functionalities of the ShopEZ Ecommerce Application. The demo will cover both user and admin functionalities.

https://drive.google.com/file/d/1sf0OhwgIi3d6qpX8PHjiiuWHaaonJbmT/view?usp=sharing

[https://drive.google.com/file/d/1znDPKbi1CsA1oLESelnp5fbzPIrtxCfw/view?usp=sharing](https://drive.google.com/file/d/1jNxbOSGoIyT39YXXcZXKSpkKCFA1USoF/view?usp=sharing)
