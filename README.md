# 🛡 Autonomous Insurance Claims Processing Agent

## Overview

This project is an AI-powered First Notice of Loss (FNOL) Claims Processing Agent developed using Python and Streamlit.

The application extracts information from insurance claim documents, validates mandatory fields, recommends claim routing, and logs processed claims into an Excel file.

---

## Features

- 📄 Upload PDF and TXT claim documents
- ✍️ Manual claim text input
- 🤖 Automatic claim field extraction
- ✅ Missing field validation
- 🚦 Intelligent claim routing
- 📊 Excel logging
- 📦 JSON output
- 💻 Streamlit dashboard

---

## Tech Stack

- Python
- Streamlit
- OpenAI / Ollama
- pdfplumber
- pandas
- openpyxl

---

## Installation

```bash
git clone https://github.com/D-UJWAL/InsuranceAgent.git
cd InsuranceAgent
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file.

Example:

```env
OPENAI_API_KEY=YOUR_API_KEY
```

---

## Run

```bash
streamlit run app.py
```

---

## Workflow

1. Upload a claim document or paste claim text.
2. Click **Process Claim**.
3. Extract claim details.
4. Validate mandatory fields.
5. Recommend the claim route.
6. Save results to Excel.
7. Display JSON response.

---

## Project Structure

```text
app.py
pipeline.py
extractor.py
llm_client.py
excel_logger.py
requirements.txt
claims_log.xlsx
```

---

## Future Improvements

- User authentication
- Database integration
- OCR support
- Email notifications
- Admin dashboard

---

## Author

**Ujwal D**
