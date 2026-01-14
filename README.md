# 🕷️ WebScraper

A simple full-stack **web scraping application** built using **Node.js, Express, Puppeteer**.  
It can scrape data from **any JavaScript-rendered website** and display it in a clean frontend UI.

---

## 🚀 Features

- Scrapes JavaScript-rendered (SPA / React / Vue) websites using Puppeteer  
- Backend API built with Express.js  
- Frontend fetches scraped data and displays it  
- Works for any website by changing URL and selectors   
- CORS enabled for frontend-backend communication  

---

## 📁 Project Structure

```
webscraper/
│
├── index.js        # Backend scraper API
├── package.json
│
├── index.html      # Frontend UI
├── app.js          # Frontend fetch logic
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/tanmoyPaul12/webscraper.git
cd webscraper
```

Install dependencies:

```bash
npm install
```

---

## ▶️ Run Backend

```bash
node index.js
```

Backend runs at:

```
http://localhost:8000/results
```

---

## 🌐 Run Frontend

Open `index.html` using **Live Server** or any local server:

```
http://127.0.0.1:5500/index.html
```

The frontend fetches data from the backend and displays it.

---

## 📊 What It Scrapes

This scraper can extract data from **any JavaScript-rendered website**, not just this portfolio.

In this project, my own portfolio website was used **only for testing and demonstration purposes**, but the scraper can be easily adapted to scrape:

- Blogs  
- News sites  
- Product pages  
- Profile pages  
- Any SPA / React / Vue / JS-rendered site  

By changing the target URL and selectors, you can scrape different websites without changing the core logic.

---

## 🧠 Why Puppeteer?

The target websites are JavaScript-rendered, so libraries like Cheerio cannot scrape them correctly.  
Puppeteer loads the page like a real browser and extracts data after rendering.

---

## 🔐 Legal Notice

This project is for **educational purposes only**.  
Always check website terms and robots.txt before scraping.

---

## 📌 Future Improvements

- Add multi-page crawling  
- Save scraped data to JSON or database  
- Add refresh button  
- Add loading animation  
- Add export feature  

---


