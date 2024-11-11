# FileFusion-Powered-by-Gemini
# FileFusion is a powerful AI-driven tool that enables users to interact with and extract insights from various document formats, including PDF, Word, PowerPoint, Excel, and CSV. Powered by Gemini's advanced generative capabilities, this project provides a conversational interface where users can ask questions based on the contents of their uploaded documents, and receive detailed, context-aware answers.

Key Features:

Multi-format Document Support: Supports PDF, Word, PPT, Excel, and CSV file types.
Text Extraction: Extracts and processes text from documents with high accuracy.
Advanced AI Chatbot: Utilizes Gemini's generative AI for context-based question answering.
Vector Search Integration: Leverages FAISS for efficient document indexing and similarity search.
Seamless User Interface: A simple and intuitive web app built with Streamlit for easy user interaction.
How it Works:

Upload Documents: Users upload their documents (PDF, Word, PPT, Excel, CSV).
Text Extraction: The text is extracted from the documents and preprocessed into manageable chunks.
AI-Powered Q&A: Users can ask questions, and the system will provide context-aware answers based on the content of the uploaded documents.
Vector Store for Enhanced Search: Text from the documents is indexed using FAISS and Google Generative AI embeddings for fast and accurate query processing.
Technologies Used:

Streamlit: For building the web interface.
Langchain: For AI integrations and document processing workflows.
Google Generative AI: For embedding and response generation.
FAISS: For vector storage and similarity search.
PyPDF2, python-docx, python-pptx, pandas: For document parsing.
Installation:

Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/GeminiDocs.git
Install dependencies:
Copy code
pip install -r requirements.txt
Run the app:
arduino
Copy code
streamlit run app.py
