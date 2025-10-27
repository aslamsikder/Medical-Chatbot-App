# Medical Chatbot App

## Project Overview
The Medical Chatbot App is an AI-powered conversational assistant designed to provide reliable medical information, symptom guidance, and healthcare support. Built using LangChain, Flask, and LLM-based reasoning, it integrates retrieval-augmented generation (RAG) and domain-specific knowledge bases to deliver accurate, context-aware responses. The system enables users to interact naturally through text, receive preliminary medical insights, and vector-based retrieval. This application demonstrates the power of AI in healthcare, promoting accessibility, efficiency, and safe patient engagement through intelligent automation.
---
## Project Structure
The project is organized into a modular structure to separate concerns, making it clean, maintainable, and easy to navigate.
```
Medical Chatbot App/
├── .env                            # All API Key is stored here
├── data/
│   └─
├── research/
│   └─ experiment.ipynb             # First I explored the full project here before writing moduler structure code
├── src/                            # Start Modular Coding
│   ├─ __init__.pt.py
│   ├─ helper.py                                               
│   └─ prompt.py                               
└── LICENSE
└── README.md                       # Comprehensive project documentation
└── requirements.txt                # Lists all Python dependencies
└── setup.py
└── template.py                     # python script for creating our project folder structure
```

---

## Tech Stack

- python
- langchain
- pinecone
- flask
- openAI
- pypdf
- python-dotenv
- CI/CD Deployment (Github Action)

---

## ⚙️ How to Run

### 1. Create Environment
```bash
conda create -n MedChatbot python=3.11 -y
conda activate MedChatbot # To activate
conda deactivate # To deactivate
```

### 2. Install Requirements
```bash
pip install -r requirements.txt
```

### 3. Set API Key (Keep your all API in .env file) - best approach
Create a `.env` file in the project root:
```
HF_TOKEN = "your_HF_TOKEN_here"
OPENAI_API_KEY = "Your API Key here"
```

### Run the following command
```
python app.py

```
Then go to your browser and write
```
localhost:8080 # then press enter
```
---

## Example Output
User: What I do for acidity problem?
Answer: For managing acidity, consider using over-the-counter antacids which can neutralize stomach acid and provide relief. Products containing simethicone, like Gas-X or Mylanta Gas Relief, may also address symptoms related to gas, if that's part of your discomfort. However, if symptoms persist, consult a healthcare professional for further advice and a suitable long-term treatment plan.

---

## ✍️ Author Information
Developed by **Aslam Sikder**, October 2025    
Email: [aslamsikder.edu@gmail.com](mailto:aslamsikder.edu@gmail.com)    
LinkedIn: [Aslam Sikder - Linkedin Account](https://www.linkedin.com/in/aslamsikder)    
Kaggle: [Aslam Sikder - Kaggle Account](https://www.kaggle.com/aslamsikder)    
HuggingFace: [Aslam Sikder - Huggingface Account](https://huggingface.co/aslamsikder)    
Google Scholar: [Aslam Sikder - Google Scholar Account](https://scholar.google.com/citations?hl=en&user=Ip1qQi8AAAAJ)    
