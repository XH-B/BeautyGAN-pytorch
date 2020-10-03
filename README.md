# BeautyGAN-pytorch

# Unofficial implementation of ACM MM 2018 paper: "BeautyGAN: Instance-level Facial Makeup Transfer with Deep Generative Adversarial Network"




# Train

1. downing the 'vgg_conv.pth' : https://bethgelab.org/media/uploads/pytorch_models/vgg_conv.pth

   put it at ./addings/
2. downing dataset. Dataset can be found in project page: http://colalab.org/projects/BeautyGAN, containing of all/images/ and all/segs 

   put all/images/* and all/segs/* into ./data/makeup/makeup_final/ 
3. using generate.py to generate '*.txt' eg. 'train_MAKEMIX.txt.  

   put four txt files into ./data/makeup/makeup_final/
