# Text Summarization - Infosys Internship (Oct 2024) 🚀  

This **Text Summarization Project** aims to efficiently condense long articles, research papers, or documents into concise summaries while preserving key information and context. Utilizing advanced **Natural Language Processing (NLP) techniques**, it implements both **extractive** and **abstractive** summarization approaches, alongside **large language models (LLMs)**.  

The project also incorporates **ROUGE and BLEU score evaluation** for quality assessment and features a **Gradio-based user interface** that accepts input as **text or PDFs**.  

---

## 📌 Project Overview  

Text summarization helps create meaningful and concise summaries of input text or documents. This project provides a comprehensive solution with:  

### 🔹 1. Extractive Summarization  
Identifies and extracts the most relevant sentences from the input text.  

### 🔹 2. Abstractive Summarization  
Generates summaries by paraphrasing and reinterpreting the input text.  

### 🔹 3. Advanced Summarization Techniques  
Uses **LLMs** with refined approaches like **MapReduce** and **Refine** for scalable and context-aware summarization.  

---

## 🛠️ Techniques and Models  

### **1️⃣ Extractive Summarization**  
- **Frequency Method**: Summarizes text based on word frequencies.  
- **Sumy Method**: Utilizes the Sumy library to extract relevant sentences.  
- **Luhn Method**: Identifies important sentences using word frequencies and their positions.  

### **2️⃣ Abstractive Summarization**  
- **T5 (Text-to-Text Transfer Transformer)**: A transformer model fine-tuned for summarization tasks.  
- **BART (Bidirectional and Auto-Regressive Transformers)**: Generates high-quality abstractive summaries by reconstructing corrupted text inputs.  

### **3️⃣ Advanced Summarization**  
- **Google’s LLM Models**:  
  - Utilized for state-of-the-art abstractive summarization.  
  - Models such as **PaLM (Pathways Language Model)** or **Gemini** (if supported) provide enhanced capabilities.  
- **Refine Method**: Incrementally refines generated summaries using user-defined prompts or intermediate outputs.  
- **MapReduce Method**: Splits large documents into smaller parts, summarizes them individually, and combines the results for scalability and efficiency.  

---

## 📊 Evaluation Metrics  

To assess the quality of generated summaries:  

- **ROUGE (Recall-Oriented Understudy for Gisting Evaluation)**: Measures overlap of n-grams, word sequences, and word pairs between the system-generated and reference summaries.  
- **BLEU (Bilingual Evaluation Understudy)**: Evaluates fluency and relevance of generated summaries by comparing them with reference summaries.  

---

## 🎨 Gradio Application  

A user-friendly interface built using **Gradio** to allow interactive summarization.  

### 🔹 **Key Features:**  
#### **1️⃣ Input Options:**  
- **Text Input**: Enter plain text for summarization.  
- **PDF Input**: Upload a PDF; the app extracts text and summarizes it.  

#### **2️⃣ Model Selection:**  
- **Extractive Methods**: Choose from **Frequency, Sumy, or Luhn**.  
- **Abstractive Methods**: Select **T5 or BART**.  
- **Advanced Methods**: Utilize **LLMs with Refine or MapReduce**.  

#### **3️⃣ Customizable Parameters:**  
- Set the **maximum word limit** for summaries.  
- View **word counts and summary outputs dynamically**.  

#### **4️⃣ Outputs:**  
- Generated summarized text.  
- Word count of the summary.  

---

## 💻 Implementation  

### **Technologies Used**  
- **Python**: Core language for implementation.  
- **Libraries Used:**  
  - **NLTK**: Natural Language Toolkit for text processing.  
  - **SpaCy**: NLP library for efficient text parsing.  
  - **Sumy**: Library for extractive summarization.  
  - **Transformers (Hugging Face)**: Framework for T5, BART, and LLM models.  
  - **PyPDF2**: For extracting text from PDFs.  
  - **Gradio**: For building the user interface.  

---

## 🔥 Example Use Cases  

- **📚 Academic Research**: Summarize lengthy research papers into concise abstracts.  
- **🏢 Business**: Generate executive summaries from reports and proposals.  
- **📖 Education**: Simplify textbook content for students.  

---

## 🚀 Future Enhancements  

🔹 **Cloud Integration**: Support for document uploads via **Google Drive, Dropbox, etc.**  
🔹 **Fine-Tuned Models**: Improving model performance for **domain-specific summaries**.  
🔹 **Multi-Lingual Support**: Enabling real-time summarization across different languages.  

---

## 📬 Connect with Me  

- **LinkedIn**: [Sameer](https://www.linkedin.com/in/shaik-sameer18)  
- **GitHub**: [sameerr-18](https://github.com/sameerr-18)  

💡 *Feel free to contribute, provide feedback, or reach out!*  
