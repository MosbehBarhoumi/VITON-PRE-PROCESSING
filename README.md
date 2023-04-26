# VITON Pre-Processing Steps

## Introduction

In this project, I have developed a pre-processing pipeline for the VITON dataset. The pipeline includes human-parsing, densepose pose-estimation, and cloth mask. The pre-processing steps are designed for practical uses and are aimed at give you a simple way to pre-process your own dataset the way VITON is processed.

## Getting Started

Before you use the notebook, please make a copy of this folder in your drive at this link: https://drive.google.com/drive/folders/1tctFFeiwkLLJymC5rS3RtLRx0YRizRbD?usp=sharing. The folder contains all pre-trained models and code fixed, migrated, and cleaned of errors. Please note that this is the first version and it is not fully automated. I will release other versions in the future.

## Usage

The code in the drive is not clean yet, but it works well. If you want to check the results of the pre-processing methods, go to the folder of that pre-processing step and see some examples. The input folder is named 'input-folder' and the output folder is 'output-folder'. To pre-process your own data, just upload it to the input folder and you will get the results in the output folder.

## Resources

I would like to mention the resources that I have used for this first try:

- Dense-pose: https://github.com/facebookresearch/detectron2
- Human-parse: https://github.com/GoGoDuck912/Self-Correction-Human-Parsing
- Pose-estimation: https://github.com/CMU-Perceptual-Computing-Lab/openpose (although in this Colab, I used a PyTorch version of OpenPose due to faster execution time)
- Cloth-mask: I developed two solutions, one using OpenCV and the other using U-2-net.

Thank you for checking out my project!

