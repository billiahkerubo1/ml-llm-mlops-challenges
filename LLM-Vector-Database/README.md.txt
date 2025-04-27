# Part 2: LLM & Vector Database Challenge

---

##  Problem Statement

This part involves creating a **document processing pipeline** and integrating **Large Language Models (LLMs)** to process product reviews. The key tasks include extracting key information, generating embeddings, implementing semantic search, applying an LLM for summarization and Q&A, and conducting sentiment analysis.

---

##  Files Included

- `part2-solution.ipynb` — Jupyter Notebook containing the full code.
- `part2-report.pdf`) — Detailed report of methodology, insights, and results.

---

##  Challenge Breakdown

### 1. Document Processing Pipeline 

- **Extract Key Information from Reviews**: 
  - Build a pipeline to parse product reviews and extract key insights (e.g., product features, issues, ratings).
  
- **Generate Embeddings for Each Review**: 
  - Use an appropriate technique (e.g., BERT, RoBERTa, or sentence transformers) to generate embeddings for each review.
  
- **Store and Retrieve Reviews Using Semantic Similarity**: 
  - Implement a system that stores the generated embeddings and can retrieve reviews based on semantic similarity (e.g., using cosine similarity or FAISS).

### 2. LLM Application 

- **Product Performance Summarization**: 
  - Use a Large Language Model (LLM) like OpenAI's API or Hugging Face models to **generate concise summaries** of product performance by category based on review data.

- **Q&A System Development**: 
  - Implement a **Q&A system** where users can ask specific questions about products (e.g., "What are the common issues with Product X?") and receive accurate answers from the review data.

- **Feature Identification**: 
  - Use the LLM to **identify common praised features and issues** across different product categories.

### 3. Sentiment Analysis & Classification 

- **Sentiment Detection**: 
  - Implement a sentiment classification system that can detect sentiment in product reviews (e.g., positive, neutral, negative).

- **Compare Sentiment with Provided Labels**: 
  - Compare your sentiment classifier’s results with the provided sentiment labels and analyze accuracy.

- **Sentiment Trend Dashboard**: 
  - Create a **visualization dashboard** to show sentiment trends over time and across different product categories (e.g., using line graphs, bar charts, or heatmaps).

---

##  How to Run

1. Open `part2-solution.ipynb` in Jupyter Notebook.
2. Run all cells sequentially.

Requirements:
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- transformers (for LLMs)
- FAISS (for semantic search)
