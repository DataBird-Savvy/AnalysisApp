# DataAnalysisApp

**DataAnalysisApp** is a full-stack interactive analytics dashboard built with **FastAPI** (backend) and **Next.js/React.js** (frontend). It provides real-time insights into company performance — including revenue, gross value added (GVA), security incidents, and more — tailored for Wayne Enterprises.

---

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

## Getting Started with Docker

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/DataAnalysisApp.git
cd DataAnalysisApp

### Build Docker Images
docker-compose build --no-cache


### Run the App
docker-compose up



Frontend: http://localhost:3000

Backend: http://localhost:8000

### To stop:

docker-compose down