# Mini Gemini

Mini Gemini is a Streamlit web application that utilizes Google's Generative AI models for various tasks including chat search, PDF reading, image analysis, and database analysis.

- 
## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)
- [Requirements](#requirements)

## Features

### Chat Search
- Allows users to interact with a Generative AI chatbot.
- Users can input their queries and receive responses from the chatbot.

### PDF Reader
- Enables users to upload PDF files.
- Generates content based on the input text and the uploaded PDF file using Generative AI.

### Image Reader
- Allows users to input prompts and upload images.
- Generates textual descriptions or analysis of the uploaded image using Generative AI.

### Database Reader
- Enables users to input prompts about databases.
- Users can get the analysis of the database.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/mini-gemini.git
cd mini-gemini
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Set up environment variables:
    - Obtain a Google API key and set it as `GOOGLE_API_KEY` in a `.env` file.

4. Run the Streamlit app:

```bash
streamlit run app.py
```

## Usage

1. Select the desired functionality from the sidebar menu.
2. Follow the prompts and provide necessary inputs (e.g., text, files, database name).
3. Click on the corresponding button to trigger the action (e.g., "Answer", "Tell me about the PDF").
4. View the results displayed on the app.

## Requirements

- Python
- Streamlit
- API Key (Google)
- streamlit
- google-generativeai
- python-dotenv
- pdf2image

## Screenshot

---

Feel free to contact me.
