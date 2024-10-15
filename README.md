# README for ICDAR 2024 Paper Classification

## Overview

This project classifies ICDAR 2024 conference papers using natural language processing techniques. It extracts titles and authors, preprocesses data, and categorizes documents into predefined classes, using a zero-shot classifier from HuggingFace.

## Requirements

- Python 3.x
- Libraries:
  - pandas
  - transformers
  - PyMuPDF

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AntonisGantzos/ICDAR-Paper-Classification.git
   cd ICDAR-Paper-Classification
   
## Usage
- For data configutation, execute the code and it will pull and extract the raw version of the zip file containing the pdfs automatically from github.
- Open the Jupyter Notebook in Jupyter or Google Colab.
- Install all libraries mentioned in the **Requirements** section
- Execute the cells sequentially to run the analysis.
- The classification results and visualizations will be displayed after execution.

## Notes
- Use a GPU for better performance with deep learning models.
- Adjust hyperparameters for optimal results based on your dataset.
