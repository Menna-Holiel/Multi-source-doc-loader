# Multi-Source Document Loader

## 📌 Overview
This project demonstrates how to use **LangChain Community Loaders** to extract and process content from different sources:
- **Text files** 
- **PDF documents**
- **Web pages** with BeautifulSoup filters

---

## ⚙️ Tools & Libraries Used
- **LangChain Community** – document loaders
- **PyPDF** – PDF parsing
- **BeautifulSoup (bs4)** – web content extraction
- **Python (Colab/Jupyter)** – development environment

---

## 🚀 How It Works
1. **Text Loader**  
   - Loads plain text documents from files (`speech.txt`).  

2. **PDF Loader**  
   - Extracts text from PDF documents (`attention.pdf`).  

3. **WebBase Loader**  
   - Fetches and parses web pages using BeautifulSoup filters.  
   - Example: extracting content from [Lilian Weng’s blog on Agents](https://lilianweng.github.io/posts/2023-06-23-agent/).  

---

## ▶️ How to Run
1. Install dependencies:
   ```bash
   pip install langchain_community pypdf bs4
