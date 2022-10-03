### Self-Supervised Deep Clustering for Tabular Data

Note: this is my bachelor thesis in Computer Science, Ludwig Maximilian University of Munich, Germany.

Abstract: Self-supervised learning has long had great success in the fields of computer vision and natural language processing. However, these self-learning frameworks have been little studied on tabular data sets. In this paper, we propose a technique of self-supervised learning for tabular data, where views are created using a novel augmentation method for tabular data. We then apply a simple clustering algorithm in the embedding space, which is the output of the learned backbone of the self-supervised learning framework. In experiments, we evaluate the proposed technique on several tabular data sets from different domains and compare the proposed augmentation method for tabular data with several other methods. The proposed technique shows significant optimization of clustering performance in the embedding space compared to the original data space.

Eight datasets of tabular data:
- Synthetic data
- Zelnik
- MNIST
- Pendigits
- Optdigits
- USPS
- Wine
- Mobile

Each of the dataset trained with three self-supervised learning frameworks:
- SimCLR
- SimSiam
- Barlow Twins

Several data augmentation methods applied:
- MixUp
- MixCut
- DropOut
- Masking
- Upsampling (SMOTE)

Extra experiment:
- SimCLR framework + Transformer as backbone + Masking 
