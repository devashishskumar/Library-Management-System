📖 Library Management System

A book management system designed for libraries, facilitating seamless book tracking and user interactions.

	Note: This is not an e-commerce platform—there is no payment system involved.

🏛 System Overview

The application consists of two user roles:

🔹 ADMIN
	1.	Manage Books – Add, update, remove, or delete books.
	2.	User Management – View user details such as name, ID, and borrowed books.
	3.	Request Handling – Approve or reject book requests and confirm returns.
	4.	Fine Management – Apply charges for overdue book returns.

🔹 CLIENT (User)
	1.	Browse Books – Search and check book availability.
	2.	Book Requests – Request to borrow a book.
	3.	Profile Management – Perform CRUD operations on their dashboard.

🛠 Technology Stack

Frontend:
	•	React (v18.2.0)
	•	Bootstrap

Backend:
	•	Node.js (v18.16.0)
	•	Express (v4.18.2)
	•	MongoDB (v6.0.6)
	•	Mongosh (v2.0.2)

🚀 Running the Project Locally

1️⃣ Clone the Repository

git clone git@github.com:devashishskumar/Library-Management-System.git

2️⃣ Navigate to Frontend & Backend

cd frontend  
cd backend  

3️⃣ Install Dependencies

Run the following command in both frontend and backend directories:

npm install

	Note: In the backend, create a .env file and copy the values from .env.example.

4️⃣ Start the Application

Run both frontend and backend servers:

npm run dev

	Backend Info: If you encounter any backend-related issues, refer to the /backend/BackendInfo/ folder.

5️⃣ Set Up the Database
	•	Ensure your MongoDB server is running (check via Windows Services).
	•	Open MongoDB Compass (download if necessary).
	•	Import database collections from the mongoDatabase folder.

# Import respective .JSON files into the database collections

🐳 Running with Docker
	1.	Populate the MongoDB database as explained in Step 5 above.
	2.	Update the .env file with the correct CONNECTION_URL.
	3.	Navigate to the project root folder:

cd LIBRARYMANAGEMENTSYSTEM_MERN/

	4.	Run the application with Docker:

docker-compose up

🔑 Default Login Credentials

	Ensure you have imported the userdetails JSON file into the database collections.

Admin Login
	•	Email: admin@gmail.com
	•	Password: admin

User Login
	•	New users can sign up through the SignUp Page.

📌 Key Takeaways
	1.	Code comments are like love letters to your future self—leave them wisely.
	2.	If you can’t solve it today, document it. Your future self will thank you!

💡 Lessons Learned

This project was built with React, Bootstrap, Node.js, Express, and MongoDB, focusing on seamless book management and user interactions in a library environment.
