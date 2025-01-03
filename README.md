# File-Sharing-Application
Project Introduction:
1. Problem statement:

The objective of this project is to create a secure file-sharing application that allows users to upload files, share them via unique links, and optionally password-protect their files. Additionally, the system tracks the number of downloads for each file, giving users insights into file activity. The application is currently built and hosted on a local server (localhost) using Node.js, Express, and MongoDB.

2. Introduction to Secure File Sharing::

File sharing systems need to prioritize both ease of access and security. This project ensures that users can share files conveniently while maintaining file security through optional password protection. Additionally, download tracking gives users an overview of file usage, providing analytics on how often files are accessed.

3. Tools used:

Node.js: The main backend technology for creating this application and managing server-side logic.

Express.js: A web framework used to build the server-side application and handle routes.

MongoDB: A NoSQL database used for storing file metadata, download tracking.

Multer: A middleware for handling file uploads in Node.js.

bcrypt: Used for encrypting passwords and securing sensitive information.

EJS (Embedded JavaScript): A templating engine for rendering HTML pages dynamically.

Project outline:
File Uploads with Shareable Links: Users can upload files to the server, and a unique link is generated for each file to facilitate easy sharing.

Password Protection: Users can choose to add a password to their files, ensuring that only authorized users can access the files.

Download Tracking: The system tracks the number of downloads for each file, providing users with insights into file activity.

Local Hosting: The application is currently deployed on localhost for testing and development purposes.

References:
Nodejs : https://www.w3schools.com/nodejs/

MongoDB : https://www.w3schools.com/mongodb/

Future Idea:
As mentioned above, currently this application is operating on localhost, in the future we can host it on cloud storage solutions like Google cloud or AWS.
