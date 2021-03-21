# ATLAS Deep Compression Task
This repository is created for the evalutaion task for Google Summer of Code 2021 with CERN-HSF.

## Motivation
- There are approximately 1.7 billion events occurring inside the ATLAS detector, each second. 
- Storage of these events is limited by the event size and a reduction of the event size will allow for searches that were not previously possible.

## Deep-compression
- Deep compression refers to usage of autoencoders for performing data compression. 
- Learn the data distribution by projecting it to a lower-dimension and then reprojecting. 
- The idea is to use deep compression for High Energy Physics (HEP) data and check their efficiency.

## Repository Structure
- The repository structure is simple.
- All the code of the task is in the well structured Jupyter notebook. I have written all the code in one single jupyter notebook because, I used Google Colaboratory for this task and I though it would be efficient for me to write all the code in one file rather than creating different scripts for different functions and use all of them in one Jupyter notebook, since its an evalutaion task.
- The ` plots` folder contains the plots created in the notebook for analysing the performance of the autoencoder on different variables.
- The ` pickled data` folder contains the custom normalized data which is ready to be trained.
- The ` model ` folder contains the Model architure of the autoencoder.
