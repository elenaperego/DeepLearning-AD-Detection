# Deep Learning methods for Alzheimer’s Disease detection

## Dataset
The dataset used in this study consists of T1-Weight MRI images as the biomarker and as the training dataset for the before-mentioned models. These images were collected from the Alzheimer’s Disease Neuroimaging Initiative (ADNI), and pre-processed by Professor Jia Guo to label the data as Alzheimer’s Disease (AD) or Cognitive Normal (CN). The given pre-processed dataset shape was (182, 218, 182). The data has been split into training, testing and validation datasets following 60% (370 AD & 421 CN), 20% (131 AD & 129 CN) and 20% (127 AD & 126 CN) of the total dataset respectively.
Additionally, further pre-processing entailed the down sampling of the images to optimize computational efficiency at the expense of compromising accuracy. Different down sampling parameters were tested (1.5; 2 and 2.5) with 1.5 providing the optimal trade-off. Similarly, batch normalization was implemented to stabilize and speed the training of the artificial neural network.

## Models
- 3D VGG-16 and VGG-19
- 2D VGG-16 and VGG-19
- ResNet-18
- Swin Transformer
