# Machine Learning Projects
This repo contains ML/ deep learning projects related but not limited to patient data analysis, computer vision, natural language processing, and drug discovery.

Classify Peptides:
  The ability of peptides to bind to specific chemical species was evaluated based on published data: https://doi.org/10.1021/acsomega.2c00640
  
  Amino acid sequences were one-hot-encoded and fed into a basic LSTM model for binary classification. (80% accuracy)
  
Cell Segmentation:
  Background removal for cell segmentation using a low depth UNET model. (80% intersection over union).

Cancer Recurrence:
  Classifying cancer recurrence from high dimensional patient data: https://www.kaggle.com/datasets/dhruvlotia/differentiated-thyroid-cancer-recurrence 
  
  A support vector machine with feature importance was implemented. (98% accuracy).
  
Proliferation Topology:
  Reducing multi dimensional immunofluorescence staining on single cells treated with different quiescence-inducing treatments (doi: 10.1038/s41556-022-00860-9)
  
  Techniques used: PCA, UMAP, t-SNE, PHATE, and PaCMAP

**Portions of code in this repository were generated with the assistance of ChatGPT, an AI language model developed by OpenAI
