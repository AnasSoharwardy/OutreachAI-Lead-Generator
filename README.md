# 🚀 OutreachAI — AI-Powered Lead Generation Tool

**OutreachAI** is an AI-powered personal lead generation tool that helps agencies, freelancers, and B2B businesses find **verified leads** faster. It leverages **Google Maps data via Serper**, scrapes company websites, and uses **LLaMA 3 (via Groq)** to enrich leads with business insights.

## Features
- **Live Data from Google Maps** – fetch businesses based on niche & location  
- **Website Scraping** – extract company text, emails, and social media links  
- **AI Enrichment (LLaMA 3 via Groq)** – generate:
  - Company description  
  - Unique Selling Points (USPs)  
  - Target audience  
- **One-click CSV Export** – download structured leads instantly
- **Simple Frontend** – built with Streamlit for ease of use


https://github.com/user-attachments/assets/00d2ebaa-c122-4f3b-8dcf-c8d26e17f051


---
## How to Run

### 1. Install Dependencies

Open a CMD in project folder and enter:
```
pip install -r requirements.txt
```

### 2. Add Your API Keys

Edit the `.env` file in the root directory and replace it with your key:

```
SERPER_API_KEY = YOUR_SERPER_API_KEY_HERE
GROQ_API_KEY = YOUR_GROQ_API_KEY_HERE
```
You can get the SERPER API KEY from [here](https://www.serpapi.com)

You can get the GROQ API KEY from [here](https://console.groq.com/keys)


### 3. Run the Tool

Run the provided file to automatically launch the tool
```
RUN ME.bat
```

---

## Tech Stack
- **Backend**: FastAPI  
- **Frontend**: Streamlit  
- **AI Model**: LLaMA 3 (via Groq) 
- **Data Source**: Google Maps (via Serper.dev API)  
- **Web Scraping**: BeautifulSoup + Regex
- **Export**: Pandas → CSV  


