# Segmentation-Masking
The code implements U-Net Architecture using Python 3 and the TensorFlow library for segmentation. It consists of the encoder block, decoder block and the U-Net Model.

Encoder Block: The contraction path block containing two 3x3 convolutional layers with ReLU activations, followed by a 2x2 max pooling layer.
Decoder Block: The expansive path block which upsamples the input, concatenates it with the corresponding encoder features and applies two 3x3 convolutional layers with ReLU activations.
U-Net Model: Combining the encoder and decoder blocks to define the complete U-Net architecture.
