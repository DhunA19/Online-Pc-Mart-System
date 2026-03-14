💻 Online PC Mart
📌 Project Overview

The Online PC Mart project is developed as part of the Master of Computer Applications (MCA) academic curriculum. The primary goal of this project is to transform theoretical knowledge into a practical real-world web application.

In today’s digital world, buying a computer system can be confusing due to component compatibility issues, lack of guidance, and difficulty comparing different systems. The Online PC Mart platform provides a simple and efficient solution by allowing users to build their own PC or choose from prebuilt systems.

The platform enables users to customize PC components, filter systems based on requirements, save builds, and purchase systems online, making the computer-buying process easier and more user-friendly.

🚀 Features
🔧 Custom PC Builder

Users can build their own PC by selecting compatible components such as:

Processor (CPU)

Motherboard

RAM

Storage (SSD / HDD)

Graphics Card (GPU)

Power Supply Unit (PSU)

Cabinet

The system ensures that users can experiment with different configurations and create a PC according to their needs.

🖥 Prebuilt PC Systems

Users who prefer ready-made systems can choose from different categories such as:

🎮 Gaming PCs

💼 Professional PCs

🏠 Basic / Home PCs

These prebuilt options make it easy for users who do not want to manually configure components.

💰 Budget Based Filtering

Users can filter PCs based on budget range, helping them quickly find systems that match their financial requirements.

💾 Save Custom Builds

Users can save their PC builds

Saved builds can be edited later

Users can purchase the saved configuration anytime

🛒 Online Purchase System

Users can purchase:

Custom built PCs

Prebuilt systems

This feature makes the platform a complete PC shopping solution.

🛠 Technology Stack
Frontend

React.js

HTML

CSS

JavaScript

React is used to create a responsive and interactive user interface.

Backend

Spring Boot

REST API

Spring Boot handles server-side logic, API requests, and system operations.

Database

MySQL

MySQL is used to store:

User information

PC components

Custom builds

Orders and purchase history

📂 Project Structure
Online-PC-Mart
│
├── frontend
│   ├── src
│   ├── components
│   ├── pages
│   └── App.js
│
├── backend
│   ├── controller
│   ├── service
│   ├── repository
│   ├── model
│   └── application.properties
│
└── database
    └── MySQL scripts
▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/online-pc-mart.git
2️⃣ Setup Backend (Spring Boot)

Open backend folder.

Run the project using:

mvn spring-boot:run

or run using Spring Tool Suite / IntelliJ / Eclipse.

3️⃣ Setup Database

Install MySQL

Create database

CREATE DATABASE pcmart;

Update database details in:

application.properties

Example:

spring.datasource.url=jdbc:mysql://localhost:3306/pcmart
spring.datasource.username=root
spring.datasource.password=yourpassword
4️⃣ Run Frontend

Go to frontend folder:

cd frontend
npm install
npm start

The application will start on:

http://localhost:3000

🎯 Project Objectives

The main objectives of the project are:

Simplify the computer buying process

Provide component compatibility guidance

Allow users to build custom PCs

Provide categorized prebuilt systems

Enable budget-based filtering

Allow users to save and purchase builds

📚 Learning Outcomes

During the development of this project, the following skills were improved:

Full Stack Development

React Frontend Development

Spring Boot Backend Development

REST API Integration

Database Management

Software Engineering Practices

System Design

📖 Conclusion

The Online PC Mart project provided valuable practical experience in designing and developing a full-stack web application. It demonstrates how theoretical concepts learned during the MCA program can be applied to build real-world solutions.

This platform aims to simplify the PC buying experience for users while also serving as a useful academic reference for students and developers interested in similar projects.

👨‍💻 Author

DHUN
MCA Student
Full Stack Developer
