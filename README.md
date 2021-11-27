# TE-HI-GCN

The implementation of TE-HI-GCN in our paper:

Lanting Li et.al "TE-HI-GCN: An Ensemble of Transfer Hierachical Graph Convolutional Networks for Disorder Diagnosis." 

# Require

Python 3.6

# Reproducing Results

## For ABIDE Datasets：

mkdir model

cd model

mkdir <fGCN/hiGCN/ehiGCN>  (choose a floder name that you need)

cd <fGCN/hiGCN/ehiGCN>

mkdir <atlas name>

1、f-GCN: python train-fGCN.py

2、HI-GCN: python train-hiGCN.py

3、E-HI-GCN: python train-ehiGCN.py

4、TE-HI-GCN: 

Train the model of Transfer learning part that you need.

Load the Transfer learning part into the E-HI-GCN model.

Then, python train-ehiGCN.

## For ADNI Datasets：

Using the code in the folder: ADNI.

Other operations are consistent with the ABIDE datasets.

Change "name" in these codes when you need to product results of different atlas.

Change "thr" in train-fGCN.py when you need to product results with different thresholds.
