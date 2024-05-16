EdVenture ERP System
Description
Welcome to the EdVenture ERP System repository! This system is designed as a comprehensive tool to facilitate operations management at EdVenture Park. The ERP system enables administrative users to send appointment and rejection emails directly from the dashboard with a single click, enhancing the efficiency of communication processes.

The application includes a public-facing form where prospective members or employees can apply to join EdVenture Park. Admin users can then review these applications through the admin dashboard and send out acceptance or appointment letters, as well as rejection emails, as needed. This system streamlines the initial contact and follow-up process, making administrative tasks simpler and more efficient.

Prerequisites
Before you begin, ensure you have the following installed:

Node.js
npm (Node Package Manager)
Git
A code editor like Visual Studio Code
Installation & Setup
1. Clone the Repository
First, clone the repository using SSH:

bash
Copy code
git clone <SSH_KEY_URL>
Replace <SSH_KEY_URL> with the actual SSH URL of the repository.

2. Set Up the Backend
Navigate to the dummy folder, install dependencies, and start the backend server:

bash
Copy code
cd dummy
npm install -y
npm start
This will start the backend server, typically running on http://localhost:3000.

3. Set Up the Frontend
Open a new terminal window or tab. From the repository root, navigate to the edventure-frontend folder, install dependencies, and start the frontend application:

bash
Copy code
cd edventure-frontend
npm install -y
npm start
This will launch the frontend application, typically accessible via http://localhost:3000.

Admin Login
The login page is designed exclusively for admins. Use the following credentials to access the admin dashboard:

Username: huda
Password: huda
After logging in, navigate to the 'Admin' page and click on 'Pending' to view submission details.

Features
Application Submission Form: A public form available for potential applicants to submit their details.
Admin Dashboard: Allows admins to manage submissions, send appointment letters, and issue rejection emails effortlessly.
Data Storage
Data for submissions is stored in submission.json within the dummy directory. This setup does not use MongoDB or any other database.

Additional Notes
Ensure both the backend and frontend servers are running concurrently to fully utilize the functionality of the ERP system.
The system's source code can be accessed and modified within the dummy and edventure-frontend folders using your preferred code editor (e.g., Visual Studio Code).
For further information or support, please check the mail to code.huda@gmail.com
