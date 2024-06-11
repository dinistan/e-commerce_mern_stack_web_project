NoLimit E-commerce Website README

Overview

Welcome to the NoLimit E-commerce Website README file.
This document will guide you through the setup, installation, and usage of our full stack e-commerce website built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

This website is designed for NoLimit, the biggest popular dressing shop in Sri Lanka. It features sections for Men, Women, and Kids, along with pages for About Us, Contact Us, FAQ, Terms, and Size Guide.
Users can create accounts, add products to their cart, and make purchases. An admin panel is also included for managing products.
Project Structure

The project is divided into three main parts:
1.	Front End
2.	Back End
3.	Admin Panel

Setup and Installation

Front End
1.	Navigate to the Front End Directory:
•	Open your command prompt (cmd) and navigate to the path of the front end directory.
•	Use the command cd path/to/front-end-directory to change the directory.
2.	Open the Project in Visual Studio Code:
•	Type code . to open the project in Visual Studio Code.
3.	Install Dependencies:
•	Open a new terminal in Visual Studio Code.
•	Run the command: npm install to install all necessary dependencies.
4.	Install React Router DOM (if needed):
•	If the project requires React Router DOM, install it using the command: npm install react-router-dom.
5.	Run the Front End:
•	Start the development server by running: npm start.


Back End
1.	MongoDB Setup:
•	Create an account on MongoDB.
•	Go to the Projects section and create a new project.
•	Provide a project name and create the project.
•	Navigate to the database section and create a new database.
•	Click on "Build Cluster", select M0 free server, choose Google Cloud, and name your cluster (default is cluster0).
•	Click "Connect" and set up a username and password.
•	Allow access from anywhere by setting the IP address permissions.
•	Go back to the database section, click "Connect", select "Compass", and copy the connection link.
2.	Install and Connect:
•	In the back end directory, open the terminal and run: npm install to install necessary packages.
•	Paste the MongoDB connection link into your configuration file and replace <password> with your MongoDB password.
•	Check the connection by visiting: http://localhost:4000/.
3.	Run the Server:
•	Start the server by running: node index.js.


Admin Panel
1.	Install Dependencies:
•	In the admin panel directory, open the terminal and run: npm install.
2.	Run the Admin Panel:
•	Start the admin panel by running: npm start.


Usage
•	User Functionality:
•	Users can sign up, log in, browse products in the Men, Women, and Kids sections, add products to their cart, and make purchases.
•	The website also includes informational pages such as About Us, Contact Us, FAQ, Terms, and Size Guide.
•	Admin Functionality:
•	The admin panel allows administrators to add, update, and remove products from the inventory.


Conclusion
You now have all the information needed to set up and run the NoLimit E-commerce website. Follow the steps carefully to ensure everything is installed and configured correctly. If you encounter any issues, refer back to this README for guidance. Enjoy using and managing the NoLimit E-commerce platform!

