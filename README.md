# 📄 Multi-Format PDF Converter – Convert Any File to PDF with Python

This project allows you to **instantly convert multiple file formats into clean, readable PDF documents** using Python.
It supports text files, Word documents, CSV data tables, Markdown files, images, and even Jupyter Notebook cells — both code & markdown!

Perfect for students, developers, automation tasks, and real-world utility projects.


## ✨ Features

* 📄 Convert TXT → PDF
* 📘 Convert DOCX → PDF
* 📊 Convert CSV → PDF
* 📝 Convert Markdown (.md) → PDF
* 🖼 Convert Images (JPG/PNG) → PDF
* 🧪 Convert Jupyter Notebook (.ipynb) → PDF
* 📃 Automatically handles long content with page breaks
* ⚡ Fast, lightweight, offline — no internet needed
* 💯 100% working , clean PDF output every time

---

## 📦 Installation

1️⃣ **Just run:**

```bash
python converter.py
```
2️⃣ **Clone the Repo**

```bash
https://github.com/codertheashish/Pdf_generate.git
```


## ▶️ How it works

1. Enter the file path in the program
2. Program auto-detects the file format
3. Correct converter function runs
4. PDF is generated with the same filename
5. Final output saved instantly in the same folder

---

## 🧠 Supported Conversions Logic

```
📄 TXT      → Text written line-by-line
📝 MD       → Markdown converted to formatted text
📘 DOCX     → Extracts each paragraph
📊 CSV      → Converts rows into readable table lines
🖼 Image    → Directly saved as PDF
📓 IPYNB    → Reads markdown + code cells
```

PDF is created using **ReportLab** with clean margins and auto page breaks.

---

## 🛠 Requirements

Install required libraries:

```bash
pip install reportlab pillow pandas python-docx markdown
```

---

## 📁 Project Structure

```
📦 PDF-Converter
 ┣ 📜 converter.py
 ┗ 📄 README.md
```

---

## 🌈 Why this project?

* Perfect for college submissions
* Useful for automating documentation
* Converts notebooks without exporting
* Multiple format support in one tool
* Looks great in GitHub projects
* Shows file handling, parsing & PDF generation

---

## 💡 Want more features?

I can add:

✅ Merge multiple PDFs
✅ Password-protected PDFs
✅ GUI version (Tkinter)
✅ Drag & Drop file conversion
✅ Dark mode converter window

---

## 📜 License

This project is open-source under MIT License.

---

## 👨‍💻 Author

**Ashish Kumar Prajapati**
<img width="1672" height="941" alt="Pdf_generate" src="https://github.com/user-attachments/assets/0452bb47-49e6-427d-b4e1-5f4570c9b778" />
