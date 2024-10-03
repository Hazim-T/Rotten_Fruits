# 🍎🍌 Rotten Fruit Classification - Image Recognition Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Setup Instructions](#setup-instructions)

---

## Project Overview

This project aims to identify **rotten fruits** using **image recognition** techniques. The goal 
is to classify fruit images into categories such as fresh and rotten. This can have real-world 
applications in industries like agriculture and retail, where identifying spoiled produce efficiently 
is important.

---

## Features:
- Uses **Convolutional Neural Networks (CNNs)** for image classification.
- Uses transfer learning to improve model accuracy.
- Data preprocessing includes image augmentation (rotation, scaling, etc.) to improve model robustness.
- Model is trained and tested on a dataset of various fruits in both fresh and rotten conditions.
- Built with Pytorch.

---

## Project Structure

- **data/fruits**: Contains the training and testing datasets of fruits (fresh and rotten).
  - `train/`: Training images, labeled as fresh or rotten followed by the fruit name.
  - `valid/`: Test images for evaluation, same format as the training images.

- **models/**: Pre-trained models saved after training.

- **notebooks/**: Jupyter notebooks used for data exploration and initial model prototyping.

- **src/**: Source code directory.
  - `utils.py`: Helper functions for the project.

- **README.md**: Documentation file (you’re reading it now!).

---

## Setup Instructions

### 1. Clone the repository:

```bash
git clone https://github.com/Hazim-T/Rotten_Fruits
cd Rotten_Fruits
```

### 2. Install required packages:
```bash
pip install -r requirements.txt
```
