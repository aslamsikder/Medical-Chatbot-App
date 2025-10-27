# Medical Chatbot App

## Project Overview

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

### Run the serve
```
python app.py

```

---

## Example Output


## Evaluation Results

---

## ✍️ Author Information
Developed by **Aslam Sikder**, October 2025  
Email: [aslamsikder.edu@gmail.com](mailto:aslamsikder.edu@gmail.com)  
LinkedIn: [Aslam Sikder - Linkedin Account](https://www.linkedin.com/in/aslamsikder)
Kaggle: [Aslam Sikder - Kaggle Account] (https://www.kaggle.com/aslamsikder)
HuggingFace: [Aslam Sikder - Huggingface Account] (https://huggingface.co/aslamsikder)
Google Scholar: [Aslam Sikder - Google Scholar Account](https://scholar.google.com/citations?hl=en&user=Ip1qQi8AAAAJ)