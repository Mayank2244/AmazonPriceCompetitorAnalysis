
# Amazon Price Competitor Analysis using LLM

## 📌 Project Overview
Amazon Price Competitor Analysis using LLM is an AI-powered system designed to **scrape, compare, and analyze product prices** from Amazon and competitor platforms. The project combines **web scraping (Oxylabs)** with **Large Language Models (Gemini API)** to generate intelligent insights, summaries, and business-oriented recommendations.

This project reflects a **real-world e-commerce analytics pipeline**, integrating data collection, processing, and AI-driven interpretation.

---

## 🎯 Objectives
- Scrape product pricing data from Amazon and competitor platforms
- Perform structured price comparison and trend analysis
- Use **Gemini LLM** to generate human-readable insights
- Assist businesses in making data-driven pricing decisions

---

## 🧠 Key Features
- 🌐 Web scraping using **Oxylabs API**
- 📊 Amazon vs competitor price comparison
- 🤖 LLM-powered analysis using **Google Gemini API**
- 📝 Natural language summaries and recommendations
- 📈 Price trend and variance analysis
- ⚙️ Modular and scalable architecture

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **LLM:** Google Gemini API  
- **Web Scraping:** Oxylabs API  
- **Data Processing:** Pandas, NumPy  
- **Visualization:** Matplotlib / Seaborn  
- **Environment:** Jupyter Notebook / Python Scripts  

---

## 📂 Project Structure
AmazonPriceCompetitorAnalysisLLM-main/ │ ├── data/                # Scraped and processed pricing data ├── scrapers/            # Oxylabs-based scraping logic ├── notebooks/           # Data analysis & experimentation ├── src/                 # LLM integration and business logic ├── outputs/             # Generated insights and reports ├── requirements.txt     # Project dependencies └── README.md            # Project documentation

---
---

## 🌐 Data Collection (Oxylabs)
- Product price data is collected using **Oxylabs Web Scraping API**
- Supports:
  - Amazon product listings
  - Competitor e-commerce platforms
- Handles:
  - IP rotation
  - Anti-bot protection
  - Scalable scraping

> ⚠️ Scraping is performed responsibly and for **educational purposes only**.

---

## 🧠 LLM Integration (Gemini API)
- Scraped data is converted into structured prompts
- **Gemini LLM** is used to:
  - Summarize price differences
  - Identify competitive patterns
  - Generate business insights and recommendations
- Prompt engineering is used to ensure:
  - Factual consistency
    
  - Clear analytical outputs

---

## ⚙️ How It Works
1. Scrape product pricing data using Oxylabs
2. Clean and preprocess the collected data
3. Perform statistical price comparison
4. Generate structured prompts from analysis
5. Pass prompts to Gemini API
6. Receive AI-generated insights and summaries

---

## 🚀 How to Run the Project
1. Clone the repository
2. pip install -r requirements.txt
3. export GEMINI_API_KEY=your_api_key
export OXYLABS_API_KEY=your_api_key
python main.py
   ```bash
   git clone https://github.com/your-username/Amazon-Price-Competitor-Analysis-LLM.git
