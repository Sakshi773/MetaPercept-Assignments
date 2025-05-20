# MetaPercept-Assignments


This files contains two assigments given by Metapercept as a test.

## Assessment 1: Mini RAG Pipeline with ChromaDB on Colab

Instructions:

Use Google Colab for the task.
Take 3–5 short documents (you can hardcode them).
Preprocess the text by converting to lowercase and removing punctuation.
Embed the documents using any method you prefer (e.g., sentence-transformers, HuggingFace, or other embedding techniques).
Store the embeddings in ChromaDB or FAISS (use ChromaDB for simplicity).
Accept a user query and retrieve the most relevant document based on cosine similarity.
Generate a simple response by outputting the most relevant document.


## Assessment 2: Building a Knowledge Graph with Semantic Search and Query Answering

Instructions:
Build a basic RDF knowledge graph using the rdflib library.
Example: "Alice is a person," "Alice knows Bob," "Bob works at Acme Corp."
Convert the RDF triples into simple text sentences (e.g., "Alice knows Bob").
Embed these text sentences using any method you prefer (e.g., sentence-transformers, HuggingFace, or other embedding techniques).
Store the embeddings in FAISS or ChromaDB.
Accept a simple user query like: "Who does Alice know?" and return the relevant text from the stored embeddings.
