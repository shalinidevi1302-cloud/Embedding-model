Embedding Model
Project Overview

This project demonstrates how text embeddings can be generated using a pre-trained Sentence Transformer model and how cosine similarity can be used to identify semantically similar sentences.

Text embeddings convert sentences into numerical vectors that capture the meaning and context of the text.

In this project, the all-MiniLM-L6-v2 model from Sentence Transformers is used to generate embeddings for multiple sentences. Cosine similarity is then calculated to compare the semantic similarity between the sentences.

Features
Generate text embeddings using Sentence Transformers
Use the all-MiniLM-L6-v2 pre-trained model
Convert sentences into numerical vectors
Display the embedding dimension
Calculate cosine similarity between sentences
Identify semantically similar sentences
Display similarity scores
Project Workflow
Input Sentences
       ↓
Load Pre-trained Sentence Transformer Model
       ↓
Generate Sentence Embeddings
       ↓
Convert Sentences into Numerical Vectors
       ↓
Calculate Cosine Similarity
       ↓
Compare Similarity Scores
       ↓
Identify Similar Sentences
       ↓
Display Results
Technologies Used
Python
Sentence Transformers
Scikit-learn
Cosine Similarity
all-MiniLM-L6-v2
Installation

Install the required Python libraries using:

python -m pip install sentence-transformers scikit-learn
How It Works

The project follows these steps:

A list of sentences is provided as input.
The pre-trained all-MiniLM-L6-v2 model is loaded.
Each sentence is converted into a numerical embedding.
The number of sentences and embedding dimension are displayed.
Cosine similarity is calculated between all sentence embeddings.
Sentence pairs with a similarity score greater than 0.5 are displayed.
The similarity score is used to identify sentences with related meanings.
Example Sentences

The project uses the following example sentences:

I like playing cricket.
I enjoy playing football.
The weather is very hot today.
The sun is shining brightly.
I am learning Python programming.
Python is used for data science.
My favorite food is pizza.
I love eating cheese pizza.
Model Used
all-MiniLM-L6-v2

The project uses the all-MiniLM-L6-v2 model from the Sentence Transformers library.

The model converts sentences into numerical vectors called embeddings. These embeddings can be compared using cosine similarity to determine how semantically related two sentences are.

The embedding dimension produced by this model is:

384
Cosine Similarity

Cosine similarity measures the similarity between two numerical vectors.

The similarity score ranges from:

-1 to 1

A higher score indicates greater semantic similarity between two sentences.

In this project, sentence pairs with a similarity score greater than:

0.5

are displayed.

Sample Output
Total number of sentences: 8
Embedding dimension: 384

--- Embeddings ---

Sentence: I like playing cricket.
Embedding: [...]

Sentence: I enjoy playing football.
Embedding: [...]

Sentence: The weather is very hot today.
Embedding: [...]

...

--- Semantic Similarity ---

Sentence 1: My favorite food is pizza.
Sentence 2: I love eating cheese pizza.
Similarity: 0.xxxx

Note: The exact embedding values and similarity scores may vary depending on the installed model and library versions.

Applications

Text embeddings and semantic similarity are commonly used in:

Semantic Search
Recommendation Systems
Document Similarity
Question Answering
Chatbots
Retrieval-Augmented Generation (RAG)
Text Clustering
Information Retrieval
Project Structure
Embedding-Model/
│
├── Embedding.py
└── README.md
How to Run

Open the project folder in VS Code and run:

python Embedding.py

The program will generate sentence embeddings and display semantically similar sentence pairs.

Conclusion

This project demonstrates how Sentence Transformers can convert natural language sentences into numerical embeddings. By using cosine similarity, the program can compare the semantic meaning of different sentences and identify sentences that are related to each other.

Author

Shalini Devi
