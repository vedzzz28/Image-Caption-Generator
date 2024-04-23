# Image Caption Generator

This project implements an image caption generator system using deep learning techniques, specifically convolutional neural networks (CNNs) and long short-term memory (LSTM) networks. The system is capable of generating relevant and descriptive captions for given images, automatically describing their visual content.


## Features

- Extracts high-level visual features from images using a pre-trained CNN (ResNet50 and VGGNet16).
- Generates captions for images using a combination of CNN and LSTM networks.
- Trained on a large dataset of images and corresponding captions.
- Evaluates the performance of the generated captions using the BLEU score metric.
- Provides sample code for inference and caption generation on new images.

## Requirements

- Python 3.8 or higher
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Pillow
- NLTK
- tqdm

## Installation

1. Clone the repository:

```bash
git clone https://github.com/vedzzz28/Image-Caption-Generator.git
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Prepare your dataset of images and corresponding captions in the required format.
2. Update the file paths and dataset paths in the code according to your local setup.
3. Run the python notebook script to train the model:

```bash
python VGG.ipynb
python ResNet.ipynb
```

4. After training, you can generate captions for new images in notebook



## Dataset

This project was trained and evaluated on the Flickr8k dataset, which consists of 8,000 images and corresponding captions. However, you can use your own dataset by following the same data format and updating the file paths in the code accordingly. Link for the dataset: https://www.kaggle.com/datasets/adityajn105/flickr8k

## Project Structure

```
image-caption-generator/
├
│── images/
│   └── ... (image files)
│── captions.txt (caption file)
├── ResNet.ipynb (ResNet50)
├── VGG.ipynb (VGG16)
├── requirements.txt
└── README.md
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

