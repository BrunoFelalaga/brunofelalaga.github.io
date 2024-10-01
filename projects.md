# Projects

## PDF Chatbot

### Advanced PDF Parsing and Querying:
- Developed an interactive PDF chatbot that allows users to upload and query multiple PDFs or DOCX files, providing real-time responses based on the document content.
- Integrated **PyPDF** for seamless document processing and **RAG (Retrieval-Augmented Generation)** to enhance accuracy by retrieving relevant document chunks before generating responses.

### Efficient Text Chunking and Semantic Search:
- Implemented text chunking using **LangChain’s `CharacterTextSplitter`** to optimize the querying process and preserve context across chunks.
- Enabled the **RAG model** to retrieve and synthesize information from large documents while maintaining coherence and precision in the chatbot’s responses.

### Embedding and Vector Storage with FAISS:
- Leveraged **OpenAI embeddings** to transform text chunks into high-dimensional vector representations.
- Utilized **FAISS** as a local vector store to support efficient retrieval of relevant text for semantic search, a core component of the **RAG** pipeline.

### Conversational Memory and Context Retention with RAG:
- Created a robust **Conversational Retrieval Chain** using **OpenAI’s chat model** and **LangChain’s buffer memory**, integrated within a **RAG framework**.
- This allowed the chatbot to maintain conversation context across multiple queries, enhancing user experience during follow-up questions by retrieving pertinent document sections.

### Streamlined UI with Real-Time Processing Feedback:
- Built a user-friendly interface with **Streamlit**, enabling real-time feedback for users when uploading and processing documents.
- The **RAG model** provided accurate, contextually relevant answers by retrieving and generating responses from the document database in real time, ensuring smooth interaction and improved overall usability.

---

## Geospatial Data Processing  
*UChicago TechTeam & Genesys Work*  
**Sept 2023 - Present**  
- Mentoring undergraduates on software and data strategies for non-profit firms in Chicago.
- Creating a platform for pairing high school students with internships in Chicago.
- Integrating Google Maps API to streamline location pairing using GPS data and zip codes.
- Developing algorithms to optimize transit times and utilizing Power BI for data visualization.

---

## Virtual Book Club - Group Project  
*UChicago*  
**June 2023 - Present**  
- Leading the development of an end-to-end social platform with **FastAPI** for book reading and discussion.
- Executed CRUD operations, integrated authentication, and managed relational database structures.
- Integrated **CI/CD pipelines** for automated testing across various platforms.
- Tested the platform with ~20 users and continuously incorporated user feedback.

---

[Back to Home](index.html)
