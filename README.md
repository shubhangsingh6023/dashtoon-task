## Image Style Transfer and Colorization

This project uses Neural Style Transfer using a pre-trained VGG19 model and Grayscale Image Colorization using Generative Adversarial Networks (GANs) with a UNet-like generator structure for artistic image stylization and realistic colorization.

### Features

1. **Neural Style Transfer with VGG19:**
   - Utilizes a pre-trained VGG19 neural network for extracting content and style features from input images.
   - Employs iterative optimization to update a target image based on content and style losses until the desired artistic style is achieved.

2. **Grayscale Image Colorization with GANs:**
   - Utilizes Generative Adversarial Networks (GANs) for adding color to grayscale (B/W) images.
   - The generator model follows a UNet-like architecture, including skip connections for enhanced feature propagation.
