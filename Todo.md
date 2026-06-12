# price-tracker — Price Tracker

## Project Overview
Automated price monitoring system with web scraper, REST API, and dashboard with price history charts.

## Tech Stack
Python · Express · Next.js · Supabase

---

## Phases & Tasks

### 1️⃣ Setup
- [ ] Create repo named "price-tracker"
- [ ] Create /scraper folder for Python
- [ ] Create /api folder for Express
- [ ] Create /frontend folder for Next.js
- [ ] Install requests, beautifulsoup4, supabase-py in Python
- [ ] Create requirements.txt

### 2️⃣ Python Scraper
- [ ] Write scraper for a real website (e.g., Digikala or Amazon)
- [ ] Extract: product name, price, link, image
- [ ] Save data to Supabase using supabase-py
- [ ] Add timestamp to each record
- [ ] Schedule execution every 6 hours using schedule library
- [ ] Add error handling and logging

### 3️⃣ Express API
- [ ] Build GET /products route to list products
- [ ] Build GET /products/:id/history for price history
- [ ] Build POST /products/track to add new product
- [ ] Connect to same Supabase database

### 4️⃣ Next.js Dashboard
- [ ] Build tracked products list page
- [ ] Build price history chart using recharts
- [ ] Build form to add new product URL
- [ ] Show lowest and highest price
- [ ] Show price change percentage

### 5️⃣ Deployment
- [ ] Deploy scraper on PythonAnywhere
- [ ] Deploy API on Render
- [ ] Deploy dashboard on Vercel
- [ ] Add architecture diagram to README