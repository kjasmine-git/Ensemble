# Ensemble
1. Introduction

The rise of deepfake technology poses growing threats to digital media integrity, making reliable detection methods essential. While deep learning offers promising solutions, training specialized detectors from scratch remains resource-intensive. Pre-trained vision models offer a potential solution by leveraging learned features from large-scale datasets.

In the present work, the aim is to propose an ensemble model for deepfake image detection with the goal to attain better performance than the existing machine learning models. Ensemble methods are learning algorithms that construct a set of classifiers and then classify new data points by taking a (weighted) vote of their predictions.

2. Dataset
   
The study utilizes a carefully curated dataset of 200 images (100 real and 100 deepfake samples) sourced from the Deepfake Image Detection dataset on Kaggle. This balanced collection contains high-quality synthetic images generated using modern GAN-based techniques alongside authentic photographs, representing diverse facial features, lighting conditions, and image resolutions. All samples were preprocessed to 224×224 resolution to meet model input requirements and normalized using each architecture's specific preprocessing pipeline. A stratified 70-30 train-test split preserves class distribution in both subsets, ensuring reliable assessment of generalization capability.


3. Models evaluated
    
ViT-Base (google)

Swin-Base (microsoft)

BEiT-Base (microsoft)

MIT-B0 (nvidia)

MobileViT-Small (apple)

ConvNeXt-Tiny (facebook)

EfficientNet-B7 (google)

