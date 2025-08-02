**KaptureEvent**

KaptureEvent is a full-stack event management platform designed to streamline the process of creating, managing, and discovering events. The application is built with a clear separation between the frontend user interface and the backend API, allowing for a scalable and maintainable architecture.

**Key Features**
Event Management: Create, update, and delete events.

User Authentication: Secure user sign-up and login functionality.

Event Discovery: Browse and search for a variety of events.

Responsive UI: A user-friendly interface that works well on both desktop and mobile devices.

**Tech Stack**
Frontend: 

REACT JS

TAILWIND CSS

Backend (API):

Java SPRINGBOOT

JavaScript

Repository Structure
This repository is organized into two main project folders:

Project-Kapture-Events-API-main/: Contains the backend API services written in Java. This is the core logic for event management, user authentication, and data handling.

Project-Kapture-Events-Frontend-main/: Contains the user-facing application built with JavaScript and CSS. This project interacts with the backend API to display events and manage user interactions.

Getting Started
To get the project up and running on your local machine, follow the steps below.

Prerequisites
Before you begin, ensure you have the following installed:

Node.js & npm: For the frontend.

Java Development Kit (JDK): For the backend.

A code editor (e.g., VS Code).

1. Clone the Repository
First, clone this repository to your local machine using git:

git clone https://github.com/Sure-2411/KaptureEvent.git
cd KaptureEvent

2. Set up the Backend (API)
Navigate to the API directory and run the application.

cd Project-Kapture-Events-API-main/
# Run the Java application (e.g., using a Spring Boot or similar command)
# Replace 'your-build-command' with the appropriate command for your project.
# For example:
# ./mvnw spring-boot:run

3. Set up the Frontend
Open a new terminal, navigate to the frontend directory, install the dependencies, and start the development server.

cd Project-Kapture-Events-Frontend-main/
npm install
npm start

The frontend application should now be running locally and connected to the backend API.

Contribution
Contributions are welcome! If you have suggestions for new features, bug fixes, or improvements, feel free to open an issue or submit a pull request.
