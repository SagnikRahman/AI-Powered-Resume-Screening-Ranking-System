# AI-Powered Resume Screening & Ranking System

## 🚀 Overview
The **AI-Powered Resume Screening & Ranking System** is a **Streamlit-based web application** that automates the process of evaluating and ranking resumes based on a given job description. Using **Natural Language Processing (NLP)** techniques, this tool extracts text from resumes (PDFs), computes **TF-IDF vector representations**, and ranks candidates based on **cosine similarity**.

## 🔥 Features
-  **Upload multiple resumes (PDF format)**
-  **Enter job description manually**
-  **Automated ranking based on similarity matching**
-  **Displays results in an interactive table**
-  **User-friendly UI with Streamlit**

## 🛠️ Tech Stack
- **Python** (Core programming language)
- **Streamlit** (For UI development)
- **PyPDF2** (For extracting text from PDF resumes)
- **Scikit-learn** (For TF-IDF and cosine similarity calculations)
- **Pandas** (For data processing and visualization)

## 📂 Running the Project on Google Colab
### 1️⃣ Open Google Colab and Create a New Notebook
Go to [Google Colab](https://colab.research.google.com/) and create a new notebook.

### 2️⃣ Install Dependencies
Run the following command in a Colab cell:
```python
!pip install streamlit PyPDF2 scikit-learn pandas
```

### 3️⃣ Write and Save the Script
Create a Python script (`app.py`) in Colab using:
```python
%%writefile app.py
# Paste the complete app.py code here
```

### 4️⃣ Run the Streamlit App
Execute the following command to start the application:
```python
!streamlit run app.py & npx localtunnel --port 8501
```
This will generate a public URL where you can access the application.

## 🏗️ How It Works
1. **Upload multiple resumes** in PDF format.
2. **Enter the job description** in the sidebar.
3. **Click the "Rank Resumes" button** to process the data.
4. The system **extracts text** from resumes and applies **TF-IDF vectorization**.
5. **Cosine similarity** is used to rank resumes based on their relevance.
6. **Results are displayed** in a sorted table, with higher scores indicating better matches.

## 🏆 Contributors
👤 **Sagnik Rahman**  **[LinkedIn](https://www.linkedin.com/in/sagnik-rahman)**  
