# mSOM
mSOM (metaboliteSOM)

John Pearce

MSc Applied Bioinformatics 2023  
Cranfield University

john.pearce.041@cranfield.ac.uk  
john.pearce@virtuallychaos.com  

## Objectives
* Investigate the suitability of conventional clustering methods (K-means) for metabolic time-series data
* Apply and optimise SOMs for the same data set
* Compare K-means with a Self-Organizing Map (SOM)
* Evaluate the appropriateness of conventional measures to assess cluster quality
* Investigate the use of additional biological information (common metabolic pathways) to classify types of clusters.

## Workflow
The workflow is illustrated below. It consists of a Conventional Processing Workflow and a SOM Clustering & Biological Connectivity Workflow. The former provides basic data validation and then performs data exploration (elbow graphs, clustering metrics, K-means and PCA). The latter provides SOM clustering (using minisom package) and Biological Connectivity (using additional data on common metabolic pathways).

<img width="1041" alt="image" src="https://github.com/jp-cranfield/mSOM/assets/127055199/7b5bdee6-9150-4964-85e7-27c7e1055d26">

## Data sets
A time-series metabolic data set (Arabidopis thaliana) was obtained from Kim, Jae Kwang & Cho, Myoung & Baek, Hyung-Jin & Ryu, Tae & Yu, Chang & Kim, Myong & Fukusaki, Eiichiro & Kobayashi, Akio. (2007). Analysis of metabolite profile data using batch-learning self-organizing maps. Journal of Plant Biology. 50. 517-521. 10.1007/BF03030693. 

Additional biological data (common metabolic pathways) was obtained (for Arabidopsis thaliana) from the BioCyC database using the PythonCyC package.

A **Data** folder contains the required data files. Including the additional biological data if you don't want to install and run * *Pathway Tools* * (part of the BioCyC server).

## Jupyter Notebooks
The Conevntional Processing Workflow is implemented in * *DataExploration.ipny* * and * * Advanced KmeansAnalysis.ipny* *

The SOM clustering and Biological Connectivity workflow is implemented in * *SOMClustering.ipny* *, * *CommonPathwayData.ipny* * and * *BiologicalConnectivity.ipny* *



