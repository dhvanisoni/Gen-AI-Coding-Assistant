## AI-powered Coding Assistant

Gen-AI-Coding-Assistant is a Streamlit-based web application designed to assist developers with various Python coding tasks, including:

- Debugging assistance
- Code documentation generation
- Solution design
- Code suggestions and optimizations

## Technologies Used

1. **LangChain**: Framework for handling and integrating LLMs in a structured way.
2. **Ollama**: Local execution of LLM models for enhanced privacy and performance.
3. **AI-Model**: deepseek-r1:1.5b
4. **Streamlit**: Simple web interface for displaying outputs and interacting with the user.
5. **Python**: For backend logic and model interaction.

## Installation

### Clone the Repository
```
git clone https://github.com/dhvanisoni/Gen-AI-Coding-Assistant.git
cd Gen-AI-Coding-Assistant
```

### Install Ollama and Pull the deepseek-r1:1.5b model
```
ollama --version
ollama pull deepseek-r1:8b
ollama run deepseek-r1:8b
```

### Install Dependencies
```
pip install -r requirements.txt
```

## Usage 
1.Launch the app using Streamlit:
```
streamlit run app.py
```
2. The app will start running on your local machine and will be accessible in your browser at:
   http://localhost:8501

