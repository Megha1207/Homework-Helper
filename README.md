**Homework Helper**

Homework Helper is a Streamlit app that leverages multiple AI agents to assist students with homework questions. The app intelligently clarifies questions, generates detailed solutions, reviews them for quality, and provides concise answers, making homework faster and smarter.

**Features**

*Clarification Agent*: Ensures questions are well-defined and requests additional details if needed.
*Solution Agent*: Generates a comprehensive solution to the given question.
*Quality Assurance Agent*: Reviews the solution for accuracy, coherence, and correctness.
*Concise Answer Agent*: Summarizes the solution into a clear, easy-to-read answer for quick understanding.
*Interactive Streamlit Interface*: User-friendly web interface for seamless interaction with AI agents.

**Installation**

1. Clone the repository:
git clone https://github.com/Megha1207/Homework-Helper.git
cd Homework-Helper

2. Create a virtual environment (optional but recommended):
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

3.Install dependencies:
pip install -r requirements.txt

4.Set up environment variables:
Create a .env file in the project root and add your OpenAI API key:
OPENAI_API_KEY=your_openai_api_key
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/f0f8e808-6b2b-4592-b7e5-1ad4d44d53c8" />


**Technologies**

Streamlit – Web app interface
OpenAI GPT-4 – AI agent backend
Python – Core programming language
NLTK / spaCy – NLP processing
Docker (optional) – Containerization for deployment
