# Scrape-Talker-AI

![aiwebscrapereadme-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/44c9ce61-8a28-4dc3-8f90-496f2762a38e)

An intelligent web scraping application that combines modern web scraping techniques with AI to extract and analyze content from any website. The application uses a Streamlit interface for easy interaction and leverages AI to parse and organize scraped data based on natural language prompts.

## 🚀 Features

- Clean and intuitive Streamlit web interface
- Automated web scraping with Selenium
- Intelligent content parsing using Ollama (Local LLM)
- Captcha bypass and IP rotation capabilities via Bright Data
- DOM content cleaning and optimization
- Batch processing for large websites
- Natural language prompt-based data extraction

## 🛠️ Tech Stack

- **Frontend**: 
  - Streamlit - Web interface
  - Python - Core programming language

- **Scraping & Browser Automation**:
  - Selenium - Web automation and scraping
  - BeautifulSoup4 - HTML parsing
  - Bright Data - Web unblocking and proxy services

- **AI & Language Processing**:
  - Ollama - Local LLM integration
  - LangChain - LLM framework
  - Custom prompt engineering

- **Other Tools**:
  - Chrome WebDriver - Browser automation
  - Python venv - Virtual environment management

## 🔧 Installation

1. Create a virtual environment:
```bash
python3 -m venv ai_env
source ai_env/bin/activate  # On Windows: .\ai_env\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Download and install Ollama from [Ollama's website](https://ollama.ai)

4. Pull the required Ollama model:
```bash
ollama pull llama3
```

5. Download appropriate ChromeDriver for your Chrome version

## 🚀 Usage

1. Start the application:
```bash
streamlit run main.py
```

2. Enter the website URL you want to scrape

3. After scraping, enter a natural language prompt describing what information you want to extract

4. View the AI-processed results in a structured format

## 🔑 Key Components

- `main.py` - Streamlit interface and main application logic
- `scrape.py` - Web scraping functionality
- `parse.py` - AI parsing and content processing

## 📝 Notes

- The application requires sufficient RAM to run the Ollama model
- For production use, consider implementing rate limiting and respecting robots.txt
- Some websites may require additional authentication or have terms of service regarding scraping
