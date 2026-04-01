<div align="center">

<!-- TYPING ANIMATION HEADER -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=00E5A0&center=true&vCenter=true&width=600&lines=📊+CSV+Agent;Chat+with+your+Data;Powered+by+Groq+%2B+LangChain;No+Code.+Just+Questions." alt="Typing SVG" />

<br/>

<!-- BANNER IMAGE — replace with your own screenshot -->
<!-- <img src="assets/banner.png" alt="CSV Agent Banner" width="100%" style="border-radius:12px"/> -->

<br/><br/>

> **An AI-powered web interface that lets you chat with any CSV file in plain English.**
> Upload → Connect → Ask. No code required.

<br/>

<!-- BADGES -->
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

<br/>

![GitHub stars](https://img.shields.io/github/stars/ashishaptel/csv-agent?style=social)
![GitHub forks](https://img.shields.io/github/forks/ashishaptel/csv-agent?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/ashishaptel/csv-agent?color=00e5a0)

</div>

---

## 🤖 What is CSV Agent?

```
 USER  ──► "What is the average credit amount?"
              │
              ▼
       ┌─────────────┐
       │  CSV Agent  │  ◄── Your CSV file is loaded here
       │  Interface  │
       └──────┬──────┘
              │
              ▼
       ┌─────────────┐
       │  Groq API   │  ◄── llama-3.3-70b-versatile
       │  LangChain  │
       └──────┬──────┘
              │
              ▼
 AGENT  ──► "The average credit amount is ₹3,271.26"
```

CSV Agent is a **browser-based AI assistant** that reads your CSV data and answers questions about it using the power of **LLaMA 3.3 70B via Groq**. No Python environment needed on the frontend — everything runs in your browser.

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 📂 **Drag & Drop Upload** | Upload any CSV instantly — no file size limits |
| 🔑 **Groq API Integration** | Direct connection to Groq's blazing-fast LLM API |
| 🧠 **Multi-turn Memory** | Ask follow-up questions — the agent remembers context |
| 👁️ **Live CSV Preview** | See your data before you start chatting |
| ⚡ **Quick Prompts** | One-click starter questions for fast analysis |
| 🎨 **Dark UI** | Sleek terminal-inspired design |
| 📦 **Zero Backend** | Pure HTML + CSS + JS — open in any browser |

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology | Purpose |
|-------|-----------|---------|
| 🎨 Frontend | HTML5, CSS3, Vanilla JS | UI & interaction |
| 🤖 LLM | Groq API (LLaMA 3.3 70B) | Natural language understanding |
| 🔗 Agent Framework | LangChain + langchain-experimental | CSV agent logic (notebook) |
| 📊 Data | Pandas | CSV parsing & analysis (notebook) |
| 📋 Formatting | Tabulate | Table display in terminal |
| 🔐 Env | python-dotenv | API key management |

</div>

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ashishaptel/csv-agent.git
cd csv-agent
```

### 2. Install Python dependencies (for the notebook backend)

```bash
pip install -r requirements.txt
```

### 3. Run the frontend

Simply open `index.html` in your browser:

```bash
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html
```

### 4. Use the app

```
1. 🔑  Paste your Groq API key  →  https://console.groq.com
2. 📂  Upload your CSV file
3. 🔌  Click "Connect Agent"
4. 💬  Start chatting with your data!
```

---

## 📁 Project Structure

```
📦 csv-agent/
├── 📄 index.html          # Main UI — open this in your browser
├── 🎨 style.css           # All styling & animations
├── 📓 CSV_Agent.ipynb     # Original LangChain notebook backend
├── 📋 requirements.txt    # Python dependencies
└── 📖 README.md           # You are here
```

> 💡 **Tip:** Add a `assets/` folder and drop your screenshots there to replace the banner placeholder above.

---

## 📸 Screenshots

> _Add your screenshots here by placing images in an `assets/` folder_

```
<!-- Uncomment and update paths after adding your screenshots -->

<!-- <img src="assets/screenshot-home.png" width="49%"/> -->
<!-- <img src="assets/screenshot-chat.png" width="49%"/> -->
```

To add a screenshot:
1. Take a screenshot of your running app
2. Create a folder called `assets/` in your project
3. Save the image as `assets/banner.png`
4. Uncomment the `<img>` tag at the top of this README

---

## 🔑 Get Your Groq API Key

1. Go to **[console.groq.com](https://console.groq.com)**
2. Sign up for a free account
3. Navigate to **API Keys** → **Create API Key**
4. Copy and paste it into the app's sidebar

> Groq offers a **free tier** with generous rate limits — perfect for this project.

---

## 🧪 Example Questions to Ask

```
💬 "Show me the first 5 rows"
💬 "What is the average credit amount?"
💬 "How many male vs female applicants are there?"
💬 "Which purpose has the highest loan amount?"
💬 "Are there any missing values in this dataset?"
💬 "What is the distribution of job types?"
```

---

## 📦 Requirements

```txt
langchain>=1.2.14
langchain-experimental>=0.4.1
langchain-groq>=1.1.2
langchain-community>=0.4.1
pandas>=3.0.2
tabulate>=0.10.0
python-dotenv>=1.1.0
requests>=2.32.5
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Report bugs via [Issues](https://github.com/ashishaptel/csv-agent/issues)
- 💡 Suggest features
- 🔀 Submit a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.

---

<div align="center">

## 👨‍💻 Developer

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=2000&pause=1000&color=00E5A0&center=true&vCenter=true&width=400&lines=Built+with+❤️+by+Ashish+Aptel;AI+%7C+Data+Science+%7C+Web+Dev" alt="Developer" />

**Ashish Aptel**

[![GitHub](https://img.shields.io/badge/GitHub-ashishaptel-181717?style=for-the-badge&logo=github)](https://github.com/ashishaptel)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ashish_Aptel-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/ashishaptel)

<br/>

*If you found this project helpful, please consider giving it a ⭐ — it means a lot!*

<br/>

![Wave](https://capsule-render.vercel.app/api?type=waving&color=00E5A0&height=100&section=footer)

</div>
