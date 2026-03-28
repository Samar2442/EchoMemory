🌟 EchoMemory

EchoMemory is a full-stack memory management application that allows users to store, organize, and revisit their personal memories. It includes a web platform (PHP + MySQL) and a mobile client for seamless access anytime, anywhere.

🚀 Features
🌐 Web Application
🔐 User Authentication (Login / Register)
📝 Add, Edit, Delete Memories
📂 Categorize Memories
📅 Timestamp for each entry
🔍 Search & Filter functionality
📊 Dashboard overview
📱 Mobile Client
📲 Cross-platform mobile access (Android / iOS)
🔄 Sync with web database via API
📝 Create & manage memories on the go
🔔 Push notifications (optional)
📷 Upload images with memories
🌙 Dark mode support
🛠️ Tech Stack
Web
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL
Mobile
Framework: (Choose one → React Native / Flutter / Android Java/Kotlin)
API Communication: REST API (PHP-based)
Storage: Local cache + remote MySQL database
📁 Project Structure
EchoMemory/
│
├── backend/              # PHP backend (API + logic)
│   ├── config/           # DB config
│   ├── api/              # REST API endpoints
│   └── models/           # Database models
│
├── web/                  # Web frontend
│   ├── assets/
│   ├── pages/
│   └── index.php
│
├── mobile/               # Mobile client app
│   ├── src/
│   ├── components/
│   └── screens/
│
└── database.sql
⚙️ Installation
🔧 Backend (PHP + MySQL)

Clone repository:

git clone https://github.com/your-username/EchoMemory.git

Move to server directory:

C:\xampp\htdocs\EchoMemory
Start Apache & MySQL
Create database:
Name: echomemory
Import database.sql

Configure DB in:

backend/config/db.php
🌐 Web App

Open in browser:

http://localhost/EchoMemory/web
📱 Mobile App

Navigate to mobile folder:

cd mobile

Install dependencies:

npm install

Update API URL:

const API_URL = "http://YOUR_LOCAL_IP/EchoMemory/backend/api";

Run app:

npm start
🔗 API Endpoints (Example)
Method	Endpoint	Description
POST	/login	User login
POST	/register	User registration
GET	/memories	Fetch memories
POST	/memories	Add memory
PUT	/memories/{id}	Update memory
DELETE	/memories/{id}	Delete memory
🔐 Security Notes
Use password_hash() for passwords
Use prepared statements (PDO / MySQLi)
Token-based authentication (JWT recommended)
Secure API endpoints
📸 Screenshots

(Add Web + Mobile screenshots here)

📈 Future Enhancements
🧠 AI-based memory tagging
☁️ Cloud backup (Google Drive / AWS)
🎤 Voice-to-text memory input
📍 Location-based memories
👥 Social sharing features
