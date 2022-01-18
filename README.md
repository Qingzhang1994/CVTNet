# End-to-end large-scale image retrieval network with convolution and vision transformers
This repository contains the PyTorch implementation of our paper: "End-to-end large-scale image retrieval network with convolution and vision transformers" Qing Zhang Feilong Bao Xiangdong Su Weihua Wang Guanglai Gao

# Requirements
•	Python 3  
•	PyTorch tested on 1.3.0 - 1.5.1, torchvision 0.5+  
•	opencv-python (cv2) tested on 3.3.0.10  
•	TensorBoard tested on 2.0.0+  
•	numpy  
•	tqdm  

# dataset

Downloads the GL18 dataset for training https://www.kaggle.com/google/google-landmarks-dataset  
Downloads the Oxford dataset, Paris dataset, and R-1M distractor dataset for testing http://cmp.felk.cvut.cz/revisitop/

# Training

python3 -m cvtnet.examples.train

# Test

python3 -m cvtnet.examples.test
