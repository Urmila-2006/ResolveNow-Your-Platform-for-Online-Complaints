ResolveNow – Online Complaint Registration & Management System

ResolveNow is a full-stack web-based complaint registration and management platform designed to simplify the process of submitting, tracking, assigning, and resolving customer complaints in a secure and transparent manner.

The system allows users to register complaints, track real-time status updates, communicate with assigned agents, and receive timely resolutions through a centralized dashboard.

🚀 Features

User registration and secure login

Complaint submission with detailed information

Real-time complaint tracking

Admin-based complaint assignment to agents

Chat communication between user and agent

Status updates and resolution workflow

Secure authentication and data protection

🛠️ Technology Stack

Frontend: React.js, Bootstrap, Material UI
Backend: Node.js, Express.js
Database: MongoDB with Mongoose
Authentication: JWT
Real-time Communication: Socket.io
API Communication: Axios

🏗️ System Architecture

ResolveNow follows a three-tier MERN architecture:

Presentation Layer: React user interface

Application Layer: Express REST APIs

Data Layer: MongoDB database

Key collections include:

Users

Complaints

Assigned Complaints

Messages

📊 Application Flow
User

Register → Login → Submit Complaint → Track Status → Chat with Agent → Receive Resolution → Provide Feedback

Agent

Login → View Assigned Complaints → Communicate with User → Update Status → Resolve Complaint

Admin

Monitor Complaints → Assign to Agents → Manage Users & Agents → Ensure Policy Compliance

🔐 Security

Password hashing using bcrypt

JWT-based authentication

Role-based access control (User, Agent, Admin)

Protected API routes and validation

⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/your-username/resolvenow.git
cd resolvenow
2️⃣ Install Dependencies
cd frontend
npm install

cd ../backend
npm install
3️⃣ Run Application
npm start

The app will run at:

http://localhost:3000
🧪 Testing

The system is tested for:

Authentication and login validation

Complaint submission accuracy

Real-time chat communication

Status update correctness

API response performance

📸 Results

ResolveNow successfully demonstrates:

Secure complaint registration

Efficient admin assignment

Real-time agent interaction

Transparent status tracking

Reliable MongoDB data storage

⚖️ Advantages

Centralized complaint handling

Faster resolution workflow

Real-time communication

Secure MERN architecture

Improved customer satisfaction

⚠️ Limitations

Requires internet connectivity

SMS notification not yet implemented

Basic analytics in current version

🔮 Future Scope

SMS & email automation

AI-based complaint prioritization

Advanced analytics dashboard

Mobile application support

Multi-language interface
