## 🔗 Links
Follow on 
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debendra-bakhati/)

# PDF Chatbot

This is a Streamlit application that allows users to query multiple PDF files and get responses from a conversational AI model. The application utilizes Google Generative AI for embeddings and conversational responses.

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/Debendra62/Chat_with_PDF.git
```

### Set Up the Virtual Environment

Create and activate a virtual environment:

```bash
conda create -p venv python==3.11
conda activate /Chat_with_PDF/venv   
```

### Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
conda install -c conda-forge faiss-cpu       
```

### Set Up Environment Variables

Create a .env file in the root directory of the project and add your Google API key:

```env
GOOGLE_API_KEY=your_google_api_key      
```

### Run the Application

To run the Streamlit application, use the following command:

```bash
streamlit run app.py
```

