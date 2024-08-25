# Ellza - Mental Health Care Bot

This repository contains the code for **Ellza**, a Mental Health Care Bot designed to provide support for stress, anxiety, and other mental health concerns. Ellza leverages **Retrieval-Augmented Generation (RAG)** to enhance its responses with relevant information from a custom knowledge base. It runs entirely on a local machine, ensuring privacy and security for users.

## Key Features
- **RAG-Enhanced Responses**: Utilizes Retrieval-Augmented Generation to provide accurate, contextually relevant information and advice.
- **Local Execution**: Runs on your local machine to ensure data privacy and security.
- **Customizable Knowledge Base**: Easily extend Ellza's knowledge by adding or updating the local database.
- **Support for Various Mental Health Issues**: Focuses on stress, anxiety, depression, and other common mental health challenges.
- **Interactive and User-Friendly**: Designed to offer an engaging, empathetic interaction experience.

### Installation and running 

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Harisindhu-5/ALPHA-SQUAD_TECH-A-THON_2024.git

2. **Install the required dependencies**
    ```bash
    pip install -r requirements.txt
3. **Run Ellza**
    ```bash
    chainlit run model.py -w
**Note**
    1. Running this for first time may take some time since it run on cpu of the local machine,
    2. It may download some large files to for the model support 
    3. Make sure the you Machine RAM is 8 Gib or More

