# GenAI-Application-Using-DeepSeek


🚀 **AI-powered chatbot for energy trading systems**  
A Streamlit-based chatbot using **DeepSeek (via Ollama)** and **LangChain** to assist with.

## 🌟 Features
✅ **Interactive Chat** – Users can communicate with the AI in a Streamlit interface.  
✅ **Customizable Models** – Supports DeepSeek models (`deepseek-r1:7b`).  
✅ **Dark-Themed UI** – Custom-styled sidebar and chat input.  

---

## 📌 Tech Stack

- **Frontend:** Streamlit  
- **AI Model:** DeepSeek via Ollama  
- **Backend Logic:** LangChain  
- **Deployment:** Localhost (or Docker)  

---

## 🛠️ Setup & Installation

### **1️⃣ Clone the Repository**
git clone https://github.com/MehmetAliAkar/GenAI-Application-Using-DeepSeek.git
cd GenAI-Application-Using-DeepSeek

### **2️⃣ Install Dependencies**
pip install -r requirements.txt

### **3️⃣ Start Ollama Server**
ollama pull deepseek-r1:7b

### **4️⃣ Run the Chatbot**
streamlit run app.py
