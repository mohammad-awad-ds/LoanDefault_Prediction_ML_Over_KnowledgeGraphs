
# Leveraging Knowledge Graphs for Loan Default Prediction

This repository contains a collection of Jupyter notebooks showcasing our research work on machine learning over Knowledge graph projects. Each notebook demonstrates different techniques and approaches for working with data and building models.

## Contents

1. **Normal Machine Learning on CSV**
   - Filename: `normal_ml_on_csv.ipynb`
   - Description: This notebook covers the basics of applying machine learning algorithms to a CSV dataset. It includes data preprocessing, feature selection, model training, and evaluation.
   we used the same featers and model used on our kg version of the data on csv

2. **Knowledge Graph Embedding and Machine Learning**
   - Filename: `kg_embading_and_ml.ipynb`
   - Description: This notebook delves into the integration of knowledge graph embeddings with machine learning models. It demonstrates generating embeddings, use these embeddings as features in machine learning algorithms for improved performance, and evaluating those predctions.

3. **kg preprocessing file**
   - Filename: `XAI_Project_24052024_WIP.ipynb`
   - Description: this file is showcasing turning our real world finance data into a connected knowledge graph, where we firstly turned csv into ttl rdf
      then we've converted categorical litrals into iri's by creating unique note for litrals that occures multiple times in each categorical column
     .

## Getting Started

To run these notebooks locally, follow these steps:

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/ml-xai-projects.git
   cd ml-xai-projects
   ```

2. **Set up the environment:**

   Make sure you have Python installed. It is recommended to use a virtual environment to manage dependencies.

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   Install the necessary Python packages using `pip`:

   ```sh
   pip install rdflib
      pip install pyrdftovec
   ```

4. **Run the notebook by order:**

   Launch Jupyter Notebook or JupyterLab to explore the notebooks.
order: XAI_Project_24052024_WIP, then kg_embading_and_ml, then normal_ml_on_csv
   ```sh
   jupyter notebook
   # or
   jupyter lab
   ```


Happy coding!
