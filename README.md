# RouteX-Travel-Recommender-System

### 📍 RouteX Escapade

A travel recommendation system that uses K-Nearest Neighbors (KNN) + LLM-based AI reasoning (Groq API) to suggest personalized travel destinations with real-world budget estimates.

#### 🚀 Features
User authentication (localStorage-based)
KNN-based travel recommendation engine
AI-powered travel reasoning using Groq LLM
Realistic trip budget estimation (INR)
Personalized ranking of destinations
Image gallery for each destination
Dark mode support
User search history tracking
Smart prefetching for faster recommendations

### 🏗️ Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
AI Model: Groq (LLaMA 3.1 8B Instant)
ML Algorithm: K-Nearest Neighbors (K=5, Euclidean Distance)
Storage: LocalStorage (browser-based)

#### 🧠 How It Works
User enters travel preferences (budget, weather, days, etc.)
KNN algorithm compares input with dataset destinations
Top matching destinations are selected
AI backend:
1. Calculates real-world travel cost
2. Generates reasoning & insights
3. Produces personalized summary
Final recommendation is displayed with score + explanation

#### Prerequisites

###### Set environment variables
Create a .env file:
GROQ_API_KEY=your_api_key_here

