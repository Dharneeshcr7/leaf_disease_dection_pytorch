# leaf_disease_dection_pytorch

For Dataset refer plant village dataset in kaggle:
https://www.kaggle.com/datasets/tushar5harma/plant-village-dataset-updated


Overview of Model used:

   1.Extract features of the input image from efficientnetb0 model at global average pooling layer.
   2.Apply SVM on extracted features to classify the leaves based on types of diseases.
