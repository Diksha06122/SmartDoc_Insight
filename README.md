# SmartDoc_Insight
SmartDoc Insight reads text from URLs, PDFs, and documents to answer queries using Retrieval-Augmented Generation (RAG) and Hugging Face embeddings. It utilizes FAISS, a vector database, for efficient retrieval and management of embeddings, providing quick and relevant responses to enhance document interaction and knowledge extraction.<br>
<br>
## Key Features: <br>
 * **Multi-source Document Reading:** Capable of extracting text from URLs, PDFs, and text documents. <br>
 * **Advanced Query Answering:** Utilizes RAG and Hugging Face embeddings for accurate responses. <br>
 * **Efficient Data Management:** Employs FAISS for fast and efficient embedding retrieval. <br>
 * **Context-aware Interaction:** Enhances document interaction and knowledge extraction with context-aware insights..<br>
 <br>
## Technologies Used: <br>
Retrieval-Augmented Generation (RAG): Combines retrieval-based and generative models to improve response relevance and accuracy. <br>
Hugging Face Embeddings: Provides state-of-the-art embeddings for natural language understanding. <br>
FAISS (Facebook AI Similarity Search): A vector database optimized for efficient similarity search and clustering of dense vectors. <br>
<br>
## Project Structure: <br>
### Data Ingestion: Extracts text from various sources. <br>
 - Supported Formats: URLs, PDFs, text documents. <br>
### Data Processing: Processes and cleans extracted text. <br>
 - Text Cleaning: Removes noise and irrelevant content. <br>
###Embedding Creation: Converts processed text into embeddings. <br>
 - Embedding Models: Uses Hugging Face models for embedding generation. <br>
###Storage and Retrieval: Manages embeddings using FAISS. <br>
 - Vector Database: Stores embeddings for efficient retrieval. <br>
###Query Answering: Responds to user queries using RAG. <br>
 - Query Processing: Matches queries with relevant embeddings and generates responses. <br>
