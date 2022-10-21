# PHYSICAL-FITNESS-PERSONAL-MANAGEMENT-SYSTEM
Physical fitness is a person’s ability to perform daily activities with optimal performance. Fitness management is an interdisciplinary field that blends scientific knowledge of exercise physiology and fitness studies with practical business skills thus an online application personal system is created to discover this.

Physical Fitness Personal Management System
Table of Contents
research problem
objectives
Users
Technologies
[ Run website](#Run website)
REQUIREMENTS SPECIFICATION
Technical Requirements
Non-functional requirements
Functional Requirements
Users Module
[physical fitness PMS-log in system](#physical fitnes PMS-log in system)
pages module
Software Design Description

User Interface Design
Login Page
Registration Page
campaign Page
voting Page
Database package
Users Table
votes-Table

Problem Statement
Owing to the rapid development of city, busier modern life without space to exercise, the gymnasium needs to exercise development. Regular forms of exercise reduce risk of mortal diseases such as heart disease and even depression .I have come up with an application that will make physical fitness easier to work on and how to improve the quality of personal management system in physical fitness areas such as the gymnasiums ,parks or even homes.

Objectives
The main objective of this project is to create a physical fitness personal management system web based application. This can be broken down into:



To create a users management module that will allow registration of students for voting purposes,login.
To create a system that will allow users to follow along in the campaing.
To create an voting system log in system that will allow users to votes and campaign.
To create a real time project that when someone votes can see they voted for.
Users
campus students
System administrators.
Technologies
The system we build on JAM stack with the following technologies

Javascript -EJS
HTML,SCSS
MONGO DB
Run Website
To run this website

clone the repository to your local machine.
git clone <url>
install dependancies
npm install
run the app
npm start
REQUIREMENTS SPECIFICATION
Technical Requirements
You need to use a phone or laptop to access the website.

Non-functional requirements
Data should be encrypted.
The system should be light weight for ease of access and should within two seconds.
Should be responsive to different screen sizes.
Functional Requirements
Users Module
Registration
login
Password
campaing module
log in
upload your campaign
voting module
you just get in to the page and vote
Software Design Description
User Interface Design
Landing Page
The landing page is expected to look as shown below.

Landing Page

Login Page
The Login Page Design: Login Page

Registration Page
The sign up design: Sign Up page

Campaign page
Campaign page

Voting page
voting page

Users Table
Id - This will be auto increment which will the unique identifier for the user
email - This will be a school email
name first name and second name - User given name
password - should be atleast 6 characters
vote Table
id
person voted for
voter id
