# ⚽ PlayerIQ

PlayerIQ is an AI-powered football analytics platform that helps users explore player statistics, compare performances, analyze matches, and generate intelligent football insights using Machine Learning.

The project combines a modern React frontend, an Express backend, and a FastAPI-based AI service to deliver real-time football intelligence and analytics.

---

## 🚀 Features

### 📊 Player Analytics
- View detailed player profiles
- Explore performance statistics
- AI-generated player ratings
- Player playstyle analysis

### ⚔️ Player Comparison
- Head-to-head player comparison
- Statistical performance breakdown
- Comparative analytics dashboard

### ⚽ Match Analysis
- Match insights and reports
- Historical match data exploration
- AI-assisted match evaluation

### 🤖 Machine Learning Integration
- Random Forest-based player rating prediction
- Performance trend analysis
- Feature-engineered football metrics
- Data-driven insights generation

---

# 🏗️ System Architecture

```text
PlayerIQ
│
├── Frontend (React + Vite)
│       ↓
├── Backend API (Express.js)
│       ↓
├── AI Service (FastAPI)
│       ↓
└── Machine Learning Models
```

---

# 🛠️ Tech Stack

## Frontend
- React
- Vite
- JavaScript
- Axios
- Socket.IO Client

## Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Socket.IO

## AI Service
- FastAPI
- Python
- Pandas
- NumPy
- Scikit-Learn

## Machine Learning
- Random Forest Regressor
- Feature Engineering
- Data Preprocessing
- Model Evaluation

---

# 📂 Project Structure

```text
PlayerIQ/

├── frontend/           React + Vite Dashboard
├── backend/            Express API and Authentication
├── ai-service/         FastAPI Analytics Service
├── data/               Football datasets and generated reports
├── docs/               Documentation files
├── scripts/            Utility scripts

├── README.md
└── PRD.md
```

---

# 🎯 Product Modules

## Home
- Featured matches
- Recent results
- Spotlight players
- Analytics overview

## Players
- Complete player directory
- Individual player profiles
- AI-generated ratings

## Compare
- Compare player statistics
- Analyze strengths and weaknesses
- Performance benchmarking

## Matches
- Match directory
- Completed match analysis
- AI-generated match insights

---

# 🤖 Machine Learning Workflow

The Machine Learning pipeline follows the architecture below:

```text
Football Dataset
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Model Training
(Random Forest)
        ↓
Performance Prediction
        ↓
Player Ratings
        ↓
FastAPI Service
        ↓
React Dashboard
```

### ML Features

- Player rating prediction
- Performance evaluation
- Statistical trend analysis
- Football intelligence reports

### Libraries Used

```python
Scikit-Learn
Pandas
NumPy
```

---

# 📥 Installation

## Clone Repository

```bash
git clone https://github.com/Madhur-K4/PLAYER-IQ.git

cd PLAYER-IQ
```

---

# 📋 Prerequisites

Install the following before running the project:

- Node.js
- npm
- Python 3.10+
- MongoDB Community Server or MongoDB Atlas
- Git

---

# ⚙️ Backend Setup

```bash
cd backend

npm install
```

Create `.env`

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

AI_SERVICE_URL=http://127.0.0.1:8000

CLIENT_ORIGIN=http://localhost:5173
```

Run Backend

```bash
npm run dev
```

Backend URL:

```text
http://localhost:5000
```

---

# 🤖 AI Service Setup

```bash
cd ai-service

python -m venv .venv
```

### Activate Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Mac/Linux

```bash
source .venv/bin/activate
```

Install Dependencies

```bash
pip install -r requirements.txt
```

Run AI Service

```bash
uvicorn app.main:app --reload --host 127.0.0.1 --port 8000
```

AI Service URL

```text
http://localhost:8000
```

Health Check

```text
http://localhost:8000/health
```

---

# 🎨 Frontend Setup

```bash
cd frontend

npm install
```

Create `.env`

```env
VITE_API_BASE_URL=http://localhost:5000/api

VITE_SOCKET_URL=http://localhost:5000
```

Run Frontend

```bash
npm run dev
```

Frontend URL

```text
http://localhost:5173
```

---

# ▶️ Running The Complete Project

Open three terminals.

### Terminal 1

```bash
cd ai-service

uvicorn app.main:app --reload
```

### Terminal 2

```bash
cd backend

npm run dev
```

### Terminal 3

```bash
cd frontend

npm run dev
```

Open:

```text
http://localhost:5173
```

---

# 🔍 Verification

### Frontend Build

```bash
cd frontend

npm run build
```

### Backend Tests

```bash
cd backend

npm test
```

### AI Service Tests

```bash
cd ai-service

python -m unittest discover -s tests
```

---

# 📸 Screenshots

Add your application screenshots here.

```markdown
![Dashboard](screenshots/dashboard.png)

![Player Profile](screenshots/player-profile.png)

![Comparison](screenshots/comparison.png)
```

---

# 🚀 Future Enhancements

- Live football data integration
- Advanced scouting reports
- Transfer recommendation system
- Team performance analytics
- Deep Learning player forecasting
- Real-time match intelligence

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push changes
5. Create a Pull Request

---

# 👨‍💻 Author

### Madhur Kalra

B.Tech Student | Software Developer | Open Source Contributor




---

# ⭐ Support

If you found this project useful, consider giving it a star on GitHub.
