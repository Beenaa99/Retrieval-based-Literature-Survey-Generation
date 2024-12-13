# Retrieval-based-Literature-Survey-Generation

Retrieval-based Automated Literature Survey Generation

## Project Structure

Please find the dataset used at - 
Please find our project report at - 
### `/jupyter notebooks`
Main implementation notebooks:
- `RAG_Pipeline_for_LitReviewGeneration.ipynb`: RAG-based literature survey generation
- `GraphRAG_PIpeline_Literature_Survey_Generation.ipynb`: Graph-based RAG implementation
- `BERTScore_eval.ipynb`: Evaluation using BERTScore metrics
- `RAGAS_eval.ipynb`: Evaluation using RAGAS framework

### `/evaluation results`
Results and analysis files:
- `rag_bert_eval_results.csv, graphrag_bert_eval_results.csv`: Contains for each test query:
  - Input query
  - Output response
  - Retrieved paper abstracts (context)
  - BERTScore evaluation metrics
- `graph_ragas_eval results.json`: Contains for each test query:
  - Input query
  - Output response
  - Retrieved community summaries (context)
  - RAGAS evaluation scores

## Features

- Two approaches for literature survey generation:
  - Traditional RAG using paper abstracts
  - Graph-based RAG using community detection and summarization
- Comprehensive evaluation using:
  - BERTScore: semantic similarity metrics
  - RAGAS: LLM as a judge for coherence, informativeness, citation coverage, and redundancy metrics

## Requirements

- Python 3.x
- LlamaIndex
- HuggingFace
- Sentence Transformers
- FAISS
- NetworkX
- PyTorch
- PyVis
- Transformers
- RAGAS
- BERTScore

## Getting Started

1. Clone the repository
2. Install dependencies
3. Acquire LLM API keys (This repository uses Groq and Together)
4. Run notebooks in this order:
   - Implementation notebooks first (`/jupyter notebooks/rag_implementation.ipynb` or `/jupyter notebooks/GraphRAG_PIpeline_Literature_Survey_Generation.ipynb`)
   - Evaluation notebooks second (`/jupyter notebooks/bert_evaluation.ipynb` and `/jupyter notebooks/ragas_evaluation.ipynb`)

## References
- GraphRAG implementation adapted from LlamaIndex (source: https://docs.llamaindex.ai/en/stable/examples/cookbooks/GraphRAG_v2/)

## Contact

- Ananya Prakash (ananya23@vt.edu)
- Anushka Sivakumar (anushkas01@vt.edu)
- Beenaa Salian (beenaamotiram@vt.edu)


