
|  Abdulrahman Rami Bargouth| A23MJ4014 |  
|Thamer Nasser Alharbi | A23MJ4015 |
|  Anika Rahman Antu | A23MJ9013 |  


### System Design Final Report for Shopping Website

----------

#### 1 Overview of the Project

The goal of this project is to design and develop a comprehensive shopping website that offers users a seamless and secure online shopping experience. The website will allow users to browse products, add items to a shopping cart, and complete purchases smoothly using a secure checkout process. Additional features include user accounts, order tracking, and product search and filter options.

----------

#### 2 Problem Statement

The current process of shopping, both online and offline, often involves numerous challenges such as lack of product availability, security, product quality and reliability of the seller . Customers seek a reliable and user-friendly online platform that addresses these issues while providing a secure and efficient shopping experience.

**Product Availability**: Customers often face difficulties in finding accurate and comprehensive about products. Incomplete or misleading product descriptions can result in unsatisfactory shopping experiences.

**Security Concerns**: Security is a major concern for customers when shopping online. Issues such as data breaches, insecure payment processes, and lack of trust in website security can deter customers from completing transactions.

**Product quality:** refers to the degree to which a product meets certain standards, fullfills customer expectations, and performs its intended functions effectively. High product quality is essential for building trust with customers

----------

#### 3 Proposed Solutions

Implementing these solutions will enhance customer satisfaction, build trust, and improve the overall shopping experience on the e-commerce platform.

To address the identified problems, we propose the development of a shopping website with the following features:

**1.1** **Inventory Management System**: Implement an advanced inventory management system that tracks stock levels in real-time. Use predictive analytics to forecast demand and ensure optimal stock levels.

**2.1 Two-Factor Authentication (2FA)**: Implement two-factor authentication for customer accounts to add an extra layer of security beyond just usernames and passwords.

**3.1 High-Quality Images and Videos**: Use high-quality images and videos to give customers a clear and accurate view of the product from multiple angles.

----------

#### 4 Current Business Process/Workflow

Currently, customers either visit physical stores or navigate through multiple online platforms to find and purchase products. This process can be time-consuming and lacks centralization, leading to a fragmented shopping experience.

Since most of the customers prefer using online website. The process goes as below:

Finding our website by using e-commerce.

Choose what kind of product he’s looking for (clothes, games , food or grocers).

Send it to cart

payment

----------

#### 5 Logical DFD (AS-IS)

The AS-IS logical DFD illustrates the current shopping process, highlighting how users interact with various elements such as physical stores, websites, and payment systems.

----------

#### 6.0 System Analysis and Specification

**6.1 Logical DFD TO-BE System (Context Diagram, Diagram 0, Child)**

The TO-BE logical DFD outlines the desired system architecture, illustrating the flow of data between users, the shopping website, and external systems (e.g., payment gateways, shipping services).

**Context Diagram:**

-   in the beginning the customer has to confirm the order then the employer will check in the inventory system if the item is available or not then the customer has to pay for the website for delivery your order to you

**Diagram 0:**

-   we have to inputs there are customer and the employees , the customer to send the order and the employees for checking the order then when they create the order
-   1.0 the information of customer will go to the data store for the website then the order go to pay the order
-   2.0 the customer has to pay the payment for the order to continue the processing then in the last we have confirm order
-   3.0 the employees has to confirm the order and they will send the order and the order invoice to the customer.

**Child Diagrams:**

-   1.0 ( Create Order)

Create the order we have two inputs , these are customer order requests and customer information the customer request will process the receive order

1.1 and the customer information will process the verify customer

1.2 information then after receive order we have order details and for the verify customer information will output the verified customer’s information then together will process, valied the order.

1.3 then then it will save the order.

1.4 and save order details and we move out to pay order

-   2.0 ( Pay order)

first we have to payment details then it will process the process information payment 2.1 then we have payment request it will process the verify payment.

2.2 then we have confirmation payment it will process the update order status

2.3 in the last we have confirm order

-   3.0 (Confirm Order )

we have two inputs, these are order details and payment confirmation to process the generate invoice.

3.1 to have order invoice then it will process the confirmation customer.

3.2 to have order confirmation and processing the update customer records.

3.3 to have update customer records.

**6.2 Process Specification (based on Logical DFD TO-BE)**

Each process in the logical DFD is specified with detailed descriptions of inputs, outputs, and the steps involved.

----------

#### 7.0 Physical System Design

**7.1 Physical DFD TO-BE System (Diagram 0, Child, Partitioning, CRUD Matrix, Event Response Table, Structure Chart, System Architecture)**

**Diagram 0:**

-   Once the customers find our website, this is the following proceders.
-   After log-in, the customer click on the items.
-   The items sent to the cart.
-   Payment time.
-   Once the payment is confirmed.
-   Place order.

**Child Diagrams:**

-   1.1  Save customer informations.
-   2.1 Select payment method (the customer must choose the payment method wither  they want it by card or cash on delivery).
-   2.2 Packing the orders nicely
-   2.3 Contact the delivery company
-   3.1 check the customer order.
-   3.2 send message to delivery company.
-   3.3 place a propriate date to receive the order.

----------

#### 8.0 System Wireframe (Input Design, Output Design)

**Input Design:**

The user must enter his information, such as:

-   To log-in (customer’s name, age, phone number and his/her email)
-   Payment requirement (card holder name and number)
-   Address location.

**Output Design:**

-   Packing the orders properly and nicely.
-   Receiving  the products in good condition.
-   Give the customers promotion so they order again.

----------

#### 9.0 Summary of the Proposed System

The proposed shopping website aims to revolutionize the online shopping experience by offering a user-friendly, secure, and efficient platform. By addressing the current challenges and implementing the proposed features, the new system will streamline the shopping process, enhance customer satisfaction, and drive business growth.

This System Design Final Report outlines the development and implementation of a comprehensive shopping website aimed at addressing the challenges faced by customers in the current shopping environment. The proposed system focuses on enhancing product availability, ensuring security, and maintaining high product quality.

Overall, this project represents a significant step towards creating a reliable, efficient, and customer-centric online shopping platform.
