# Gorilla_news

Gorilla News is a fast, modern news aggregator built with the MERN stack and powered by an external News API (e.g., NewsAPI.org, GNews, or NYTimes API). The app delivers real-time news articles with personalized feeds, search, and category filtering.
How to Run:
Clone repo & install dependencies (npm install in /client )

Add News API key in .env (e.g., VITE_NEWS_API_KEY=your_key)

Start dev servers:

Frontend: npm run dev (Vite)

Backend: npm start (Node.js)

GitHub Structure:
/gorilla-news  
├── /client      # React + Vite (Frontend)  
│   └── /src  
│       ├── /components  
│       ├── /hooks (custom API hooks)  
│       └── /pages (Home, Search, Categories)  
