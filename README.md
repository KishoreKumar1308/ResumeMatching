# ResumeMatching
Matching resumes to the job description, based upon their similairty using LangChain, ChromaDB and LLM.

# How it Works?
The program is written as an API that can
- accept a folder path consiting of resumes and clean, save the files as a TXT file
- an upload method, that will take the cleaned TXT files, convert it into Vector Embeddings and stores it in a vector database, ChromaDB
- a matching method, that will take in the job description as an input and returns the matched resumes along with their summarization
