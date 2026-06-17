
# 🚀 Finance AI Agent  

A **multi-agent AI system** that provides real-time **stock market insights, financial news, and analysis**. Built using **Phi-Agents, Groq's Llama-3.3-70B, YFinance, and DuckDuckGo**, this project leverages **agentic AI** to autonomously fetch, analyze, and present financial data in a structured format.  

## 📌 Features  
✅ **Web Search Agent** – Fetches the latest financial news using DuckDuckGo with source links.  
✅ **Finance AI Agent** – Retrieves stock prices, analyst recommendations, and financial reports from YFinance.  
✅ **Multi-Agent Collaboration** – Agents work together for enriched financial insights.  
✅ **Interactive UI** – Uses **Phi Playground** for a seamless user experience.  

## 🛠️ Tech Stack  
- **[Phi-Agents](https://github.com/phidata-dev/phi)** – Multi-agent AI framework  
- **[Groq Llama-3.3-70B](https://groq.com/)** – Large language model  
- **[YFinance](https://pypi.org/project/yfinance/)** – Financial data extraction  
- **[DuckDuckGo API](https://duckduckgo.com/)** – Web search integration  
- **Playground UI** – Interactive AI interface  

## 📂 Project Structure  

📦 Finantical_Analysis_Chatbot  
 ┣ 📜 .env                 # Your API keys — create from .env.example, never commit  
 ┣ 📜 .env.example         # Template for required environment variables  
 ┣ 📜 finantial_agent.py   # CLI multi-agent run (prints a sample response in the terminal)  
 ┣ 📜 playground.py        # Launches the Phi Playground web UI  
 ┣ 📜 requirment.txt       # Required dependencies  
 ┗ 📜 README.md            # Project documentation  


## 🚀 Installation & Usage  

### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/Mehtab-kabir/Finantical_Analysis_Chatbot.git
cd Finantical_Analysis_Chatbot
```

### 2️⃣ **Set Up Environment Variables**  
Copy the template and fill in your keys (never commit `.env`):  
```bash
cp .env.example .env
```
```ini
GROQ_API_KEY=your-groq-api-key       # https://console.groq.com/keys
PHI_API_KEY=your-phidata-api-key     # required for the Playground UI
OPENAI_API_KEY=your-openai-api-key   # optional, used by finantial_agent.py
```

### 3️⃣ **Install Dependencies**  
```bash
pip install -r requirment.txt
```

### 4️⃣ **Run the Application**  

Run the CLI agent (prints a sample analysis to the terminal):
```bash
python finantial_agent.py
```

Or launch the interactive Phi Playground web UI:
```bash
python playground.py
```
The Playground UI will be available at `http://localhost:8000`.

## 🖥️ Example Usage  
- **Get real-time stock prices**  
- **Fetch analyst recommendations**  
- **Search for financial news**  
- **Receive structured financial reports**  

## 🛠️ Contributing  
Feel free to **fork this repository** and submit **pull requests**! If you encounter issues, open a GitHub **issue**.  

## 📜 License  
This project is licensed under the **MIT License**.  

## 🌟 Acknowledgments  
Special thanks to **Phi-Agents, Groq, YFinance, and DuckDuckGo** for providing the essential tools to make this project possible!  

---

🔥 **Let's revolutionize financial AI with multi-agent intelligence!** 🚀  
