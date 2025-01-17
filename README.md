# NSAI_KG_LLM

## Overview
This repository explores the use of **Neuro-Symbolic AI (NSAI)** for geological applications, specifically predicting copper deposit types. The project combines machine learning and symbolic reasoning to create interpretable models for ore deposit system analysis. The knowledge graph (KG) approach integrates geochemical and geological domain knowledge to enhance prediction accuracy and system interpretability.

### Highlights
- The **Jupyter Notebook** demonstrates the implementation of NSAI for predicting deposit types, focusing on **Porphyry Cu-Mo-Au** systems,and illustrates the construction of the corresponding knowledge graphs.
- The **Turtle file** (`.ttl`) contains a knowledge graph of geological features and their relationships specific to Porphyry Cu-Mo-Au deposits.

---

## Repository Structure

### Files
- **`NSAI_KG_WeilinChen_0111.ipynb`**
  - Implements NSAI techniques for predicting copper deposit types.
  - Visualizes knowledge graphs to analyze relationships in Porphyry Cu-Mo-Au systems.
  - Provides examples of integrating data-driven and knowledge-based methods.
  - Libraries used include `rdflib`, `networkx`, and `matplotlib`.

- **`geological_knowledge_graph_Cu.ttl`**
  - A Turtle RDF file encoding a **Porphyry Cu-Mo-Au Knowledge Graph**.
  - Captures relationships between geological features, alteration types, tectonic settings, minerals, and associated deposits.

- **`Porphyry Cu-Mo-Au.csv`**
  - Contains geochemical and geological data pertinent to Porphyry Cu-Mo-Au deposits.
  - Serves as a data source for constructing and validating the NSAI models.
  - Raw dataset from: U.S. Geological Survey, 2021. National geochemical database: Ore deposits - legacy data. Retrieved from https://www.usgs.gov/data/national-geochemical-database-ore-deposits-legacy-data.
    
### Additional Files
- **`LICENSE`**: MIT License for permissive use.
- **`README.md`**: Documentation for repository usage and content.

---

## Introduction
Porphyry Cu-Mo-Au deposits are among the world's most significant sources of copper, molybdenum, and gold. Predicting their occurrence requires integrating geochemical data, geological knowledge, and domain-specific rules.

This project demonstrates how **Neuro-Symbolic AI** can be applied to:
1. Encode geological knowledge into machine-readable formats (e.g., RDF knowledge graphs).
2. Predict deposit types based on geochemical data.
3. Visualize relationships in Porphyry Cu-Mo-Au systems for enhanced interpretability.

---

## Installation

### Prerequisites
Ensure the following tools and libraries are installed:
- Python 3.7 or above
- Jupyter Notebook
- Required Python libraries:
  ```bash
  pip install rdflib networkx matplotlib


**Key Revisions:**

1. **Repository Structure:**
   - Added a description for the `Porphyry Cu-Mo-Au.csv` file, detailing its contents and purpose.

2. **Installation:**
   - Provided a code block for installing the required Python libraries, enhancing clarity for users setting up the environment.

These revisions aim to offer a clearer understanding of each file's role within the repository and facilitate easier setup and usage for users.
::contentReference[oaicite:0]{index=0}
 
