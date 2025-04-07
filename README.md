# Network-Analysis-Project: Social Network of MOOC Users

## Project Overview

This project explores the **Social Network: MOOC User Action Dataset** from the Stanford Large Network Dataset Collection. The aim is to understand interaction patterns, user engagement, and dynamic relationships among users in a Massive Open Online Course (MOOC) environment using **network analysis** techniques.

## Objectives

- Define nodes (users, actions, interactions)
- Construct edges (relationships, weights based on interactions)
- Incorporate temporal dimensions for dynamic network analysis
- Perform exploratory data analysis (EDA) and network visualizations
- Analyze structural properties (degree centrality, clustering, paths, etc.)
- Detect communities and key influencers
- Answer research questions using metrics and visual insights

## Tools & Technologies

- **Python** (NetworkX, pandas, matplotlib, seaborn)
- **Google Colab** (for collaborative notebook-based exploration)
- **Gephi** (for complex visualizations)
- **Jupyter Notebook** (alternative development environment)

## Project Structure
network-analysis-mooc │ ├── data/ │ └── actions.csv # Raw dataset (user interactions) │ ├── notebooks/ │ └── mooc_network_analysis.ipynb # Main analysis notebook │ ├── images/ │ └── network_graphs/ # Visual outputs from EDA and network graphs │ ├── README.md └── requirements.txt

## Research Questions

- Who are the most influential users in the MOOC network?
- What patterns of interaction occur over time?
- Are there distinct communities of learners?
- How do users' activity levels change across the course timeline?
- What roles do high-degree or central users play?

## Key Metrics & Techniques

- **Degree, Betweenness, Closeness Centrality**
- **Connected Components**
- **Community Detection (e.g., Louvain Method)**
- **Temporal Network Slicing**
- **Density, Diameter, Path Length**
- **Visualization using layouts like spring, circular, etc.**

## Visualizations

- Bar charts for degree distribution
  https://github.com/SHALOM-1434/Network-Analysis-Project/commit/b856283c9bec90699bc9c5555564e44b49d37735
  
- Time series of user interactions
  https://github.com/SHALOM-1434/Network-Analysis-Project/commit/b856283c9bec90699bc9c5555564e44b49d37735
  
- Network graphs with color-coded communities
  https://github.com/SHALOM-1434/Network-Analysis-Project/commit/b856283c9bec90699bc9c5555564e44b49d37735
  
- Heatmaps for temporal activity patterns

## Dataset Source

- [Stanford Large Network Dataset Collection (SNAP)](https://snap.stanford.edu/data/)

## Getting Started

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
