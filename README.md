# Unit Conversion Chatbot with LangChain and Gemini

An AI-powered chatbot that performs intelligent unit conversions using **LangChain** and **Google Gemini 2.0 Flash**.  
The chatbot leverages conversational memory, agent-based workflows, and external tools to provide accurate and context-aware conversions.

---

## 🚀 Features
- **Multi-tool support**: Handles conversions for temperature, distance, and weight.  
- **Conversational memory**: Remembers past conversions during the session for a natural flow.  
- **Agent-based workflow**: Chatbot decides when to use tools or provide direct responses.  
- **Tool logging**: Tracks tool usage for transparency.  
- **Google Colab ready**: Fully runnable in Colab for easy testing and experimentation.

---

## 🛠️ Tech Stack
- **LangChain** → for agent orchestration and memory  
- **Google Gemini 2.0 Flash** → as the Large Language Model  
- **Python** → for implementation  
- **Google Colab** → for testing and demonstration  

---

## 📂 Project Structure
├── chatbot.ipynb # Main Colab notebook with implementation
├── requirements.txt # List of dependencies


---

## ⚡ How It Works
1. Define tools for unit conversions (temperature, distance, weight).  
2. Integrate tools into a LangChain agent.  
3. Add conversational memory to store previous conversions.  
4. Use Gemini 2.0 Flash as the LLM to interpret queries and delegate tasks.  
5. Run asynchronously in Python for smooth query handling.  

---

## ▶️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/unit-conversion-chatbot.git
cd unit-conversion-chatbot

├── README.md # Project documentation
