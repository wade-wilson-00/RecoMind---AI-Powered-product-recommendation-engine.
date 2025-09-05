# 🛒 AI-Powered Product Recommendation System

An **AI-powered recommendation engine** for e-commerce platforms that suggests personalized products to users.  
Built with **MERN stack** for backend/frontend and a **FastAPI microservice** for machine learning recommendations.  

---

## 🚀 Features
- User authentication & authorization (JWT-based)
- Product browsing, cart, and order management
- Hybrid recommendation engine:
  - Collaborative Filtering (purchase history)
  - Content-Based Filtering (product tags & metadata)
  - NLP Embeddings (product descriptions/reviews)
- Personalized product suggestions
- Feedback loop to improve recommendations over time
- Scalable microservices architecture

---

## 🏗️ Tech Stack
### Frontend
- React (Vite + TailwindCSS)

### Backend
- Node.js + Express  
- MongoDB Atlas (database)  
- Redis (caching, optional)  

### Machine Learning Service
- Python + FastAPI  
- Scikit-learn / TensorFlow / Hugging Face Transformers  

---


---

## ⚡ Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/ai-recommendation-system.git
cd ai-recommendation-system
```

---

### 2. Install Dependencies
### Backend
```bash
cd backend
npm install
```
### Frontend
```bash
cd backend
npm install
```
### ML Microservices
```bash
cd ml-service
pip install -r requirements.txt
```

---

### 3. Environment Variables
Create a .env file in /backend
```bash
MONGO_URI=your_mongo_db_connection
JWT_SECRET=your_jwt_secret
REDIS_URL=redis://localhost:6379
ML_SERVICE_URL=http://localhost:8000
```

---

### ▶️ Running the Project
1.Start MongoDB and Redis (if using caching)
2.Run backend:
```bash
cd backend
npm run dev
```
3. Run frontend:
```bash
cd frontend
npm run dev
```
4. Run ML Services
```bash
cd ml-service
uvicorn main:app --reload
```

---

### 📊 Workflow
User → Express Backend → FastAPI ML Service → Database → Recommendations

---

### 📌 License
MIT License
