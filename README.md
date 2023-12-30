# Knowledge Graph-Based Text Clustering Project

## Project Overview

The Knowledge Graph-Based Text Clustering project aims to build a knowledge graph from the provided text data and perform clustering based on the knowledge graph. In this project, Natural Language Processing (NLP) techniques are employed to identify subjects, objects, and relations within the text. Clustering is then performed using both K-means and DBSCAN algorithms. Additionally, tokenization with GPT and BERT tokenizers is explored, and K-means clustering is applied on the resulting tokens.

## Key Components

### 1. Text Processing with NLP

- **Subject-Object-Relation Extraction:**
  - NLP techniques are utilized to extract subjects, objects, and relations from the text data.
  - The target variable (last column) is excluded during the knowledge graph creation.

### 2. Knowledge Graph Construction

- **Graph Representation:**
  - The extracted subjects, objects, and relations form the nodes and edges of the knowledge graph.

### 3. Clustering Algorithms

#### 3.1 K-means Clustering

- **Tokenization:**
  - GPT and BERT tokenizers are applied to the text.
  - Tokens are used as features for K-means clustering.

- **Knowledge Graph Clustering:**
  - K-means clustering is performed directly on the knowledge graph nodes.

#### 3.2 DBSCAN Clustering

- **Density-Based Clustering:**
  - DBSCAN is employed to cluster data points based on density.

  
### 5. Future Enhancements

- **Integration with GPT and BERT Embeddings:**
  - Explore the use of embeddings from GPT and BERT models for improved clustering.
  
- **Optimization:**
  - Fine-tune clustering algorithms and parameters for better performance.
  
## Technologies Used

- NLP Libraries (spaCy, NLTK)
- Graph Representation (NetworkX)
- Clustering Algorithms (K-means, DBSCAN)
- Tokenization (GPT, BERT)

## How to Run

1. Install the required dependencies specified in the project's environment.
2. Execute the main script for text processing, knowledge graph construction, and clustering.


