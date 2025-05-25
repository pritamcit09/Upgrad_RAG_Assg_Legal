# Upgrad Legal QnA System (RAG and NLP) – Project Summary:

A Legal QnA system was developed using Langchain, OpenAI GPT-3.5-turbo, text-embedding-3-small and vector databases (FAISS/QDrant) with a Retrieval-Augmented Generation (RAG) approach. Legal documents were preprocessed, chunked, embedded, and stored for similarity-based retrieval. A custom Langchain chain enabled contextual answering. Evaluation was done using benchmark answers in pandas DataFrames.

Key Outcomes:

Answers were relevant when source documents were available.

Token limits restricted the volume of processed data, affecting accuracy.

FAISS and QDrant performed similarly.

Future work includes handling larger datasets, improving evaluation, and optimizing retrieval.

This project demonstrates a full RAG-based QnA lifecycle for legal document understanding.
