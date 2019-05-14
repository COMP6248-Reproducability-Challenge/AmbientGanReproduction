# AmbientGanReproduction

As part of the International Conference on Learning Representations reproducibility challenge we attempted to reproduce some of the experiments in [AmbientGAN: Generative models from lossy measurements](https://openreview.net/pdf?id=Hy7fDog0b) ; a twist on the traditional baseline generative adversarial network where it is assumed that the underlying state vector is not directly observed-- instead the model must learn from images with various noise transformations applied.

In this Git we reproduce the work in the Ambient paper for block pixel using the MNIST. To do so, we follow the paper in creating baseline GAN models. One that ignores that any transformation has taken place, and another that makes use of inverse transformations, shown below. 


![alt text](https://github.com/COMP6248-Reproducability-Challenge/AmbientGanReproduction/blob/master/model_flow.png "Logo Title Text 1")


#Files 

## BASELINE_GAN.ipynb 

Contains the code for Baseline GAN Experiments

## IgnoreGan.ipynb

Contains the code for ignore model Experiments 

## AmbientGan.ipynb

Contains the code for Ambient model Experiments 

# Results 

Our reproduced results confirm that the ambient approach training on noisy-images indeed gives improvement over GAN methods that do not account for the noise as well as baseline GANs trained after de-noising approaches.

![alt text](https://github.com/COMP6248-Reproducability-Challenge/AmbientGanReproduction/blob/master/model_comparison.pdf "Click me to see the graphed results ")
