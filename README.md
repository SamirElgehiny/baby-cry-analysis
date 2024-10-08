# Baby Cry Analysis for Research Paper

## Overview

Welcome to the GitHub repository dedicated to the research paper titled '**Evaluating Convolutional Neural Networks and Vision Transformers for Baby Cry Sound Analysis**' authored by Samir Ashraf, Noha S. Tawfik and Dalia Sobhy. This repository contains the code and resources used in the research, aiming to explore a more personalized approach to understanding the reasons behind a baby's cry through machine learning techniques.

## Project Structure

- `CNNmc`: Implementation of a Multi-Input Convolutional Neural Network (CNN) using Mel spectrogram and CQT spectrogram features.

- `CNNfm`: Implementation of a Multi-Input CNN using Mel spectrogram and MFCC features.

- `SVM`: Support Vector Machine (SVM) with VGG16 feature extraction for classification.

- `spectoT`: Code to preprocess audio files and extract CQT and Mel spectrograms.

- `augmentation`: Audio augmentation techniques to enhance dataset diversity.

- `ViT`: Training a Vision Transformer (ViT) from scratch on smaller datasets with specialized attention mechanisms.

## How to Use

1. **Data Preparation**: Prepare your baby cry audio dataset. The `spectoT` folder assists in extracting necessary spectrogram features.

2. **Model Selection**: Choose the appropriate model from `CNNmc`, `CNNfm`, `SVM`, or `ViT` directories for training and evaluating models.

3. **Augmentation**: Utilize the `augmentation` section to apply augmentation methods to audio files.

4. **Results and Analysis**: Analyze model performance and insights obtained for personalized infant care.

   Inside the `ViT` directory, you'll find two options for ViT models:

- **Vanilla ViT**: The Vanilla Vision Transformer model can be executed by setting `run_vanilla_vit = True` in the code.

- **Modified ViT**: The Modified Vision Transformer model, which incorporates shifted patch tokenization and locality self-attention, can be executed by setting `run_vanilla_vit = False`.

Please note that the Modified ViT has been our best-performing model in our experiments, delivering superior results.

## Research Paper

This repository aligns with the research paper '**Evaluating Convolutional Neural Networks and Vision Transformers for Baby Cry Sound Analysis**' authored by Samir Ashraf, Noha S. Tawfik and Dalia Sobhy. Please cite this repository and the paper if you find the resources helpful for your work.



