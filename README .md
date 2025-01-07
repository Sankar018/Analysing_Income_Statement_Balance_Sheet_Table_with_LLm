---

# 📄 PDF Table Extraction & Summarization  

Welcome to the **PDF Table Extraction & Summarization** project! This innovative application enables seamless extraction of tables from PDF documents and generates concise summaries powered by advanced AI models. Built with **Streamlit**, this tool offers an intuitive and interactive user experience for enhanced productivity.  

---

## 🚀 Key Features  

- **📤 Upload PDFs**: Easily upload PDF documents through a user-friendly interface.  
- **👀 Preview PDFs**: View the contents of your PDFs directly within the application.  
- **📊 Extract Tables**: Automatically detect and extract tables from uploaded PDFs.  
- **📝 Summarize Tables**: Generate insightful summaries for each extracted table using AI-powered summarization.  
- **🧹 Automatic Cleanup**: Securely deletes temporary files after processing, ensuring efficiency and data privacy.  

---

## 🛠️ Installation  

Follow these steps to set up and run the project locally:  

### 1️⃣ Clone the Repository  
```bash  
git clone https://github.com/yourusername/pdf-table-extraction.git  
cd pdf-table-extraction  
```  

### 2️⃣ Set Up a Virtual Environment (Optional but Recommended)  
Create a virtual environment to isolate dependencies:  
```bash  
python -m venv venv  
```  
Activate the virtual environment:  
- **Windows**:  
  ```bash  
  venv\Scripts\activate  
  ```  
- **macOS/Linux**:  
  ```bash  
  source venv/bin/activate  
  ```  

### 3️⃣ Install Dependencies  
Install all required packages:  
```bash  
pip install -r requirements.txt  
```  

---

## 🖥️ Usage  

Run the application with the following command:  
```bash  
streamlit run app.py  
```  

### Steps to Use the Application:  

1. **📂 Upload Your PDF**:  
   Use the sidebar to upload your PDF file.  

2. **🔍 Preview the PDF**:  
   View a preview of the uploaded PDF within the application.  

3. **📑 Extract Tables**:  
   The app will detect and display extracted tables in expandable sections.  

4. **📝 Summarize Tables**:  
   Generate and view detailed summaries for each extracted table.  

---

## 📁 Project Structure  

```plaintext  
pdf-table-extraction/  
├── app.py                # Main application file  
├── requirements.txt      # Python dependencies  
├── utils/                # Utility scripts  
│   ├── table_extraction.py   # Handles table extraction from PDFs  
│   └── summarization.py      # Summarizes extracted table data  
├── README.md             # Project overview and instructions  
├── assets/               # (Optional) Directory for icons or images  
│   └── icons/            # Folder for storing icon files  
```  

---

## 🧰 Dependencies  

The project utilizes the following libraries:  

- **Streamlit**: For building the interactive web application.  
- **Pandas**: For efficient data manipulation and analysis.  
- **PyPDF2**: For reading and processing PDF files.  
- **Mistralai**: For AI-driven summarization (ensure proper installation and configuration).  

### Full List of Dependencies:  

```plaintext  
streamlit  
pandas  
PyPDF2  
mistralai  
```  

---

## 🌐 Contributing  

We welcome contributions to enhance this project. Follow these steps to contribute:  

1. **Fork the Repository**  
2. **Create a New Branch**:  
   ```bash  
   git checkout -b feature/YourFeature  
   ```  
3. **Commit Your Changes**:  
   ```bash  
   git commit -m "Add your message here"  
   ```  
4. **Push to the Branch**:  
   ```bash  
   git push origin feature/YourFeature  
   ```  
5. **Open a Pull Request**  

---

## 📝 License  

This project is licensed under the **MIT License**.  

---  
