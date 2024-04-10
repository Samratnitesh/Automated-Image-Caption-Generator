# Automated Image Caption Generator

## Overview 
This project aims to develop an automated image caption generator using deep learning techniques. The system takes an input image and generates
a descriptive caption for it. 

## Features
- **Image caption Generation** : Given an input image, the system generates descriptive captions.
- **Deep Learning** : Utilizes state-of-the-art deep learning models for image understanding (**VGG16**) and natural language processing.
- **Customization** : Easily customizable for different datasets and models.
- **Evalutaion Metrics** : Includes evaluation metrics to assess the quality of generated captions.

## Setup
**1. Clone the Repository:**
```
git clone https://github.com/samratnitesh/Automated-Image-Caption-Generator.git
cd Automated-Image-Caption-Generator
```
**2. Install Dependencies:**
```
pip install -r requirements.txt
```
**3. Download Pretrained Models:**
- Download pretrained models for image understanding (CNNs, VGG16) and language generation (LSTMs).
- Ensure the models are compatible with the system architecture.

## Usage
#### 1. Prepare Data: 
- Ensure your dataset is properly formatted. Each image should be associated with one or more captions. <br>
#### 2. Train the Model:
- Train the image understanding and language generation models on your dataset. 
- Tweak hyperparameters as needed. <br>
#### 3. Generate Captions:
- Provide input images to the trained model to generate captions. Evaluate the quality of generated captions using appropriate metrics.


## Contributing
Contributions are welcome! For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
