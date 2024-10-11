# Projects

## [RAG PDF Chatbot](https://github.com/BrunoFelalaga/RAG_PDF_Chatbot)
This project developed an interactive PDF chatbot to enable users to upload documents to a chatbot and be able to query the bot on the contents of the documents. This implements Retrieval-Augmented Generation to provide more and accurate context for the LLM for each query. 

#### Advanced PDF Parsing and Querying:
- Developed an interactive PDF chatbot that allows users to upload and query multiple PDFs or DOCX files, providing real-time responses based on the document content.
- Integrated **PyPDF** for seamless document processing and **RAG (Retrieval-Augmented Generation)** to enhance accuracy by retrieving relevant document chunks before generating responses.

#### Efficient Text Chunking and Semantic Search:
- Implemented text chunking using **LangChain’s `CharacterTextSplitter`** to optimize the querying process and preserve context across chunks.
- Enabled the **RAG model** to retrieve and synthesize information from large documents while maintaining coherence and precision in the chatbot’s responses.

#### Embedding and Vector Storage with FAISS:
- Leveraged **OpenAI embeddings** to transform text chunks into high-dimensional vector representations.
- Utilized **FAISS** as a local vector store to support efficient retrieval of relevant text for semantic search, a core component of the **RAG** pipeline.

#### Conversational Memory and Context Retention with RAG:
- Created a robust **Conversational Retrieval Chain** using **OpenAI’s chat model** and **LangChain’s buffer memory**, integrated within a **RAG framework**.
- This allowed the chatbot to maintain conversation context across multiple queries, enhancing user experience during follow-up questions by retrieving pertinent document sections.

#### Streamlined UI with Real-Time Processing Feedback:
- Built a user-friendly interface with **Streamlit**, enabling real-time feedback for users when uploading and processing documents.
- The **RAG model** provided accurate, contextually relevant answers by retrieving and generating responses from the document database in real time, ensuring smooth interaction and improved overall usability.


---


## msh - (Unix-like Shell)
msh implemented a functional Unix-like shell that simulates core features of traditional Unix environments, allowing users to manage processes, execute commands, and navigate file systems.

#### Custom Shell Implementation:
- Developed a fully functional **Unix-like shell** that emulates core features of a typical Unix shell, including user login, job control, and command execution.
- The shell allows users to interact with processes, manage foreground and background jobs, and handle user sessions.

#### User Authentication and Directory Management:
- Implemented user authentication with a **passwd** file, where users must log in with valid credentials to access the shell.
- Integrated a **/home** directory structure for each user with personalized history files, storing the last 10 commands executed.

#### Job Control and Signal Handling:
- Built job control mechanisms, enabling users to run jobs in the background or foreground, list active jobs, and terminate them.
- The shell includes signal handlers for **SIGINT**, **SIGTSTP**, and **SIGCHLD**, ensuring proper control over processes through **Ctrl+C**, **Ctrl+Z**, and background process management.

#### Process Management with /proc Filesystem:
- Developed a virtual **/proc filesystem** that mirrors the Unix-like process information structure, maintaining process metadata like process IDs, parent process IDs, and session states.
- Each process generates a status file in the **/proc/PID** directory, updating the state dynamically as the process runs.

#### Command Parsing and Built-in Functionality:
- Implemented a custom command parser using **tokenization** and argument separation, enabling users to execute built-in commands like `jobs`, `history`, and `logout`, or run external programs by providing the full path.
- The shell supports adding new users with the `adduser` command, restricted to **root** privileges, ensuring controlled access to the system.

---


## Crop Yield Prediction with Sparse Data  
This project aims to leverage remote sensing and climatology data to develop predictive models for estimating crop yields in Northern Uganda, addressing the challenges posed by sparse data availability in agricultural contexts.

#### Data Collection and Integration:
- Utilized the **NASA CropHarvest datasets** to gather remote sensing and climatology data, including information from Sentinel-2, Sentinel-1, and the SRTM Digital Elevation Model.
- Compiled and preprocessed data from multiple sources to create a comprehensive dataset for training predictive models.

#### Model Development for Yield Prediction:
- Implemented various machine learning models, with a focus on **Random Forest** due to its robustness with sparse data and capacity to handle irrelevant features.
- Explored **Long Short-Term Memory (LSTM)** networks with Gaussian Process layers for temporal data analysis, aiming to capture spatio-temporal dynamics in crop yield.

#### Evaluation Metrics and Model Tuning:
- Employed evaluation metrics including **R²**, achieving a score of **0.85** for model accuracy, and **Root Mean Square Error (RMSE)** of **3.2 tons/ha** in predicting crop yield.
- Calculated **Normalized RMSE (nRMSE)**, resulting in a value of **0.15**, indicating effective model performance relative to yield variance.
- Conducted hyperparameter tuning using validation sets to optimize model performance while preventing overfitting.

#### Visualization and Analysis:
- Developed visualizations to compare predicted yields against actual yields, identifying patterns and potential biases in model predictions.
- Utilized exploratory data analysis techniques to gain insights into the relationships between environmental factors and crop yield.

#### Software and Tools:
- Leveraged **Python** libraries such as **scikit-learn** and **TensorFlow** for model development, along with **Pandas** and **NumPy** for data manipulation.
- Implemented the project within **Google Colab** for collaborative coding and easy access to computational resources.

#### Future Directions:
- Plans to enhance model generalizability by incorporating additional geographical data and experimenting with different machine learning architectures.
- Aiming to publish findings and methodologies to contribute to ongoing research in agricultural data science and yield prediction in Africa.


---


## Geospatial Data Processing  
*UChicago TechTeam & Genesys Work*  
**Sept 2023 - Present**  
This project focuses on developing data-driven solutions for non-profit organizations in Chicago by leveraging geospatial technologies to enhance internship matching and improve transportation efficiency.

- Mentoring undergraduates on software and data strategies for non-profit firms in Chicago.
- Creating a platform for pairing high school students with internships in Chicago.
- Integrating Google Maps API to streamline location pairing using GPS data and zip codes.
- Developing algorithms to optimize transit times and utilizing Power BI for data visualization.


---


## Virtual Book Club - Group Project  
*UChicago*  
**June 2023 - Present**  
This project involves creating a comprehensive social platform designed for book reading and discussion, aimed at fostering community engagement among readers.

- Leading the development of an end-to-end social platform with **FastAPI** for book reading and discussion.
- Executed CRUD operations, integrated authentication, and managed relational database structures.
- Integrated **CI/CD pipelines** for automated testing across various platforms.
- Tested the platform with ~20 users and continuously incorporated user feedback.


---


---
[Skills](skills.md) | [Experience](experience.md) | [Projects](projects.md) | [Leadership & Engagement](leadership.md) | [Publications](publications.md) 
<br>
[Back to Home](index.html)

