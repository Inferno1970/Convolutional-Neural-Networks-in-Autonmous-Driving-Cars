# FCN8s Semantic Segmentation

## Project Overview

This project involves training and evaluating an FCN8s (Fully Convolutional Network) model for semantic segmentation using the CamVid dataset. The goal is to segment images into different classes such as roads, vehicles, pedestrians, etc. The model is based on a VGG16 backbone and is evaluated using metrics such as pixel accuracy and Mean Intersection over Union (Mean IoU).

## Features

- **Training**: Train the FCN8s model on the CamVid dataset.
- **Evaluation**: Evaluate the model's performance using pixel accuracy and Mean IoU metrics.
- **Inference**: Generate and visualize semantic segmentation predictions on test images.
- **Visualization**: Compare predictions with ground truth images.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Training](#training)
  - [Evaluation](#evaluation)
  - [Inference](#inference)
  - [Visualization](#visualization)
- [File Structure](#file-structure)
- [Notes](#notes)

## Installation

To run this project, you need to have Python and the required packages installed. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fcn8s-semantic-segmentation.git
   cd fcn8s-semantic-segmentation
