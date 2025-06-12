# Ensemble

The study utilizes a carefully curated dataset of 200 images (100 real and 100 deepfake samples) sourced from the Deepfake Image Detection dataset on Kaggle. This balanced collection contains high-quality synthetic images generated using modern GAN-based techniques alongside authentic photographs, representing diverse facial features, lighting conditions, and image resolutions. All samples were preprocessed to 224×224 resolution to meet model input requirements and normalized using each architecture's specific preprocessing pipeline. A stratified 70-30 train-test split preserves class distribution in both subsets, ensuring reliable assessment of generalization capability.
 Pre-trained Models Evaluated

Model
Type
Params
Pretraining
ViT-Base (google)
Pure Transformer
86M
ImageNet-21k
Swin-Base (microsoft)
Hierarchical Transformer
88M
ImageNet-1k
BEiT-Base (microsoft)
Masked Image Modeling
86M
ImageNet-22k
MIT-B0 (nvidia)
Lightweight CNN
3.4M
ImageNet-1k
MobileViT-Small (apple)
Mobile-Optimized Hybrid
5.6M
ImageNet-1k
ConvNeXt-Tiny (facebook)
Modernized CNN
28M
ImageNet-1k
EfficientNet-B7 (google)
Scaled CNN
66M
ImageNet-1k

