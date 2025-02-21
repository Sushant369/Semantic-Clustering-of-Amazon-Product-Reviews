# Semantic Clustering of Amazon Product Reviews for Summarization Report
## Overview
This project performs semantic clustering on Amazon product reviews to generate automated summarization reports. It leverages text embeddings, K-Means clustering, and LLM-based summarization to group and summarize customer feedback efficiently.

## Features
- Text Embeddings: Uses BAAI/bge-small-en-v1.5 from Hugging Face Transformers to generate high-dimensional embeddings of Amazon product reviews.
- Optimal Cluster Selection: Implements the Elbow Method with KneeLocator to determine the ideal number of clusters automatically.
- Semantic Clustering: Applies K-Means clustering on normalized embeddings to group similar reviews together.
- Automated Summarization: Uses LLaMA 4B to generate concise summaries for each cluster, making it easier to interpret key insights.

## Installation
### Prerequisites
- Python 3.8+
- Hugging Face Transformers
- Scikit-learn
- NumPy & Pandas
- Matplotlib & Seaborn
- kneelocator
- LLaMA 4B model (via Hugging Face or local setup)
