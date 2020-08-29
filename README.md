# Adversarial-Attack-on-Fine-Tuned-Flood-Detection-Model
Implementation of FGSM (Fast Gradient Sign Method) attack on fine-tuned MobileNet architecture trained for flood detection in images.

The model was originally achieving more than 98% accuracy. After feeding it images with small pertubrations, it misclassifies images as can be seen in the code.

The code was inspired from TensorFlow's tutorial which can be found on the following link:
https://www.tensorflow.org/tutorials/generative/adversarial_fgsm

The fine-tuned model can be found here:
https://drive.google.com/file/d/1mF8NmMClUbKXYJoDdW3OYHhwiSknI5hk/view?usp=sharing
