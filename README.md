### AI Cover Letter Architect
**Real-Time Technical Analysis Meets Local LLM Intelligence**
**AI Stock Advisor** is a high-frequency market monitoring tool that bridges the gap between raw financial data and actionable intelligence. It tracks major tech stocks (Apple, Google, Microsoft) and the Dow Jones Index in real-time, calculates complex technical indicators, and leverages a local gemma3:1b model via Ollama to provide professional-grade trading insights every 5 minutes.



-------------------------------------------------------------------------------------------------------------------------------------

### 3. Technology Stack
**- Languages:** Python 3.9+

**- Web Framework:** Streamlit (realtime UI)

**- Data Source:** yfinance (Yahoo Finance API).

**- Data Analysis:** Pandas & Numpy

**- AI Engine:** Ollama 

**- PDF Processing:** PyPDF2.

-------------------------------------------------------------------------------------------------------------------------------------

### 4. Prerequisites and Installation 
**Prerequisites**

**1. Python 3.10+** Installed on your machine

**2. Google Gemini API Key** **Google Gemini API Key:** Obtain one for free at [Google AI Studio](https://aistudio.google.com/).

**Installation Steps**

**1. Clone The Repository**
```bash
git clone https://github.com/carlos-marin1742/AI-cover-letter-generator.git
```

**2. Install Dependencies:**
```bash
pip install -r requirements.txt
```
**3. Configure Environment Variables:** Create ***.env*** file in the root directory
```plaintext
GOOGLE_API_KEY=your_actual_key_here
```

**4. Run the Server:**
```bash
python app.py
```
-------------------------------------------------------------------------------------------------------------------------------------

### 5. Usage & Examples
**1. Input:** Paste a Job Description from job board

**2. Upload:** Select your resume

**3. Generate:** Click "Generate Professional Letter" and watch AI architect your response

**4. Export:** Click the **Copy Text** Button to instantly save the results to your clipboard for use in your application


**Sample App images**

**Inital Screen**
![Initial Screen](./images/initial.png)
**Uploading Resume and pasting Job Description**
![Uploading Resume and Pasting JD](./images/PastingCoverLetter.png)
**Cover Letter Generation**
![Cover Letter Generation](./images/CoverLetter.png)


### 6. Contact and Support 
**- Developer:** Carlos Marin

**- Project Link:** [Github Link](https://github.com/carlos-marin1742/AI-cover-letter-generator/)