# WebAppDev_Project
This repository contains the implementation of my group's final project for my Web Application Development course in the spring of 2017.
Additional Authors: Henry Phelps, Patrick Fei

## Frameworks Used
* Express 4.13.4
* Socket.io 1.4.5

## Front-End Development
* HTML
* CSS
* Javascript

## Back-End Development
* Node is used to launch the application on a server
* Express framework gives added functionality to Node
* Socket.io faciliates the two-way communication between the server and client

### Application Description
This application was designed as a guide/tool for students relative to major choice and major completion. Essentially, the first landing page of our application will give a dropdown menu with possible Boston College majors. For our purposes in this project, we chose to code for just 3 major choices: Economics, Computer Science B.S., and Computer Science B.A. Had we more time or resources, we would have expanded this list (Creating a new major though required a fair amount of hardcoding records: courses, course codes and descriptions, course pre-requisites, etc.).
Once the client has selected the major, this value is sent to the server which in turn responds with all the required classes for that major. The client is then instructed to select the classes he or she has already taken. These values are submitted to the server.
The server then responds with the final page of our application (although backtracking functionality is available). The server constructs a prerequisite tree, so that students can see not only what they have left to take, but what course must be completed prior to other courses remaining.
The prerequisite lines in the tree are color-coded corresponding to the specific relationship. There is also a bottom menu where the client can see different courses. Courses can be clicked on which brings up a description window which contains the course code and course description.
