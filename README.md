# Personal Assistant using LangChain

![Personal Assistant](https://img.shields.io/badge/AI-Powered%20Assistant-blue.svg)  
An AI-based personal assistant built using **LangChain** to enhance productivity and streamline tasks. This assistant provides various features like drafting emails, creating study plans, extracting action points, answering knowledge-based queries and querying Agent for any questions. It also offers an interactive agent interface for quick responses. The front-end is powered by **Streamlit**, making the user experience intuitive and smooth.

---

## 📋 Features

- **Draft Emails:** Generate polished and professional emails effortlessly.
- **Study Plan Creation:** Create personalized study plans based on your goals and schedule.
- **Extract Action Points:** Automatically identify actionable items from text inputs (e.g., meeting notes).
- **Knowledge-Based Q&A:** Answer questions using internal or provided knowledge bases.
- **Interactive Query Agent:** Submit quick queries through a responsive input agent.

---

## 🛠 Tech Stack

- **LangChain:** Core framework to manage and build language models.
- **Streamlit:** Front-end framework for interactive user interface.
- **Python:** Backend development.
- **OpenAI API / LLMs:** (Optional) If using advanced language models like GPT for better responses.

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher  
- `pip` (Python package installer)  
- API keys (if using external LLM services like OpenAI)  

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/personal-assistant.git
   cd personal-assistant

2. **Install Dependencies::**
    ```bash
    pip install -r requirements.txt

3. **Add your API Keys (in the .env file):**
    ```makefile
    OPENAI_API_KEY=your_openai_api_key

4. **Run the Application:**
    ```bash
    streamlit run personal_assistant.py

5. **Access the App:**
    - Open your browser and go to:
    [text](http://localhost:8501)

### 📦 Dependencies

Install all dependencies using the requirements.txt. Below are some core libraries used:

- langchain
- streamlit
- openai
- dotenv (for managing environment variables) 

### 📝 Usage

1. Draft Emails:
    Input the context or topic for the email, and the assistant will generate a well-formatted draft.

2. Create Study Plans:
    Provide subjects and time constraints, and the assistant will suggest a study plan.

3. Extract Action Points:
    Paste meeting notes or any document, and the assistant will extract actionable tasks.

4. Interactive Query Agent:
    Ask questions or provide a task request directly in the query box, and get an immediate response.

### 🤖 How it Works
1. LangChain Framework:
    Manages workflows, conversation memory, and prompts for interacting with the LLMs.

2. Streamlit Frontend:
    Provides a real-time web interface for user interaction.

3. APIs and Models:
    Uses language models like OpenAI's GPT to generate responses, if configured.


This README provides a complete overview, including installation instructions, project structure, and usage details, ensuring it's easy to get started with the project.