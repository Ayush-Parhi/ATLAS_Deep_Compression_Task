# ATLAS Deep Compression Task
This repository is created for the evalutaion task for Google Summer of Code 2021 with CERN-HSF.

## Motivation
- There are approximately 1.7 billion events occurring inside the ATLAS detector, each second. 
- Storage of these events is limited by the event size and a reduction of the event size will allow for searches that were not previously possible.

## Deep-compression
- Deep compression refers to usage of autoencoders for performing data compression. 
- Learn the data distribution by projecting it to a lower-dimension and then reprojecting. 
- The idea is to use deep compression for High Energy Physics (HEP) data and check their efficiency.
