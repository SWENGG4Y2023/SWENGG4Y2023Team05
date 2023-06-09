### **Design Document for Blinkit Food App.** 

## **Introduction:**

The Blinkit Food App is a mobile application that allows users to order food from various restaurants and have it delivered to their location. The app aims to provide a convenient and user-friendly interface for browsing menus, placing orders, and tracking deliveries. This document outlines the design and architecture of the Blinkit Food App.


## **System Architecture:**

The Blinkit Food App follows a client-server architecture, where the client application runs on users' mobile devices, and the server handles request processing and data storage. The key components of the system architecture include:


## **2.1 Client Application:**

The client application is developed for iOS and Android platforms using native mobile development frameworks. It provides the user interface for browsing restaurants, viewing menus, placing orders, and tracking deliveries. The client app communicates with the server using RESTful APIs.


## **2.2 Server Application:**

The server application handles the core business logic and data storage. It is responsible for processing user requests, managing restaurant and menu data, and coordinating deliveries. The server application is built using a scalable and reliable backend framework like Node.js or Django, and it utilizes a relational database (e.g., MySQL, PostgreSQL) for data storage.


## **2.3 Database:**

The database stores various types of data, including user information, restaurant details, menu items, orders, and delivery information. It ensures data integrity and provides efficient querying capabilities. The choice of database technology depends on the specific requirements and scalability needs of the application.


## **2.4 Third-Party APIs:**

The Blinkit Food App integrates with external services such as payment gateways, geolocation services, and SMS gateways. These APIs enable secure payment processing, accurate location tracking, and real-time notifications for order status updates.



## **3. User Interface Design:**

The user interface (UI) of the Blinkit Food App should be intuitive, visually appealing, and easy to navigate. The design principles to consider include:


## **3.1 Home Screen:**

The home screen provides a search bar to find restaurants and a list of popular or nearby restaurants. It also displays promotional banners and featured menu items.


## **3.2 Restaurant Listings:**

The restaurant listings screen shows a list of available restaurants, sorted by proximity or user preferences. Each listing includes restaurant name, ratings, cuisine type, and a thumbnail image. Users can filter restaurants based on cuisine, price range, and other criteria.


## **3.3 Menu Display:**

The menu screen displays the restaurant's menu items, categorized by appetizers, main courses, desserts, etc. Each item includes a name, description, price, and an optional image. Users can add items to their cart and customize them with options like toppings or special instructions.


## **3.4 Cart and Checkout**

The cart screen shows the items added by the user, along with their quantities and total price. Users can modify the cart contents, apply coupons or discounts, and proceed to the checkout screen. The checkout screen collects user details, delivery address, and payment information.


## **3.5 Order Tracking**

After placing an order, users can track its progress in real-time. The order tracking screen shows the current status of the order, estimated delivery time, and the delivery person's details. Users receive notifications at key milestones, such as order confirmation, dispatch, and delivery.



## **4. Security and Privacy**

The Blinkit Food App follows industry-standard security practices to protect user data and ensure privacy. Some key security measures to implement include:

Secure transmission of data using HTTPS protocol.
Hashing and encryption techniques for sensitive user information, such as passwords and payment details.
Role-based access

## **Activity Diagram:**
![image](https://github.com/SWENGG4Y2023/SWENGG4Y2023Team05/assets/75153899/a3324fc8-418b-4948-92e9-323b526377f6)
