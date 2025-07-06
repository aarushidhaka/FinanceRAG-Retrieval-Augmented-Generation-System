# FinanceRAG-Retrieval-Augmented-Generation-System
FinanceRAG is a domain-specific Retrieval-Augmented Generation (RAG) system designed to answer complex finance policy queries by combining semantic retrieval with Large Language Models (LLMs). Built to enhance response accuracy and domain relevance, FinanceRAG bridges the gap between pretrained LLMs and highly specialized financial datasets.

## Key features:
-  Domain-Specific Retrieval: FAISS-based vector storage for fast and efficient semantic search.
- Reranking Mechanisms: Combines Cosine Similarity and Cross-Encoder Re-ranking for relevance scoring.
- Step-Back Prompting: Improves context comprehension by leveraging hierarchical reasoning.
- Evaluation Metrics: Quantitative comparison of RAG outputs vs. standard LLM responses using relevance and faithfulness scores (mean ± SD).

## Tech Stack
- Language Models: Cohere LLM for generation and reranking
- Vector Search: FAISS
- Programming: Python (pandas, NumPy)
- Evaluation: Cosine Similarity, Cross-Encoder

## Features
- Manual Semantic Chunking for domain precision
- FAISS-based vector storage with optimized retrieval
- Multi-level reranking strategies for relevance refinement
- Quantitative evaluation (Faithfulness & Relevance Scores)

## Results
- Achieved higher faithfulness and relevance scores compared to GPT-style baselines.
- Improved accuracy of domain-specific question answering in financial policy datasets.
- Visualized results with mean ± standard deviation error bars for clear comparison.

## Future Enhancements
- Integrate active learning for continuous improvement of the retrieval pipeline.
- Support multilingual finance policy datasets.
- Deploy as an API for scalable use cases in financial analytics platforms.

# Getting Started
Clone this repository and install dependencies:
 
```bash
git clone https://github.com/aarushidhaka/FinanceRAG-Retrieval-Augmented-Generation-System.git
cd FinanceRAG-Retrieval-Augmented-Generation-System
```
```bash
pip install -r requirements.txt
```
Run the retrieval pipeline:
```bash
python main.py
```
