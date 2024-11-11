# FileFusion-Powered-by-Gemini

This project enables users to interact with various document formats (PDF, Word, PowerPoint, Excel, CSV) using a chatbot interface powered by **Google Gemini** and **Langchain**. You can upload documents, extract their content, and ask questions about the content. The chatbot uses embeddings to provide intelligent answers based on the document's data.

## Features
- Upload and process documents in multiple formats: PDF, Word, PowerPoint, Excel, and CSV.
- Text extraction from the documents.
- Chunking of large texts to optimize for search and retrieval.
- Integration with Google Generative AI and Langchain for Q&A based on the document content.
- Easy-to-use interface with **Streamlit** for a smooth user experience.

## Tools & Technologies Used
- **Streamlit**: For building the web application and interactive UI.
- **Langchain**: For managing the question-answering chain and working with document embeddings.
- **Google Generative AI (Gemini)**: For generating embeddings and providing Q&A capabilities.
- **FAISS**: For storing and searching document embeddings efficiently.
- **PyPDF2**: For extracting text from PDF documents.
- **python-docx**: For extracting text from Word documents.
- **python-pptx**: For extracting text from PowerPoint presentations.
- **Pandas**: For reading and processing Excel and CSV files.
- **dotenv**: For managing environment variables such as API keys.
- **GitHub Actions** (optional, if you want CI/CD integration for deployments).

## Installation & Setup

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
