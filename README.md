#GeminiDocs: AI-Powered Document Chatbot
GeminiDocs is an AI-powered tool that allows users to interact with and extract insights from documents like PDFs, Word, PowerPoint, Excel, and CSV files. By leveraging Gemini's advanced generative capabilities, users can ask questions about the content of their documents, and receive context-aware answers based on the document's data.

Features
Multi-format Document Support: Supports a wide range of file formats, including PDF, Word (.docx), PowerPoint (.pptx), Excel (.xlsx), and CSV.
Text Extraction: Extracts text from documents with high accuracy using specialized libraries.
AI-Powered Question Answering: Utilizes Gemini’s generative AI to provide detailed answers based on the document content.
Vector Search Integration: Uses FAISS for efficient document indexing and similarity-based search, providing fast responses to user queries.
User-Friendly Interface: Built using Streamlit, offering a simple and intuitive web app for seamless user interaction.
How It Works
Upload Documents: Upload your files (PDF, Word, PPT, Excel, or CSV) via the web interface.
Text Extraction: Text from the uploaded documents is extracted and processed into manageable chunks.
AI-Powered Q&A: Ask any question based on the document content, and the system will generate a context-aware answer using Gemini’s generative AI model.
Search and Indexing: The document content is indexed with FAISS for efficient similarity search, allowing quick access to relevant data when answering queries.
Technologies Used
Streamlit: For building the web interface.
Langchain: For creating workflows that connect document processing and AI interactions.
Google Generative AI: For text embeddings and context-aware response generation.
FAISS: For fast similarity search and vector storage.
PyPDF2: For extracting text from PDF documents.
python-docx: For extracting text from Word documents.
python-pptx: For extracting text from PowerPoint presentations.
pandas: For working with Excel and CSV data.
Installation
To run GeminiDocs locally, follow these steps:

1. Clone the repository
bash
Copy code
git clone https://github.com/yourusername/GeminiDocs.git
2. Install dependencies
Make sure you have Python 3.7+ installed. Then, install the required libraries:

bash
Copy code
cd GeminiDocs
pip install -r requirements.txt
3. Set up environment variables
You will need a Google Generative AI API key. Create a .env file in the root directory with the following content:

makefile
Copy code
GOOGLE_API_KEY=your_google_api_key_here
4. Run the app
Start the Streamlit web app:

bash
Copy code
streamlit run app.py
Visit http://localhost:8501 in your browser to start interacting with the app.

Usage
Upload Your Documents: Use the file uploader on the sidebar to upload your documents (PDF, Word, PPT, Excel, or CSV).
Ask a Question: Once the documents are uploaded and processed, enter your question in the input box.
View Answer: GeminiDocs will generate a response based on the contents of the uploaded documents.
Example
After uploading a PDF document, you can ask questions such as:

“What is the main conclusion of the document?”
“Can you summarize the first chapter?”
“What is the financial data in the Excel sheet?”
GeminiDocs will extract the relevant content and generate answers based on the document's data.
