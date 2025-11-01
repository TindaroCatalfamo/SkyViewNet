# SkyViewNet

Aerial Landscape Classification using **Convolutional Neural Networks (CNN)** and **MobileNetV2**.

## Project Structure
- `CNN_SkyView.ipynb`: Main Colab notebook  
- `outcomes/`: Contains plots and performance metrics.  
  *(Trained models are not included to keep the repository lightweight and easy to clone, as it is intended mainly for analytical and documentation purposes rather than distributing large pre-trained weights.)*

## Model Overview
- Base model: MobileNetV2 (pre-trained on ImageNet)  
- Classes: 15 aerial landscape categories  
- Training: Data augmentation applied  
- Validation & Test: Real, unaltered images  

## Performance
- Training accuracy > 90%  
- Validation accuracy ~85–88%  
- Strong generalization, minimal overfitting  

## Dataset
[Kaggle: SkyView - An Aerial Landscape Dataset](https://www.kaggle.com/datasets/ankit1743/skyview-an-aerial-landscape-dataset)
