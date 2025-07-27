# DataAnalysisApp

**DataAnalysisApp** is a full-stack interactive analytics dashboard built with **FastAPI** (backend) and **Next.js/React.js** (frontend). It provides real-time insights into company performance — including revenue, gross value added (GVA), security incidents, and more — tailored for Wayne Enterprises.

---
https://www.youtube.com/watch?v=cGgtNB0j6MQ

## Features

- Output vs Gross Value Added (GVA) tracking  
- Year-over-Year (YoY) growth visualization for revenue and GVA  
- Division-wise revenue breakdown by quarter  
- Forecasted security incidents  
- Crime prevention vs community engagement analysis  
- Multi-year filtering and interactive charting  

---

## Tech Stack

### Frontend
- Next.js (React.js)  
- Tailwind CSS  
- Chart.js with `chartjs-plugin-datalabels`  

### Backend
- FastAPI (Python)  
- Pandas for data handling  
- Uvicorn server  

---

---

## 🐳 Getting Started with Docker

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/DataBird-Savvy/AnalysisApp.git
cd DataAnalysisApp
```

### 2️⃣ Build Docker Images
```bash
docker-compose build --no-cache
```

### 3️⃣ Run the App
```bash
docker-compose up
```

- Frontend: [http://localhost:3000](http://localhost:3000)
- Backend: [http://localhost:8000](http://localhost:8000)

### 🛑 Stop the App
```bash
docker-compose down
```

---

## ⚡ Getting Started Without Docker

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/DataAnalysisApp.git
cd DataAnalysisApp
```

---

### 2️⃣ Run the Backend (FastAPI)

```bash
# Create a virtual environment (optional)
python -m venv venv

# Activate the virtual environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r backend/requirements.txt

# Run FastAPI server
uvicorn backend.main:app --reload --host 0.0.0.0 --port 8000
```

✅ Backend: [http://localhost:8000](http://localhost:8000)

---

### 3️⃣ Run the Frontend (Next.js)

```bash
# Open a new terminal
cd frontend

# Install Node.js dependencies
npm install

# Start Next.js dev server
npm run dev
```

✅ Frontend: [http://localhost:3000](http://localhost:3000)

---
```
