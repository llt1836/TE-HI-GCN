# TE-HI-GCN

The implementation of TE-HI-GCN in our paper:(The paper is under rewever.)

Lanting Li et.al "TE-HI-GCN: An Ensemble of Transfer Hierachical Graph Convolutional Networks for Disorder Diagnosis." 

# Require

Python 3.6

# Reproducing Results

## For ABIDE Datasets：

mkdir model

cd model

mkdir <fGCN/hiGCN/ehiGCN>

cd <fGCN/hiGCN/ehiGCN>

mkdir <atlas name>

1、f-GCN: python train-fGCN.py

2、HI-GCN: python train-hiGCN.py

3、E-HI-GCN: python train-ehiGCN.py

4、TE-HI-GCN: 

Train the model of Transfer learning part that you need.

load the Transfer learning part into the E-HI-GCN model

Then, python train-ehiGCN

## For ADNI Datasets：

Using the code in the folder: ADNI

Other operations are consistent with ASD
