## Text Summarizer App 🧠

This is a web application that summarizes long text into short, meaningful summaries using **LangChain** and **Groq Llama3** API.  
It uses **Flask** as the backend framework and **HTML templates** for the user interface.


### 🚀 Features
- Takes text input from the user  
- Generates a concise summary using Llama3 model  
- Built with LangChain's modular components  
- Flask-based web interface  
- Secure API key handling via `.env` file  


## 🧩 Tech Stack
- **Python**  
- **Flask**  
- **LangChain**  
- **Groq API (Llama3)**  
- **HTML / CSS (Frontend)**  


## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Text-Summarizer-App.git
   cd Text-Summarizer-App
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the project directory and add your Groq API key:
   ```
   GROQ_API_KEY=your_actual_key_here
   ```

4. Run the app:
   ```bash
   python app.py
   ```

5. Open your browser and go to:
   ```
   http://127.0.0.1:5000
   ```


## 🧠 How It Works
1. User enters a paragraph or long text in the web interface.  
2. Flask sends the input to the LangChain pipeline.  
3. The **Llama3** model (via Groq API) processes and returns a short summary.  
4. The summary is displayed on the same page.



---

**Author:**  Rafay Noor Khan  
🎓 BS Data Science | Interested in NLP & AI Applications
