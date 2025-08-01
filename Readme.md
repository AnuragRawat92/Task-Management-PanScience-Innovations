✅ Task Management System — PanScience Innovations
A secure, role-based Task Management System built using the MERN stack, designed to streamline task assignment, tracking, and performance review for Admins and Users. Features include user and task CRUD operations, feedback workflows, performance charts, document attachments, and Docker-based deployment.

🔗 Live Demo:
🌐 Live App
📂 GitHub Repo
📫 Postman Workspace

✨ Features
🔐 Authentication & Authorization
JWT-based login/registration.

Secure role-based routing for Admins and Users.

Password hashing with bcrypt.

👑 Admin Dashboard
Assign, update, and delete tasks.

Review submitted tasks (accept/reject with feedback).

Monitor user performance via charts.

Perform user CRUD operations.

View task analytics and history.

🙋 User Dashboard
View and manage personal tasks.

Start, submit, and rework on tasks.

Track status and admin feedback.

Edit own profile and password.

📊 Analytics
Visual task and performance analytics using Chart.js.

📁 Attachments
Upload up to 3 PDF documents per task.

View/download attachments from task details.

🧰 Tech Stack
Layer	Tech
Frontend	React, React Router, Bootstrap, Chart.js
Backend	Node.js, Express.js
Database	MongoDB (Mongoose ORM)
Auth	JWT, bcrypt
State Mgmt	React Context API
File Upload	Multer (local storage)
Visualization	Chart.js, MDB React
Testing	Postman collection
DevOps	Docker, Docker Compose, Render for deployment

🔁 Task Workflow
Admin assigns a task to a user.

User sees the task, marks it as In Progress.

User submits task → Admin reviews and either approves or rejects.

Rejected tasks can be reworked and resubmitted by the user.

📸 Screenshots
Add screenshots or a screen recording here (optional for clarity).

🐳 Docker Setup
Ensure Docker is installed.

🧪 Run Locally with Docker:
bash
Copy
Edit
git clone https://github.com/AnuragRawat92/Task-Management-PanScience-Innovations.git
cd Task-Management-PanScience-Innovations
docker-compose up --build
Frontend → http://localhost:3000
Backend → http://localhost:5000

📂 Folder Structure
bash
Copy
Edit
Task-Management-PanScience-Innovations/
├── client/                # React frontend
├── server/                # Node.js/Express backend
├── docker-compose.yml     # Docker config
└── README.md
📬 API & Docs
Postman Collection: Postman Workspace

Full CRUD for Users and Tasks

File upload routes for PDF attachments

Secure role-based APIs

✅ Requirements Covered
 JWT Authentication

 User/Task CRUD

 Admin/Role-based access

 Attachments & File handling

 Performance dashboard

 Docker containerization

 Postman-tested API

 Responsive Bootstrap UI

 MongoDB (Dockerized)

 Live deployment on Render

🧪 Testing
All routes tested via Postman.

Basic manual integration testing.

API documentation included.

Automated tests using Jest/Mocha can be added for future enhancement.

🧠 Design Decisions
Used React Context for state management to keep the setup lightweight.

Chart.js for easy and effective visual analytics.

Multer with local storage for quick file upload prototyping.

Kept the architecture modular for ease of extension.

📌 Future Improvements
Add WebSocket for real-time task updates.

Add automated tests (Jest or Cypress).

Migrate file storage to AWS S3.

Add email notifications for task status updates.

Implement audit logs for admin actions.

👤 Contact
Anurag Rawat
📧 anuragrawat92946@gmail.com
🏫 IET Lucknow

