# ⚡ Data Analyst Agent 2.0 — Your AI-Powered Data Companion  
> Smarter, faster, and more intuitive analysis of your datasets using **Generative AI + Python magic.**  
> Repository: *Insert your GitHub repo link here*  

---

## 📌 What Is This?  
Meet **Shivania Data Analyst Agent 3.0** — an AI-driven assistant that eliminates tedious data crunching.  
Upload your dataset + queries, and instantly get:  
✅ Visual reports  
✅ AI-generated insights  
✅ Automated workflows  

Perfect for:  
- Analysts 🧾  
- Researchers 🔬  
- Startups & Businesses 📈  
- Anyone who loves turning raw data into knowledge  

---

## ✨ Key Highlights  

| Feature                  | Why It’s Awesome 🚀 |
|---------------------------|----------------------|
| 🤖 AI-Powered Insights    | Uses Google’s Generative AI to “understand” your data |
| 📊 Rich Visualizations    | Generates plots with **Seaborn & Matplotlib** |
| 🌍 Web Scraper Mode       | Fetch live data directly from URLs |
| 📂 Multi-Format Friendly  | Accepts CSV, Excel, JSON, Parquet, or TXT |
| 🔄 Ask Many at Once       | Batch processing for multiple questions |
| 🖥️ Simple-to-Use Interface | Beginner friendly, no steep learning curve |
| ⚡ Super-Fast Execution   | Optimized for speed + real-time feedback |

---

## 🚀 Getting Started  

### 1️⃣ Clone the Repo  
```bash
git clone https://github.com/your-username/shivania-data-analyst-agent.git  
cd shivania-data-analyst-agent
```

### 2️⃣ Install Requirements  
```bash
pip install -r requirements.txt
```

### 3️⃣ Configure API Keys  
Create a `.env` file inside the root folder:  
```ini
GEMINI_API_KEY=your_google_api_key  
LLM_TIMEOUT_SECONDS=240  
```

### 4️⃣ Start the Application  
```bash
python -m uvicorn app:app --reload
```

Now open [**http://localhost:8000/**](http://localhost:8000/) in your browser 🌐  

---

## 🧑‍💻 How It Works  

1. **Write Your Questions**  
   Create a `.txt` file with queries like:  
   - What’s the revenue growth month-over-month?  
   - Find correlation between Age and Income  
   - Show most profitable products  

2. **Upload Dataset + Questions File**  
- Dataset (optional) → CSV, Excel, JSON, Parquet, or TXT  
- Questions file (required) → Plain text  

3. **Voilà!**  
- AI processes the queries  
- Generates insights + summaries  
- Builds neat visualizations  

---

## 🛠 Tech Behind the Scenes  

### Backend  
- FastAPI ⚡ → High-performance web server  
- LangChain 🧠 → Orchestrates LLM interactions  
- Google Generative AI ✨ → Core AI engine  
- Pandas + NumPy 📊 → Data wrangling made smooth  
- Seaborn + Matplotlib 🎨 → Clean, insightful charts  

### Frontend  
- HTML5 + CSS + JavaScript  
- Bootstrap-inspired modern UI  

---

## 🔧 API Blueprint  

| Method | Endpoint  | Purpose |
|--------|-----------|----------|
| `GET`  | `/`       | Access web app |
| `POST` | `/api`    | Submit dataset + questions |
| `GET`  | `/summary`| App diagnostics & summaries |

---

## 📂 File Support  

| Format | Extensions |
|--------|------------|
| CSV    | `.csv`     |
| Excel  | `.xlsx`, `.xls` |
| JSON   | `.json`    |
| Parquet| `.parquet` |
| Text   | `.txt`     |

---

## 🎯 Where Can You Use This?  

- 📈 Business Strategy – Sales, KPIs, forecasts  
- 🔬 Research – Data exploration, hypothesis validation  
- 🤖 Data Science – Quick EDA, anomaly detection  
- 📊 Reporting – Automated dashboards  

---

## 🔒 Security First  
- ✅ No cloud storage → All data stays local  
- ✅ API keys kept safe via `.env`  
- ✅ Configurable CORS policy for production use  

---

## 📜 License  

Licensed under **MIT** – free for personal & commercial use.  
