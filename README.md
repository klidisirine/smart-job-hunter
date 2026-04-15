# smart-job-hunter
# 🎯 Smart Job Hunter Pro
🚀 Live Demo: https://smart-job-hunter-komudds4e3jvazmicprudh.streamlit.app/

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://smart-job-hunter.streamlit.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)

> An intelligent job/internship search application that analyzes your CV and finds matching opportunities using AI.

##  Features

| Feature | Description |
|---------|-------------|
|  **CV Analysis** | Upload PDF CV → AI extracts skills, education, domain |
| **Smart Search** | Real-time job search from RemoteOK API |
|  **Match Score** | 0-100% compatibility score with personalized advice |
| **Email Generator** | Professional cover letter ready to copy-paste |
|  **Excel Export** | Download all results with emails in one click |
|  **Modern UI** | Clean, responsive, professional interface |

##  Tech Stack

| Technology | Purpose |
|------------|---------|
| Python 3.11+ | Core language |
| Streamlit | Web interface |
| Groq (Llama 3.3) | AI analysis |
| PyPDF2 | PDF parsing |
| BeautifulSoup4 | HTML cleaning |
| OpenPyXL | Excel export |
| Requests | API calls |

##  Prerequisites

- Python 3.11 or higher
- Groq API key (free at [console.groq.com](https://console.groq.com))

##  Installation

```bash
# 1. Clone the repository
git clone https://github.com/klidisirine/smart-job-hunter.git
cd smart-job-hunter

# 2. Create virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the application
streamlit run smart_job_hunter_site.py
