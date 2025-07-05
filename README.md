# Neural Style Transfer

This project implements **Neural Style Transfer** using TensorFlow and the pre-trained **VGG19** model. It blends the content of one image with the style of another to generate a new stylized image.

## Features

- Uses VGG19 to extract content and style features
- Computes content and style loss using selected convolutional layers
- Optimizes a generated image to match content and style
- Includes total variation loss for smoother results

## Requirements

Install dependencies:

```bash
pip install tensorflow numpy matplotlib pillow
```

## How It Works

1. Load and preprocess content and style images  
2. Extract features using VGG19  
3. Compute content and style losses (using Gram matrices for style)  
4. Use gradient descent to update the generated image  

## Output

The final image combines the content structure with the style patterns.
