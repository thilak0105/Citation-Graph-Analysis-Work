# 📚 Citation Graph Analysis

Analyzing a citation network using graph theory to uncover hidden patterns, influential research papers, and collaborative structures in academia. This project builds a citation graph from dataset, applies graph algorithms like PageRank and centrality measures, and visualizes key insights.

---

## 📌 Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Visualizations](#visualizations)
- [Future Work](#future-work)


---

## Introduction :

In this project, we build and analyze a **Citation Graph**, where each node represents a research paper and each edge represents a citation from one paper to another. The analysis provides insights into:

- Most influential papers 
- Highly cited authors
- Clusters of research communities
- Trends in citation over time

Also here we have mainly concentrated on the Centralitiy of the Graph based dataset as it help us to identify the structure of the data 
---

## 📂 Dataset


The dataset contains metadata of research papers, including:
- Paper ID / Title
- Authors
- Year of publication
- List of citations
- Fields of study



---

## ✨ Features

- [x] Construct citation graph from raw data
- [x] Explore node degree, in-degree, out-degree distributions
- [x] Identify top-k influential papers using PageRank
- [x] Detect communities using graph clustering algorithms
- [x] Visualize the citation network (static and interactive)
- [x] Identify top authors by citation count
- [x] Temporal analysis of citation trends

---

## 🛠️ Tech Stack

- **Language**: Python 3.10+
- **Libraries**:
  - `NetworkX` – Graph construction and algorithms
  - `Pandas` – Data manipulation
  - `Matplotlib` / `Plotly` – Visualization
  - `Graphviz` – Grpah based atractive plots 
  - `Jupyter` – For exploratory analysis

---

## ⚙️ Installation

1. **Download the File :**
   ```bash
   Download the IYPNB file : Citation Graph Work.ipynb

   Install the required packages mention there 

   Run the code for atractive plots

## Visualizations

![closeness_centrality](https://github.com/user-attachments/assets/ad54f163-3a5b-4e5f-9fe7-5e5904120b50)
![Kernighan_Lin_Community_Detection (1)](https://github.com/user-attachments/assets/152da527-afe8-4a06-8f86-2e19db30348c)


## Future Work 

Build Deep Learning or Graph Neural Network (GNN) model for this data set and classify the paper category.

