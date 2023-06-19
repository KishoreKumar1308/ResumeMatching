# ResumeMatching
Matching resumes to the job description, based upon their similairty using LangChain, ChromaDB and LLM.

# How it Works?
The program is written as an API that can
- accept a folder path consiting of resumes and clean, save the files as a TXT file
- an upload method, that will take the cleaned TXT files, convert it into Vector Embeddings and stores it in a vector database, ChromaDB
- a matching method, that will take in the job description as an input and returns the matched resumes along with their summarization

# Methods used
OpenAI is used for crearting the Vector Embeddings. LLM (Large Language Model) is also from OpenAI (gpt-3.5 turbo). The created vector embeddings are stored in the ChromaDB vector database.
