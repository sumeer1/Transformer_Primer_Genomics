# Transformer_Primer_Genomics
 A basic tutorial for applying transformer-based models in genomics research.
This tutorial is a supplement to the manuscript by (Jesper et.al)

See the associated python [notebook](https://raw.githubusercontent.com/sumeer1/Transformer_Primer_Genomics/main/Transformer_Primer_Genomics.ipynb) for the tutorial

Analyzing DNA Sequences using Pre-Trained Transformer Models
----------------------------------------------------------------

In this Jupyter notebook, we demonstrate how pre-trained transformer models can be used to analyze DNA sequences. We use the "sentence-transformers/all-distilroberta-v1" model for generating embeddings and a Masked Language Model for predicting the probabilities of nucleotides at specific positions of the sequence.

Libraries Used
-------------------

We use the following Python libraries in this notebook:

    scanpy
    numpy
    pandas
    torch
    sklearn
    seaborn
    matplotlib
    transformers

Workflow
------------

The workflow of this notebook can be summarized as follows:

    Load a sample DNA sequence.
    Use a pre-trained transformer model to generate embeddings for the sequence.
    Visualize the embeddings using a heatmap.
    Use a Masked Language Model to predict the probabilities of nucleotides at specific positions of the sequence.
    Visualize the nucleotide probabilities using a bar plot.

Code Explanation
---------------------

The code in this notebook is divided into several cells, each with a specific purpose. The first cell imports the necessary libraries for our analysis. The second cell loads a sample DNA sequence for our analysis. The third cell generates embeddings for the DNA sequence using a pre-trained transformer model and visualizes the embeddings using a heatmap. The fourth cell uses a Masked Language Model to predict the probabilities of nucleotides at specific positions of the sequence. The final cell visualizes the nucleotide probabilities using a bar plot.

Conclusion
--------------------

This notebook demonstrates how pre-trained transformer models can be used to analyze DNA sequences. We use a pre-trained transformer model to generate embeddings for a DNA sequence and analyze the embeddings to visualize certain features of the sequence. We also use a Masked Language Model to predict the probabilities of nucleotides at specific positions of the sequence. This notebook can be used as a starting point for further analysis of DNA sequences using pre-trained transformer models.
