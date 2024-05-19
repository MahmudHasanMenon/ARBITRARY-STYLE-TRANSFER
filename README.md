# ARBITRARY-STYLE-TRANSFER
This paper focuses on arbitrary style transfer using machine learning to apply the visual style of
one image onto another while maintaining the original content. The project aims to develop an
efficient and flexible deep-learning model for style transfer, emphasizing distortion reduction. The
methodology involves dataset collection, preprocessing, and CNN-based algorithm implementation
for universal style transfer. The model is trained to learn diverse styles for transforming ordinary
images into artistic renditions. The project begins with a VGG-19 pre-trained model on ImageNet,
using the Gram matrix for style blending. To overcome VGG-19 limitations, the ResNet-34 model
is explored, and the paper details its implementation, including Gram matrix utilization, Loss and
Weights Calculations, and outcomes. The results highlight advancements in arbitrary style transfer,
addressing challenges in pre-existing models and suggesting future avenues for deep learning and
image processing exploration.

# Introduction
This report delves into the realm of computer vision and image processing, with a primary focus on
achieving nuanced and arbitrary style transfer through machine learning. The goal is to seamlessly
apply the visual style of one image to another while preserving its inherent content. The research
involves dataset collection, preprocessing, and the development of a Convolutional Neural Network
(CNN)-based algorithm for universal style transfer.
The study begins by leveraging the VGG-19 pre-trained model on ImageNet, utilizing the Gram
matrix for style blending. To address limitations, the exploration extends to the ResNet-34 model,
providing insights into its implementation, including Gram matrix utilization, Loss and Weights
Calculations, and outcomes.

# Proposing Model
This section delves into the use of VGG-19 and ResNet-34 convolutional neural network architecture.
Originally designed for image classification, these models are repurposed to convey style,
focusing on their design principles. This section compares VGG-19 and ResNet-34 considering
factors such as simplicity and computational efficiency. The Gram matrix has been highlighted for
its critical role in robust feature extraction, capturing correlations in essential feature maps for style
translation. This method introduces a different style transfer approach with adjustable stylization
levels through layered style weights. The iterative process of image updating and loss calculations
is explained. This section lays the foundation for testing, emphasizing architecture selection, warm
matrix, and innovative weight tuning for different style outputs. The following sections will review
the experimental setup, results, and discussions.

# Results
# VGG-19
![Screenshot 2024-05-19 at 3 00 07 AM](https://github.com/MahmudHasanMenon/ARBITRARY-STYLE-TRANSFER/assets/29507500/f11ebeec-3750-4dff-bba6-46ec953ccffb)

![Screenshot 2024-05-19 at 3 00 18 AM](https://github.com/MahmudHasanMenon/ARBITRARY-STYLE-TRANSFER/assets/29507500/0c5d8a34-9fae-48d1-8f5f-7460bcf2864a)

# Resnet-34
![Screenshot 2024-05-19 at 3 00 26 AM](https://github.com/MahmudHasanMenon/ARBITRARY-STYLE-TRANSFER/assets/29507500/4c4f5403-e832-4e6a-a09a-0d45e3ea4300)




