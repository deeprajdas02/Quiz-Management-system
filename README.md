# Quiz-Management-system
The ONGC Quiz Management App System is a web application built using React and PHP that serves as a comprehensive solution for managing and conducting quizzes within the ONGC organization. This system is divided into three main folders: "ongc," "login-system," and "cra." The "ongc" folder contains the PHP application for ONGC admin users to manage the quiz database, including creating, updating, and deleting questions. The "login-system" folder houses the PHP application responsible for user authentication and authorization. Once authenticated, users can access the quiz page in the "cra" folder, which is implemented in React. The React app fetches questions from the SQL database managed by ONGC admin and provides a user-friendly interface for answering quiz questions. The system also offers functionality to display quiz results, sorted by quiz attempts, for authorized users, viewable exclusively by admin users. Admin users have the ability to publish results as needed.

Folder Structure
1. ongc
This folder contains the PHP application for ONGC admin users to maintain the quiz database. Key features include:

Creating and managing quizzes,
Adding, updating, and deleting questions,
Starting and ending quizzes,
Managing quiz data in the SQL database.
![image](https://github.com/deeprajdas02/Quiz-Management-system/assets/77189362/0ac7f0ba-be55-45a2-9550-42e51c1fa5f3)
![image](https://github.com/deeprajdas02/Quiz-Management-system/assets/77189362/ada9326e-9699-4ac1-bbcf-3b7079d33e0c)

2. login-system
In this folder, you will find the PHP application responsible for user authentication and authorization. Key features include:

User registration and login,

Authorization control to ensure only authorized users access the quiz section,

Secure user authentication and session management.
![image](https://github.com/deeprajdas02/Quiz-Management-system/assets/77189362/79a6c447-561f-4f9d-8103-c68e4e821c9f)
![image](https://github.com/deeprajdas02/Quiz-Management-system/assets/77189362/0c96b08b-b1b5-4bad-b0b7-fba4a999f9ed)

3. cra
The "cra" folder houses the React application responsible for the user interface, question verification, and validation. Key features include:

Displaying quizzes for authorized users,
Fetching quiz questions from the SQL database managed by the admin,
User-friendly and responsive quiz interface,
Verification and validation of user responses,
Displaying quiz results for authorized users, sorted by quiz attempts.
![image](https://github.com/deeprajdas02/Quiz-Management-system/assets/77189362/8109b7d9-6d29-48e7-af6e-e2f3a43ed7fb)


Getting Started
Prerequisites
Before you can use the ONGC Quiz Management App System, you'll need the following:

Web server (e.g., Apache) with PHP support.
MySQL database for storing quiz data.
Node.js and npm for running the React app.
Installation
Set Up the Database:

Create a MySQL database and import the provided SQL schema to set up the quiz database.
ongc (PHP App):

Configure the database connection in the PHP files within the "ongc" folder to point to your MySQL database.
Deploy the "ongc" folder on your web server.
Access the admin site to create quizzes and manage questions.
login-system (PHP App):

Configure the database connection in the PHP files within the "login-system" folder.
Deploy the "login-system" folder on your web server.
Users can register and log in here, with authorization to access quizzes.
cra (React App):

Navigate to the "cra" folder.
Run npm install to install the required dependencies.
Configure the React app to communicate with the PHP API endpoints for user authentication and quiz data.
Run npm start to start the React app. It will be accessible at a specified URL.
Usage
Admin Users:

Access the "ongc" folder to create quizzes and manage questions.
Start and end quizzes as needed.
View and manage quiz results.
Authorized Users:

Register and log in through the "login-system" folder.
Access quizzes through the "cra" folder.
Attempt quizzes, review results, and check your progress.
Admin Users (Result Publication):

Admin users can publish quiz results when they choose.
Additional Notes
Ensure proper security measures are in place to protect sensitive user and quiz data.

Regularly back up the database to prevent data loss.

Secure the PHP and React applications from unauthorized access.

Keep the system up to date with the latest security patches and updates.

Optional Extended Description The ONGC Quiz Management App System not only simplifies quiz administration but also introduces a layer of interactivity and engagement for quiz participants. With a well-structured folder system, powerful features, and a carefully planned user journey, this system provides ONGC with a robust platform for knowledge assessment.

As a testament to its flexibility, the system caters to both ONGC admin users responsible for creating and maintaining quizzes and authorized users looking to expand their knowledge base. The system is fortified with security measures, ensuring that sensitive data is safeguarded throughout the process.

A particularly noteworthy feature is the ability of ONGC admin users to schedule quizzes, allowing for tailored assessments that align with ONGC's training and development goals. This capability ensures that quizzes are conducted at the most opportune times.

The "cra" folder, powered by React, introduces a rich and immersive quiz-taking experience, making learning engaging and enjoyable. It is designed to accommodate a variety of quizzes, making it versatile for different types of knowledge assessments within the organization.

To enhance the educational experience, the React app incorporates verification and validation mechanisms to ensure the accuracy and fairness of quiz results. It displays results in an easy-to-read format, offering insights into individual and collective performance, which can be vital for ONGC's training and development efforts.

The ONGC Quiz Management App System is more than a tool; it is an investment in ONGC's continuous learning and development, a commitment to ensuring that knowledge remains relevant and up-to-date in a dynamic industry. The system's optional extended description underscores its role as a central pillar in ONGC's pursuit of knowledge excellence.
