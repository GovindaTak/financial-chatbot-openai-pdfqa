# financial-chatbot-openai-pdfqa
A financial document question-answering chatbot built using OpenAI GPT-4 and PyPDF2. This project allows users to extract content from financial PDFs and interact with it using natural language via a chatbot interface. The model answers queries based on a given product note (e.g., Nippon India Short Term Fund).
---
# 💬 Financial Document Chatbot using GPT-4 & PyPDF2

This project is a hands-on implementation of a **domain-specific chatbot** using **OpenAI's GPT-4** and **Python**. It enables real-time Q&A on PDF-based financial documents such as product notes, annual reports, and investment guides.

-----

## 🧠 Objective

Build a chatbot that reads a **financial document (PDF)** and accurately answers user questions by extracting and interpreting content using **in-context learning** and **LLM prompting**.

---

## 📄 Sample Dataset

- **Document Used:** [Nippon India Short Term Fund – Product Note (Jan 2024)](https://mf.nipponindiaim.com/FundsAndPerformance/ProductNotes/NipponIndia-Short-Term-Fund-Jan-2024.pdf)
- **Custom Queries Supported:**  
  - What is the investment objective?  
  - What are the key risks involved?  
  - Who should invest in this fund?

---

## 🔧 Tech Stack

- 🧠 OpenAI GPT-4 API (ChatCompletion endpoint)
- 📚 PyPDF2 (PDF reading and parsing)
- 🐍 Python 3.9+
- 💻 Jupyter Notebook / Google Colab

---

## ⚙️ Features

✅ Extracts raw text from PDF documents  
✅ Uses GPT-4 with in-context document injection  
✅ Interactive chatbot for finance-based Q&A  
✅ Modular code structure for reusability  
✅ Works with any PDF – plug and play

---

## 🚀 How It Works

### 1️⃣ PDF Reading & Text Processing  
- Load PDF using **PyPDF2**  
- Clean and format raw text for consistency

### 2️⃣ OpenAI GPT-4 Prompting  
- Uses system role and document context as prompt  
- Processes user queries using `chat.completions`

### 3️⃣ Response Handling  
- Presents clean answers to finance-related questions  
- Ensures context relevance and accuracy

---

## 💡 Sample Output

| User Query                  | Chatbot Answer                                                                 |
|----------------------------|--------------------------------------------------------------------------------|
| What is the investment strategy? | Explains asset allocation, duration management, and credit strategy       |
| Who should invest?         | Recommends investor types based on risk level and time horizon                 |
| What are the main risks?   | Lists credit risk, NAV sensitivity, liquidity challenges, and market volatility|

---

## 📚 Skills Learned

- Prompt Engineering & System Role Crafting  
- Contextual Q&A Design for LLMs  
- PDF Text Extraction using PyPDF2  
- Real-world GenAI application development  
- OpenAI API Integration in Python  
- Secure environment variable handling  
- Chat interface logic structuring

---

## 📂 Folder Structure


📦 financial-chatbot-openai-pdfqa/
┣ 📜 financial_chatbot.ipynb      # Main notebook
┗ 📄 README.md                    # Project documentation

---

## 🛠️ Installation

```bash
git clone https://github.com/GovindaTak/financial-chatbot-openai-pdfqa.git
cd financial-chatbot-openai-pdfqa
pip install -r requirements.txt
```

### Set your OpenAI API key securely:

---

## ▶️ Run the Notebook

Use `financial_chatbot.ipynb` to run all steps and test the chatbot.  
Customize the PDF or prompt logic based on your domain needs.

---

## 🧠 Next Enhancements

- Integrate vector store (e.g., FAISS, LangChain) for semantic search  
- Enable conversation memory using session state  
- Expand support for multiple PDFs in the same chat  
- Add a Streamlit UI for easy deployment  

---

## 📜 License

This project is licensed under the MIT License.

---

## 📬 Contact

**👤 Govinda Tak**  
📧 Email: govindatak19@gmail.com  
🔗 [GitHub Profile](https://github.com/GovindaTak)

```
