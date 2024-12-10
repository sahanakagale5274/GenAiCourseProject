
# Denoising Diffusion Implicit Models (DDIM)

## **Overview**
This project implements Denoising Diffusion Implicit Models (DDIM) to generate images of flowers using the Oxford Flowers 102 dataset. Diffusion models work by training a neural network to denoise images, gradually transforming pure noise into structured outputs.  

## **Steps Implemented**
1. **Data Preparation**: 
   - Loaded and preprocessed the Oxford Flowers 102 dataset.
   - Images were resized to 64x64 pixels and normalized.

2. **Model Architecture**:
   - Used a U-Net-like structure with multi-scale processing.
   - Incorporated embedding layers for time-step encoding.

3. **Training**:
   - Trained the model using TensorFlow and Keras with a batch size of 64.
   - Optimized with the Adam optimizer and exponential moving average (EMA).

4. **Image Generation**:
   - Generated high-quality flower images by iteratively denoising random noise.

## **Key Features**
- Simple and modular implementation of DDIM.
- Uses minimal compute resources while delivering reasonable results.

## **How to Run**
1. Install dependencies: `tensorflow`, `tensorflow_datasets`, `keras`, and `matplotlib`.
2. Execute the notebook to train the model and generate images.
