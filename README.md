
# WebSage AI

WebSage AI is an intelligent chatbot built using **Grok API** with **Tool Calling** support.  
It uses the **Tavily API** for web search, allowing the chatbot to fetch real-time information when required.

👉 This project is part of my **Generative AI (GenAI) learning journey** where I explored how to build AI-powered apps with tool calling.

## 🚀 Features
- Full-stack chatbot (Frontend + Backend)
- Grok API integration
- Tool calling with Tavily Web Search
- Real-time responses
- Modern frontend with React + Vite
- Backend built with Node.js + Express

## 📂 Project Structure
```
WebSageAI/
│── backend/        # Node.js + Express API server
│── frontend/       # React + Vite frontend
│── README.md       # Project documentation
```

## 🛠️ Tech Stack
- **Frontend**: React, Vite, TailwindCSS
- **Backend**: Node.js, Express
- **AI**: Grok API
- **Tool Calling**: Tavily Web Search API

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/ANKITKUMARBARIK/WebSage_AI.git
cd WebSageAI
```

### 2. Setup Backend
```bash
cd backend
npm install
# Add your API keys in .env file
# GROK_API_KEY=your_grok_api_key
# TAVILY_API_KEY=your_tavily_api_key

npm start
```

### 3. Setup Frontend
```bash
cd frontend
npm install
npm run dev
```

## 📌 How It Works
1. User enters a query in the frontend UI.
2. Request is sent to the backend and processed by Grok API.
3. If Grok triggers a **tool call**, Tavily API is called.
4. Results are combined and sent back to the frontend as chatbot response.

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📜 License
MIT License
