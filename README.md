# Monet Style Transfer with CycleGAN

This notebook implements a CycleGAN model using PyTorch to transform real-world photos into Monet-style paintings. The dataset is downloaded from the Kaggle competition **"I'm Something of a Painter Myself"**.

Data from: https://www.kaggle.com/competitions/gan-getting-started

I will:
- Download the dataset using Kaggle API
- Load Monet and photo images
- Define the CycleGAN architecture (Generators and Discriminators)
- Train the model with adversarial and cycle-consistency loss
- Generate Monet-style outputs
