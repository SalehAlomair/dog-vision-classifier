# Dog Vision Classifier 🐕

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16DG8xRCfVJeg907qYEvEkDrv8Cqcwwqj)

A deep learning project that can identify 120 different dog breeds from images. This was my first real dive into computer vision and neural networks as part of Daniel Bourke's Zero to Mastery Data Science course.

## Quick Start

Want to try it out right away? Open the notebook in [Google Colab](https://colab.research.google.com/drive/16DG8xRCfVJeg907qYEvEkDrv8Cqcwwqj) (I personally suggest that)
## What it does?

Upload a photo of any dog and the model will predict which of the 120 breeds it thinks the dog is. I used transfer learning with TensorFlow to build on top of pre-trained models rather than starting from scratch.

## Dataset

The project uses the Stanford Dogs Dataset, which contains images of 120 breeds of dogs from around the world. Each breed has roughly 150 images for training.

## Tech Stack

- **TensorFlow 2.x** - Main framework for building and training the model
- **Transfer Learning** - Used pre-trained models as a starting point
- **Python** - All the coding and data preprocessing  
- **Jupyter Notebooks** - For experimenting and documenting the process

## What I learned

This project was a great introduction to:
- How transfer learning can save tons of time and computational resources
- Working with image data and preprocessing techniques
- Model evaluation metrics for classification problems
- The importance of data augmentation when working with limited datasets

## Results

The final model achieved decent accuracy on the test set, though it definitely struggles with some breeds that look very similar (looking at you, Golden Retriever vs. Labrador mixes).

## Running the Code

1. Clone this repo
2. Install the required dependencies (TensorFlow, NumPy, Matplotlib, etc.)
3. Download the Stanford Dogs Dataset 
4. Run through the notebook step by step

Note: Training takes a while even with transfer learning, so patience is key!

## Future Improvements

- Add data augmentation to improve performance on similar-looking breeds
- Try different pre-trained models as base layers
- Build a simple web interface for easier testing
- Add confidence scores to predictions

## Acknowledgments

Big thanks to Daniel Bourke and the ZTM community for the excellent course content. The hands-on approach really helped everything click.

---

*This was a learning project, so the code probably isn't production-ready, but it was a ton of fun to build!*
