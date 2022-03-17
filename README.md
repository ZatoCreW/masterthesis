# Master Thesis
Work in progress... 
## Problem Statement
Bicing is Barcelona's public cycling system, equipped with several parking lots and bikes in them to be used by subscribers of this service. One of the main issues with the service is getting to a parking lot without any available bicycles or trying to park in a lot without any free slots. I intend to predict in advance these situations which could be used to improve the service management. Ideally, I would like to solve this problem using Graph Neural Networks but simpler models will also be tried out.
## Dataset
Both taken from Barcelona's open data portal:
- [Bicing stations](https://opendata-ajuntament.barcelona.cat/data/en/dataset/bicing) 
- [Bicing usage](https://opendata-ajuntament.barcelona.cat/data/en/dataset/us-del-servei-bicing)

Datasets contain records (5min spans) of bicycles currently being used in the city and slots and bicycles available in each of the parking lots. 
## Useful References
Probably useful materials:
- [A Gentle Intro to GNNs](https://distill.pub/2021/gnn-intro/): by Google researchers
- [Crash Course on GNNs](https://gnn.seas.upenn.edu/): by UPenn
- [GNN's for Traffic Forecasting: A Survey](https://arxiv.org/pdf/2101.11174.pdf): nice review of models used un traffic forecasting
- [BD for Traffic Estimation and Prediction: Data and Tools](https://arxiv.org/pdf/2103.11824.pdf): nice review of datasets used in traffic prediction
- [Bike Flow Prediction with multi-GCN](https://arxiv.org/pdf/1807.10934.pdf): very much relevant, describes different tasks that can be done and proposes methods for creating a GNN structure from a bike sharing system with stations.

## Draft Notebook
[Colab Notebook](https://colab.research.google.com/drive/17Ocn0rekE28NoKE5dWPv_fk7LQdD-Yq1?usp=sharing) if you want to see my progress
