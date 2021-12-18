# CPS843FinalProject
Repository for the code that was implemented or used in our final project for CPS843. This repo includes the code for both the feature-based approach to the image stitching task as well as the repo provided by paper authors for the unsupervised deep learning approach. 

The two sub-directories for this project consist of the two approaches that were explored throughout our report. The approaches being a classical feature-based approach and an 
unsupervised deep learning approach for the image stitching task. The code presented in unsupervised deep learning directory is simply a copy of the implementation that was cited 
in the paper and provided with the paper, "Unsupervised Deep Image Stitching: Reconstructing Stitched Features to Images". The original repo for this project can be found here: 
https://github.com/nie-lang/UnsupervisedDeepImageStitching and the original paper can be found here:https://arxiv.org/pdf/2106.12859.pdf.

All code was implemented using python and the classical approach including the stitching experimentation done with it were written in Jupyter notebooks. There is a separate 
notebook available for each image pair which we have stitched using the classical approach. These notebooks can be viewed to see results as well as can be executed directly in Google Colab. The related results for the deep learning approach is present in its sub-directory 
under the image-reconstruction directory.

Abstract:The image stitching process and the components of image stitching algorithms are topics that have been around for a long time in the field of computer vision. Key 
components of image stitching algorithms such as feature detection for point based matching and robust estimation (i.e., RANSAC) for match refinement are well researched and 
established topics. While these topics have advanced throughout the years, they have not seen much advancement in recent years or as much advancement as other areas of computer 
vision (e.g., Object Detection/Recognition) have with the growth of deep learning concepts such as Convolutional Neural Networks (CNNs). Due to this, the classical image stitching 
process is heavily dependent on the quality of feature detection and thus, the image stitching process can be susceptible to poor performance when few features are present, this 
issue cannot be solved with a classical approach to image stitching. Thus, the question that arises is how can these new state-of-the-art deep learning models be applied to the 
image stitching process and how do the two approaches compare? The purpose of this paper is to analyze two approaches to the image stitching process one which follows a classical 
perspective using feature detection and another which uses an unsupervised deep learning approach. The method used for the classical approach is pulled from multiple papers to 
provide an exploration of the most common approach to image stitching while the deep learning method is pulled from a recent paper, Unsupervised Deep Image Stitching: 
Reconstructing Stitched Features to Images [1]. The goal of this exploration is to provide a general understanding of the two different approaches as well as compare the results 
produced by the two models to determine the significance of the use of deep learning on image stitching. 
