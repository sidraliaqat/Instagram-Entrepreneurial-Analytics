# Instagram Entrepreneurial Analytics: A Storyliving Study
**Case Study:** @mco_wonders.pk (Small Business Ecosystem)

## 📌 Project Overview
This project is an end-to-end data analytics study of a student-led startup on Instagram. It explores how entrepreneurs use "Storyliving"—sharing lived experiences in real-time—to build community and drive sales.

The project is divided into three technical phases:
1. **Data Pipeline:** Automated scraping and extraction of Reel metrics.
2. **Narrative Analysis:** Manual coding of 20 reels using the Storyliving framework.
3. **Multimodal AI Scaling:** Using AI (Whisper & LLMs) to scale the analysis using video transcripts.

## 🛠️ Technical Stack
- **Languages:** Python (Google Colab)
- **Data Extraction:** Apify Instagram Scraper API
- **AI Models:** OpenAI Whisper (Speech-to-Text), GPT-4/Claude (Semantic Analysis)
- **Libraries:** Pandas, MoviePy, Matplotlib, Seaborn

## 🚀 Key Features

### 1. Automated "Auto-Scroll" Pipeline
Developed a dynamic crawler that simulates profile scrolling to discover the top 20 reels. It automatically performs a nested loop to extract engagement metrics (views/likes) and all associated comments into a single consolidated CSV.

### 2. Multimodal Analysis (Transcription)
To move beyond simple captions, I built a pipeline that:
- Extracts audio from `.mp4` reel files.
- Uses the **Whisper AI model** to generate transcripts.
- Analyzes "Transactional Intent" in Roman Urdu, identifying buying signals that traditional text scrapers miss.

### 3. Human vs. AI Validation
A core part of this research was comparing Human intuition against 5 LLMs (ChatGPT, Claude, Gemini, DeepSeek, Llama3). 
- **Finding:** While AI is efficient, Human analysis was superior in decoding cultural nuances and "Desi" customer sarcasm in Roman Urdu.

## 📈 Key Findings
- **Viral Trigger:** The highest engagement (178k views) occurred during a "Prosocial Challenge" where the entrepreneur performed real-world marketing.
- **Trust Factor:** Transparency regarding setbacks (e.g., "Zero orders today") significantly increased parasocial bonding and audience support.


## 👩‍💻 Author
**Sidra Liaqat**  
*Data Analytics Student - Spring 2026*
