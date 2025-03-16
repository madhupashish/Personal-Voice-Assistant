# **Personal Voice Assistant: Your Intelligent Conversational Companion**  
🎙️🤖 **Transform your digital interactions with your own AI-powered Personal Voice Assistant!**  

This **advanced Personal Voice Assistant** integrates **Text-to-Speech (TTS) and Speech-to-Text (STT)** capabilities, enabling seamless, hands-free communication. It performs various tasks like managing calendars, contacts, emails, and conducting web searches—all through natural voice interactions.  

---

## 🚀 **Key Features**  

✔️ **Speech-to-Text (STT):** Convert spoken language into written text effortlessly.  
✔️ **Text-to-Speech (TTS):** Receive natural-sounding vocal responses.  
✔️ **Vocal Interaction:** Engage in smooth and intelligent conversations.  
✔️ **Smart Tool Integration:** Manage **calendars, contacts, emails, web searches,** and access personal knowledge bases with ease.  

---

## 🛠️ **Available Tools**  

🔹 **CalendarTool:** Schedule events in **Google Calendar** with event details.  
🔹 **AddContactTool:** Save new contacts to **Google Contacts** (Name, Phone, Email).  
🔹 **FetchContactTool:** Retrieve contact details using just a name.  
🔹 **EmailingTool:** Send emails through **Gmail** by specifying recipient, subject, and body.  
🔹 **SearchWebTool:** Perform real-time web searches for up-to-date information.  
🔹 **KnowledgeBaseTool:** Access your **saved notes and documents** from the `/files` folder.  

---

## 📌 **How to Set Up & Run**  

### **🔧 Prerequisites**  
✅ **Python 3.9+**  
✅ **Google API credentials** (for Calendar, Contacts, and Gmail access)  
✅ **Tavily API key** (for web search)  
✅ **Groq API key** (for Llama3)  
✅ **Google Gemini API key** (for using the Gemini model)  
✅ **Deepgram API key** (for voice processing)  
✅ Required **Python libraries** (listed in `requirements.txt`)  

### **📥 Installation & Setup**  

1️⃣ **Clone the repository:**  
   ```bash
   git clone https://github.com/madhupashish/Personal-Voice-Assistant.git
   cd Personal-Voice-Assistant
   ```  
2️⃣ **Create & activate a virtual environment:**  
   ```bash
   python -m venv venv  
   source venv/bin/activate  # Windows: venv\Scripts\activate  
   ```  
3️⃣ **Install dependencies:**  
   ```bash
   pip install -r requirements.txt  
   ```  
4️⃣ **Set up API keys:**  
   - Create a `.env` file and add:  
     ```plaintext
     GOOGLE_API_KEY=your_google_api_key  
     DEEPGRAM_API_KEY=your_deepgram_api_key  
     TAVILY_API_KEY=your_tavily_api_key  
     GEMINI_API_KEY=your_gemini_api_key  
     GROQ_API_KEY=your_groq_api_key  
     ```  
5️⃣ **Configure Google API credentials:**  
   - Follow Google's documentation to set up **Calendar, Contacts, and Gmail APIs.**  
   - Save the credentials file securely and update its path in the configuration.  

### **▶️ Running the Assistant**  
Start a conversation with the assistant using:  
```bash
python main.py
```  
📌 *The assistant will stop when you say **"goodbye."***  

---

## 💡 **Usage Examples**  

🎤 **"Schedule a meeting with John for tomorrow at 2 PM."**  
📞 **"Add a new contact: Jane Doe, phone number 555-1234."**  
📧 **"What's Mary's email address?"**  
📨 **"Send an email to Bob with the subject 'Project Update'."**  
🌐 **"Search the web for recent news about artificial intelligence."**  
📚 **"What was the recipe I saved last week for chocolate chip cookies?"**  

---

## 🤝 **Contributing**  
💡 Contributions are welcome! Feel free to **open an issue or submit a pull request** with improvements.  

## 📩 **Contact**  
📧 For any questions or suggestions, reach out at **madhupashish@gmail.com**  

---

This version is **structured better, visually engaging, and easy to read.** Let me know if you’d like any further refinements! 🚀
