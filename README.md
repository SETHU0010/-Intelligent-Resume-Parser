# 📄 Resume Parser & Metadata Extractor with Gemini API

A Flask web application that extracts structured information from uploaded resumes (PDF or DOCX), using both AI (Gemini API) and traditional methods (Regex/Keyword Extraction).

---

## 🚀 Features

- ✅ Upload `.pdf` or `.docx` resume files
- 🤖 Extract metadata using **Gemini AI API**
- 🔍 Fallback to **Regex & Keyword-based Extraction**
- 📋 Extracts:
  - Name
  - Email
  - Phone
  - Skills
  - Education
  - Experience
  - Certifications
- 🧠 Intelligent parsing with context-awareness
- 🌐 Flask-based web interface

---

## 🧠 Problem Statement

Manual resume screening is tedious, inconsistent, and inefficient. Recruiters need a tool to automate and standardize the extraction of key information from resumes.

---

## 🎯 Aim

To build a web application that automates resume metadata extraction using Gemini AI, improving the speed and accuracy of resume parsing.

---

## ✅ Solution

- Accepts PDF/DOCX resume uploads
- Extracts text content
- Uses Google Gemini AI for structured metadata extraction
- Falls back to regex/keyword extraction if Gemini fails
- Displays parsed results on the web interface

---

## ⚙️ Tech Stack

| Component     | Technology     |
|---------------|----------------|
| Backend       | Flask (Python) |
| AI API        | Gemini (Google Generative AI) |
| Text Extraction | PyPDF2, python-docx |
| UI            | HTML, Jinja2   |
| Hosting       | Local / Cloud  |

---

## 🔄 Approach

1. User uploads resume(s)
2. File content extracted (PDF or DOCX)
3. Gemini AI is used to extract metadata
4. If Gemini fails, fallback to regex
5. Parsed results displayed to user

---

## ✅ Advantages

- Fast and scalable
- Uses AI for accuracy
- Resilient with fallback logic
- Easy to use via browser
- Supports multiple formats

---

## ❌ Disadvantages

- Gemini API requires API Key and internet
- Cost may scale with high usage
- Regex extraction may lack accuracy
- Security and privacy need attention for sensitive resume data

## ✍️ Author

**Sethumadhavan V**  
📧 Email: [sethumadhavanvelu2002@gmail.com](mailto:sethumadhavanvelu2002@gmail.com)  
🐙 GitHub: [@SETHU0010](https://github.com/SETHU0010)

