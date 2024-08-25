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
    chainlit
    chainlit run Ellza.py -w

### Notes

> **Note 1:** Running this for the first time may take some time since it runs on the CPU of the local machine.

> **Note 2:** It download my download some large files.

> **Note 3:** Make sure your machine has 8 GiB of RAM or more.

> **Note 4:** It's advised to use conda langchain environment for isolated working 


### Add Your Own Data for the RAG

To add your own data to the Retrieval-Augmented Generation (RAG) system, follow these steps:

1. Add your PDF file to the `data` folder.
2. Use the following command to ingest the data:
   ```bash
   python3 ingest.py
