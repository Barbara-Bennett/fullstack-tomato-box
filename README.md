# TomatoBox Inventory Management WebApp
The TomatoBox Inventory Management WebApp is a comprehensive tool that assists intermediaries, known as "go-betweens," who play a crucial role between farm producers and merchants. This web application empowers go-betweens to efficiently manage their inventory of Tomato Boxes, enabling them to monitor stock levels with producers and merchants while tracking the boxes' condition. With customer registration, transaction logging, borrowed box tracking, and damage box management, go-betweens can make well-informed decisions, streamline operations, and foster strong relationships with producers and merchants.


## Introduction
This README provides an overview of the TomatoBox Inventory Management WebApp, including both the backend and frontend components. It covers setting up the project, running the development servers, and accessing the web application.


## Accessing the Web Application
[https://tomatobox.vercel.app/](https://tomatobox.vercel.app/)


## Project Structure
The project consists of two main components:

1. **Backend**: Built using Django and Rest Framework, the backend serves as the engine that powers the web application. It handles data processing, communication with the database, and serving data to the frontend. The backend repository can be found [here](https://github.com/Barbara-Bennett/backend-tomatobox).

2. **Frontend**: Built using React and Bootstrap5, the frontend provides the user interface for the TomatoBox Inventory Management WebApp. It interacts with the backend to display data and enable user interactions. The frontend repository can be found [here](https://github.com/Barbara-Bennett/frontend-tomatobox).


## Installation and Configuration
You can locate installations and configurations inside both the backend and frontend repositories.








##
##
## TOMATO BOX MANAGEMENT SYSTEM USER MANUAL

Welcome to the Tomato Box Management System! This manual will provide you with information on how to use all the available features in the system.

## Home Page
On the 'Home' page, you'll find a summary of information about the tomato boxes, including the total count of premium and common boxes in possession of producers, merchants, and the storehouse.

<img width="1432" alt="Screenshot 2023-08-14 at 9 53 20 PM" src="https://github.com/Barbara-Bennett/tomato-box/assets/97815099/b29fb923-b3c2-4b86-a29c-4c9def1cc90c">


## Producers Page
On this page, you can manage registered producers. The following operations are available:
- Add a new producer
- Edit information on existing producers
- Delete producers
- View the quantity of premium and common boxes held by each producer
  
<img width="1431" alt="Screenshot 2023-08-14 at 9 55 27 PM" src="https://github.com/Barbara-Bennett/tomato-box/assets/97815099/5656afa7-2868-4daf-87ff-1847e1140ca0">


## Merchants Page
Here, you can manage registered merchants. The following operations are available:
- Add a new merchant
- Edit information on existing merchants
- Delete merchants
- View the quantity of premium and common boxes held by each merchant
  
<img width="1438" alt="Screenshot 2023-08-14 at 9 56 12 PM" src="https://github.com/Barbara-Bennett/tomato-box/assets/97815099/b962b14b-988f-4a93-9ee1-36356fd864a6">


## Producers Transactions Page
Here, you can record transactions between you and the registered producers. The following operations are available:
- Add a new producer transaction
- Edit information on existing producer transaction
- Delete producer transaction

There are two types of transactions available:
- Lend: Lend boxes to a producer, increasing the box count in possession of the selected producer and the total box count in the 'Box Inventory.'
- Devolution: Receive back boxes from a producer, decreasing the box count of the selected producer and the total box count in the 'Box Inventory.'

Observation:
You can update the information of each transaction, except for the producer, transaction type, and box type selected during the transaction creation.

<img width="1436" alt="Screenshot 2023-08-14 at 9 59 05 PM" src="https://github.com/Barbara-Bennett/tomato-box/assets/97815099/c54a71ea-a057-4ab1-89c9-1fee8bf9b185">


## Merchants Transactions Page
Here, you can record transactions between you and the registered merchants. The following operations are available:
- Add a new merchant transaction
- Edit information on existing merchant transaction
- Delete merchant transaction

There are two types of transactions available:
- Lend: Lend boxes to merchants, increasing the box count in possession of the selected merchant and the total box count in the 'Box Inventory.'
- Devolution: Receive back boxes from a merchant, decreasing the box count of the selected merchants and the total box count in the 'Box Inventory.'

Observation:
You can update the information of each transaction, except for the merchant, transaction type, and box type selected during the transaction creation.

<img width="1434" alt="Screenshot 2023-08-14 at 9 59 40 PM" src="https://github.com/Barbara-Bennett/tomato-box/assets/97815099/ba0716cb-3866-4655-ae8b-b5328b7290c2">


## Box Inventory Page
Here, you can manage your tomato boxes. The following operations are available:
- Add new boxes
- Delete damaged boxes
- View the quantity of boxes in Storehouse
- View the quantity of boxes with producers
- View the quantity of boxes with merchants

There are two types of boxes:
- Premium Box: High-quality boxes for selected tomatoes.
- Common Box: Normal-quality boxes for tomatoes.

Functionality:
- Add new boxes: This increases the total box count in your inventory.
- Delete boxes with damage: This decreases the total box count in your inventory.

Observation
- Deletion operations are irreversible. Be cautious when deleting producers, merchants, or transactions.

<img width="1435" alt="Screenshot 2023-08-14 at 10 00 01 PM" src="https://github.com/Barbara-Bennett/tomato-box/assets/97815099/6d056f9e-80f3-4282-ba0b-e6243bb4bd94">


##
This manual should help you use all the Tomato Box Management System functionalities. If you have any further questions, don't hesitate to contact our support. Enjoy using the system for efficient Tomato Box Management!


