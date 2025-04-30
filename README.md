# 🔍 Source Code Analysis using OpenAI Embeddings

This project demonstrates how to analyze, embed, cluster, and visualize Python source code files using the OpenAI Embeddings API. It helps understand code similarity by transforming code into vectors and applying machine learning techniques.

## 📁 Project Structure
- `Source_Code_Analysis_OpenAI.ipynb` - Jupyter notebook that performs the entire analysis pipeline.
- `source_code/` *(optional)* - Directory containing the Python files to be analyzed.

## 🚀 Features
- Preprocesses Python source code (removing comments and docstrings).
- Generates vector embeddings using `text-embedding-ada-002`.
- Applies dimensionality reduction (PCA or t-SNE).
- Clusters the code using KMeans.
- Visualizes the clusters in 2D space.

## 🛠️ Requirements
- Python 3.7+
- Jupyter Notebook
- OpenAI Python SDK
- scikit-learn
- matplotlib
- numpy
- tqdm

Install dependencies:
```bash
pip install openai scikit-learn matplotlib numpy tqdm
