# Hello_World_Deep_Learning
High-level introduction into practical machine learning for purposes of medical
image classification using the Tensorflow framework.

Goal:

Build a deep learning classifier to accurately differentiate between the a chest x-ray and abdominal x-ray.

Inspiration: 

Lakhani, Paras et al. “Hello World Deep Learning in Medical Imaging.” Journal of digital imaging vol. 31,3 (2018): 283-289. doi:10.1007/s10278-018-0079-6

Link to the publication: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5959832/

Dataset: 

75 images, 38 are chest X-rays, and 37 are abdominal X-rays obtained from openI, https://openi.nlm.nih.gov/, a searchable online repository of medical images from published PubMed Central articles.

Transfer learning: Inseption V3, ImageNet

Loss Function: Binary cross-entropy

Optimization algorithm: Adam optimizer

Image preprocessing: we use image data generator (Keras) which performs "on a flight" augmentation, such as rotations, translation, zoom, shearing, and flipping, just before they are fed to the network.

Model evaluation: ROC curve using Scikit learn, accuracy and loss function values
 


 
