# 🧠 DecisionIQ


![DecisionIQ](https://github.com/zahidans/DecisionIQ/blob/main/pic1.jpeg)

### **Think Less. Decide Better.**

## Why DecisionIQ?
Most AI tools simply give you an answer.
DecisionIQ goes one step further — it helps you understand the decision.
It analyzes your situation, compares available options, evaluates important factors, identifies trade-offs, and provides an intelligent recommendation.

##  About the Project

**DecisionIQ** is an AI-powered decision intelligence platform designed to help users evaluate different options, understand trade-offs, and make informed decisions.

The platform combines a modern web interface with an intelligent backend to transform user problems into structured decision analysis.

##  Features

*  AI-powered decision analysis
*  Structured comparison of multiple options
*  Pros and cons analysis
*  Intelligent recommendations
*  Decision scoring and insights
*  User authentication
*  Modern responsive web interface
*  Backend API integration

##  Tech Stack

### Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS

### Backend

* Python
* FastAPI
* SQLAlchemy
* Alembic

### Database

* PostgreSQL

### AI

* OpenAI API

## 📁 Project Structure

```text
decisioniq/
│
├── frontend/          # Next.js frontend
│
├── backend/           # FastAPI backend
│
├── .github/
│   └── workflows/     # CI/CD configuration
│
├── .gitignore
└── README.md
```

##  Getting Started


### 2. Backend Setup

```bash
cd backend
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create your environment file:

```text
.env
```

Use `.env.example` as a reference and add your own API/database credentials.

Run the backend:

```bash
uvicorn app.main:app --reload
```

### 3. Frontend Setup

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

The frontend will normally be available at:

```text
http://localhost:3000
```

##  Environment Variables

Never commit your `.env` files or API keys to GitHub.

Create your own `.env` file locally using the provided `.env.example` files.

## 🗺️ Future Improvements

* Advanced decision analytics
* More AI decision models
* Decision history and insights
* Improved visualization
* Personalized recommendations
* Production deployment

## 📄 License

