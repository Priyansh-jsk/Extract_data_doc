# Extract_data_doc

**Extract text, with Summarization, images, table from documents.**

This Streamlit application.

**Steps-**

Create a virtual environment (optional but recommended):

_python -m venv venv_

_venv\Scripts\activate_ -> for windows

Install required packages:

_pip install streamlit pdfplumber pytesseract pillow pandas groq python-dotenv_

Install Tesseract OCR:

Create a .env file in the project root and add your Groq API key:

_GROQ_API_KEY=your_groq_api_key_here_

To run application-

_streamlit run app.py_
