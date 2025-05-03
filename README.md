# Alois
The theme of this project is: An intelligent web content assistant that scrapes any URL, stores content in a vector database, and uses a local LLM with an agent to summarize and answer user queries contextually.

---

## Features of this Project: 

 - **Webpage Interaction**: Chat with any website by simply entering its URL.
 - **RAG-Enabled Intelligence**: Leverages Retrieval-Augmented Generation for accurate, context-aware answers. 
 - **Vector Database Integration**: Ensures fast, precise retrieval of relevant content from a semantic knowledge base.
 - **Streamlit Interface**: Delivers a smooth and intuitive user experience via a clean Streamlit frontend.

# In order to setup and run this project, follow the following instructions:

###  Prerequisites

- Python 3.8 or above
- Git Installed
- Groq API key

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YugMakhecha17/AloisWork.git
   cd AloisWork
   ```
2. **Set Up a Virtual Environment**
     ```bash
   python -m venv myenv
   ```
3. **Activate the Virtual Environment**
   - On Windows:
     ```bash
     myenv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source myenv/bin/activate
     
4. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Application**
   Start the Streamlit app:
   ```bash
   streamlit run streamlit_app.py
   ```

---

## Usage

1. Provide the URL of the webpage you want to chat with.
2. Ask questions or request summaries about the content of the webpage.
3. The application will generate responses based on the webpage's content using RAG and DeepseekR1.





