# 🏥 Swasthya Setu

**Swasthya Setu** (meaning *"Health Bridge"*) is a comprehensive full-stack hospital management platform that connects patients, doctors, and hospitals — built with Django, React, MongoDB, and powered by the Anthropic Claude AI API.

---

## ✨ Features

- 🏨 **Hospital & Doctor Management** — Register and manage hospitals, doctors, and departments
- 👤 **Patient Portal** — Medical records, appointment history, financial ledger, and profile management
- 📅 **Appointment Booking** — Payment-first token generation for seamless scheduling
- 🤖 **Swasthya AI** — Intelligent symptom checker chatbot powered by the Google Gemini API
- 💳 **Payments Module** — Integrated payment tracking across all modules
- 🔐 **User Authentication** — Role-based access for Admin, Doctor, and Patient
- 📊 **Admin Dashboard** — Analytics and management overview

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React.js, Hooks, Axios, CSS3 |
| **Backend** | Django, Django REST Framework, FastAPI |
| **AI** | Google Gemini API |
| **Database** | MongoDB (via Djongo ORM) |
| **Auth** | Django Authentication, Session Management |
| **Tools** | Git, VS Code, Postman, JMeter |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- Node.js 18+
- MongoDB running locally or a MongoDB Atlas URI

### Backend Setup

```bash
# Clone the repo
git clone https://github.com/RajKhaitan3/SwasthyaSetu.git
cd SwasthyaSetu

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure MongoDB URI in settings.py

# Run migrations
python manage.py migrate

# Start Django server
python manage.py runserver
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🤖 Swasthya AI — Symptom Checker

Swasthya AI is the built-in chatbot powered by the **Google Gemini API**. It:

- Asks one question at a time to understand symptoms
- Maintains full conversation sessions via a `ChatSessionManager`
- Provides a warm, medically-calibrated tone

---

## 📁 Project Structure

```
SwasthyaSetu/
├── api/                  # Django apps (patients, doctors, hospitals, payments, users)
├── backend/              # FastAPI server for Swasthya AI streaming
├── frontend/             # React.js frontend
│   └── src/
│       ├── components/   # Reusable UI components
│       └── pages/        # Page-level views
├── manage.py
├── requirements.txt
└── hospitals.json        # Seed data
```

---

## 👨‍💻 Developer

**Raj Khaitan**
- 🔗 [LinkedIn](https://linkedin.com/in/raj-khaitan-622404356)
- 🐙 [GitHub](https://github.com/RajKhaitan3)
- 📧 rajkhaitan3108@gmail.com

---

## 📄 License

This project is licensed under the MIT License.
