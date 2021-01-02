# Convolutional Neural Networks

If github in unable to render a Jupyter notebook, copy the link of the notebook and enter into the nbviewer: https://nbviewer.jupyter.org/

These notebooks provide an introduction to the Convolutional Neural Networks (CNNs).

- Notebook 1: Motivation, CNN architecture, Fully-Connected (FC) Networks vs CNNs, Biological origin, CNN layers, CNN formalization

- Notebook 2: Convolution: Nuts & Bolts - I: Convolution operation, Single channel & multi-channel input, and multiple filters, Mathematical definition of convolution

- Notebook 3: Convolution: Nuts & Bolts - II
  
    -- Handcraft edge detector filters
    
    -- Edge detection in a single-channel image using a single filter
    
    -- Define a convolution function for multi-channel image using and multiple filters
    
    -- Edge detection in a multi-channel image using multiple filters
    
    -- Edge detection using TensorFlow's convolution function
    
- Notebook 4: Convolution: Nuts & Bolts - III

    -- Convolution: How it Changes the Size of an Image (Feature Map)

    -- Can we keep the size of the input unchanged?

    -- Padding: SAME and VALID

    -- What is the role of padding when stride > 1?

    -- Python Function for "SAME" Padding

    -- Convolution Function: Multi-Channel Input, Multiple Filters and Padding

    -- Edge Detection: Convolution with Padding

    -- Manually Define a 2D Convolution Class for Convnets
    
 - Notebook 5: Pooling
 
      -- Motivation
  
      -- Max Pooling, Average Pooling, p-norm pooling, Pooling by Multi-Layer Perceptron (MLP)
  
      -- Max Pooling: Python implementation
  
      -- Depthwise Max Pooling, implementation
  
      -- Global Average Pooling
      
      
- Notebook 6: CNN Training - I

    -- Forward Propagation (Softmax layer, Conv layer, Pooling layer)

    -- Backward Propagation (Softmax layer, Pooling layer)
    
- Notebook 7: CNN Training - II


    -- Backward Propagation (Conv layer)
    
    
- Notebook 8: Convnet Cheat Sheet

    -- Formulas for calculating the size & parameters in each layer

    -- LeNet-5 Architecture: TensorFlow implementation & detail discussion

    -- Compute memory requirement

    -- Compute multiplications & additions

    -- Larger Filters vs Smaller Filters

    -- 1 x 1 filters 

    -- How Do We Create an Optimal Convnet?


- Notebook 9: Notable Convnet Architectures - I

    -- ImageNet Large Scale Visual Recognition Challenge (ILSVRC)

    -- AlexNet (2012)

    -- ZFNet (2013)

    -- VGGNet (2014)

    -- Network in Network (NiN) 2013

    -- Incention-v1 (2014):GoogLeNet

    -- Inception-v2 (2015)

    -- Inception-v3 (2015)
    
 
- Notebook 10: Notable Convnet Architectures - II

    -- ResNet (2015)

    -- Pre-Activation ResNet (2016)

    -- Wide ResNet (2016)

    -- ResNeXt (Aggregated Residual Transformations for Deep Neural Networks) (2016)
    
    
- Notebook 11: Notable Convnet Architectures - III

    -- Inception-v4 (2016)

    -- Xception (2016)

    -- DenseNet (2017)

    -- Ensemble Method: Deep Feature Fusion (2016)

    -- Squeeze-and-Excitation Network (SENet) (2017)
    
    -- Comparison of the Notable Convnet Architectures: Bird's-Eye View

The notebooks are partially adapted from:

- Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems (2nd Edition) by Aurélien Géron

- Dive into Deep Learning by Aston Zhang, Zachary C. Lipton, Mu Li, and Alexander J. Smola

- Deep Learning by Ian Goodfellow and Yoshua Bengio and Aaron Courville

- Introduction to Deep Learning at Carnegie Mellon University https://deeplearning.cs.cmu.edu/S21/index.html





