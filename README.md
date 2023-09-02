# mSOM
mSOM (metaboliteSOM)

John Pearce

MSc Applied Bioinformatics 2023  
Cranfield University

john.pearce.041@cranfield.ac.uk  
john.pearce@virtuallychaos.com  

## Objectives
To investigate the suitability of conventional clustering methods (K-means) for metabolic time-series data; and then compare with a Self-Organizing Map (SOM). Evaluate the appropriateness of conventional measures to assess cluster quality. Investigate the use of additional biological information (common metabolic pathways) to classify types of clusters.

The workflow is illustrated below. It consists of a Conventional Processing Workflow and a SOM Clustering & Biological Connectivity Workflow. The former provides basic data validation and then performs data exploration (elbow graphs, clustering metrics, K-means and PCA). The latter provides SOM clustering (using minisom package) and Biological Connectivity (using additional data on common metabolic pathways).

<img width="1041" alt="image" src="https://github.com/jp-cranfield/mSOM/assets/127055199/7b5bdee6-9150-4964-85e7-27c7e1055d26">



