# Link Prediction on LastFM Music Dataset - PyTorch Geometric

**Note:** The documentation part in the jupyter notebook is a work in progress and should be completed by the end of September 2024. 

This repository demonstrates **link prediction** using **Graph Neural Networks (GNNs)** on the **LastFM** dataset with **PyTorch Geometric**. The task focuses on **predicting potential links between users and artists in a heterogeneous bipartite graph**, where:

- **Nodes** represent users and artists.
- **Edges** represent user interactions with artists.

By applying GNN-based techniques, we aim to predict missing or future edges between users and artists, leveraging the graph's structure and node features to improve prediction accuracy.

## Objective

The main goal of this project is to:

- Explore how GNNs can be used to address the **link prediction** problem.
- Predict interactions (or links) between users and artists by utilizing the features and structure of the graph.

## Dataset

We use the **LastFM** dataset, which provides a bipartite graph of user-artist interactions:

- **Users**: Represent individuals interacting with artists.
- **Artists**: Represent music artists.
- **Interactions**: Edges between users and artists signify user activity, such as listening to or favoriting an artist.

## Methodology

We utilize **PyTorch Geometric** to:

- Construct the bipartite graph.
- Apply GNN-based approaches to predict links (edges) between nodes.
  
The GNN learns from the existing interactions and node features to infer potential or missing links in the graph.

## Disclaimer

This project was a brief exercise to understand the fundamentals of GNNs for link prediction. **This is NOT my Master thesis**. The Master thesis involves a more comprehensive study, with in-depth research and experiments based on recent academic papers. Additionally, it uses a real-world dataset from the city of Brønderslev, Denmark.

## Acknowledgments

- **PyTorch Geometric** for providing the tools to build and train GNN models.
- **LastFM** for making their dataset available for this project.
  
Feel free to explore, fork, or contribute to this repository for further learning!
