# Leveraging-Large-Vision-Models-for-Terrain-Classification-in-HiRise-Mars-Orbital-Images
### Overview
This project explores the application of large vision models for the classification of Martian terrain using HiRise orbital images. HiRise (High Resolution Imaging Science Experiment) images provide detailed views of the Martian surface, and machine learning models are employed to classify these images into different terrain types.

### Key Features:
- Utilizes state-of-the-art vision transformers (ViT, BEiT, DeiT, LeViT, and Swin) for image classification.
- Comparison of performance metrics for each model.
- Jupyter notebooks that demonstrate the training and evaluation of models on HiRise datasets.

### Repository Structure:
- Jupyter Notebooks:
  - [beit-hirise.ipynb](beit-hirise.ipynb): Implementation of BEiT for terrain classification.
  - [deit-hirise.ipynb](deit-hirise.ipynb): Implementation of DeiT (Data-efficient Image Transformer).
  - [levit-hirise.ipynb](levit-hirise.ipynb): LeViT model for classification.
  - [swinv2-hirise.ipynb](swinv2-hirise.ipynb): Application of Swin Transformer.
  - [vit-hirise.ipynb](vit-hirise.ipynb): Vision Transformer for HiRise images.
  - [Eval_HiRise.ipynb](Eval_HiRise.ipynb): Evaluation notebook for comparing model performance.
- Metrics:
  - Contains evaluation metrics in JSON and Excel formats for each model.
  
### Installation
1. Clone this repository:
```bash
git clone https://github.com/aswin7956/Mini-Project-using-Vision-Models.git
```
2. Install the required dependencies (update this based on specific libraries):
```bash
pip install -r requirements.txt
```

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
