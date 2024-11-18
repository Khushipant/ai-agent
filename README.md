
# Data Processing and AI Agent Web App

This project provides a platform for users to upload data (in CSV, Excel, or Google Sheets format), ask questions about the data, and receive Python code that processes the data to answer the question. The system uses **Groq**'s API to access the **LLaMA model** and LangChain for natural language processing, and Flask to serve the web application. The project also integrates Google Sheets and file handling functionalities for easy data input.

## Features

- **Data Upload**: Users can upload data as a CSV file, Excel file, or link a Google Sheet.
- **Natural Language Querying**: Users can ask questions about the data in plain English.
- **Dynamic Code Generation**: The app generates Python code using LangChain to answer questions without altering the uploaded data.
- **Flask Web App**: A user-friendly web interface to upload files and view responses.
- **Integration with Google Sheets**: Ability to fetch data directly from Google Sheets.
- **Streamlit Dashboard**: Easily visualize and process the data through a Streamlit interface.
- **AI Model**: Uses **Groq** API to access **LLaMA** model for powerful question-answering capabilities.
- **Google Sheets Integration**: Data from Google Sheets can be accessed and processed in the web app.

## Installation

1. Clone the repository or download the code.
2. Create a virtual environment (optional, but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # For macOS/Linux
   .\venv\Scripts\activate    # For Windows
