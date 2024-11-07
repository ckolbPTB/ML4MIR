# ML4MIR
Machine Learning for Medical Image Reconstruction

In the previous lectures we discussed several approaches of how deep learning can be used for image reconstruction. 
In this image reconstruction lab we are going to implement one of these approaches. 

We are going to learn:
- how to read in MR raw data
- understand the structure and parameters of MR raw data
- create an acquisition model $A$ describing our data acquisition
- carry out a standard conjugate-gradient based iterative reconstruction
- extend this reconstruction by including a neural network
- evaluate image quality

Start an interactive session on [![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ckolbPTB/ML4MIR.git/main) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ckolbPTB/ML4MIR/blob/main/image_reconstruction_lab.ipynb)
