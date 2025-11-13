🧠 SirBrams Tech Virtual Campus
Smart Learning. Real Impact.

SirBrams Tech Virtual Campus is a modern e-learning platform designed to provide accessible, inclusive, and affordable education for everyone — including remotely marginalized groups, people with disabilities, and professionals seeking to upskill in technical fields.

The platform is built with a strong focus on real-time collaboration, automation, and scalability, powered by Django, WebSockets, AI Chatbot Integration, and Secure Payment Gateways.

🚀 Key Features
🧩 Learning Management

Create and manage courses with videos, PDFs, links (Zoom, Google Classroom, etc.)

Mentor dashboard for uploading content and monitoring student progress

Student dashboard with course status indicators: Uploaded, Enrolled, Learning (Started/Not Started)

Auto-generated course codes and mentor linkage

💬 Real-Time Chat (WebSocket)

Instant messaging between students, mentors, and admins

Typing indicators, online status, and message history

Built using Django Channels and WebSocket for low-latency communication

🤖 AI-Powered Chatbot

Provides instant assistance to users on course queries, registration, and support

Integrated with OpenAI API for natural conversation and guidance

💳 Secure Payment Integration

Supports MPesa STK Push, PayPal, and other online gateways

Real-time payment confirmation, transaction saving, and auto-generated receipts

🔐 Authentication & Security

Multi-user roles (Admin, Mentor, Student)

Email & Phone verification, OTP verification

Sign in/ signup with google integration

Password strength validation and reset via OTP

Secure data storage using Django ORM and hashed credentials

🧾 Admin Panel

Manage users, courses, and contact messages

Respond to user queries directly within the system

View payment logs and performance analytics

⚙️ Additional Functionalities

Dashboard analytics (enrollment stats, progress tracking)

File upload management (Documents, PDFs, Videos)

Mobile-friendly UI with rounded input elements

Dark/Light theme support

API endpoints for external integrations

🧱 System Architecture
Frontend:  HTML, CSS, Bootstrap, JavaScript (AJAX)
Backend:   Django Framework (Python)
Realtime:  Django Channels (WebSocket)
Database:  PostgreSQL / SQLite (local dev)
Payments:  MPesa Daraja API, PayPal REST API
Chatbot:   Gemini Pro Integration
Hosting:   whitenoise + Gunicorn (Production)


🧑‍💻 Installation & Setup
Prerequisites

Python 3.10+

Django 5+


PostgreSQL / SQLite

Git

Setup Steps
# Clone the repository
git clone https://github.com/yourusername/sirbrams-virtual-campus.git
cd sirbrams-virtual-campus

# Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start WebSocket and server
python manage.py runserver

Environment Variables (.env)
SECRET_KEY=your_secret_key
DEBUG=True
DATABASE_URL=your_database_url
EMAIL_HOST_USER=your_email
EMAIL_HOST_PASSWORD=your_password
MPESA_CONSUMER_KEY=your_mpesa_key
MPESA_CONSUMER_SECRET=your_mpesa_secret
OPENAI_API_KEY=your_openai_key


🧩 Tech Stack
Category	Technologies
Frontend	HTML5, CSS3, Bootstrap 5, JavaScript
Backend	Django, Django Channels, REST Framework
Database	PostgreSQL / SQLite
Payments	MPesa Daraja API
AI / Chatbot	OpenAI GPT
Realtime	WebSocket, Django Channels
Deployment	render
Version Control	Git & GitHub
💡 Future Enhancements

Add course recommendation AI

Integrate video conferencing (WebRTC)

Add certificates generation and grading automation

Launch native mobile app (Flutter / React Native)

👨‍🏫 Project by

Bramuel Wekesa
Founder, SirBrams Tech Solutions
📧 sirbrams.b@gmail.com

🌐 (https://techcampus-r82w.onrender.com/)

Tagline: Smart Solutions. Real Impact.
