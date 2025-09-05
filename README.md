# Indoor/Outdoor Image Classifier

This project is a simple image classification pipeline to distinguish between indoor and outdoor scenes using deep learning. It uses FastAI and a small custom dataset, with images downloaded from Bing and DuckDuckGo. The workflow includes data collection, cleaning, model training, and evaluation.

## Live Demo

This project is published on GitHub Pages:
https://adilsiraju.github.io/indoor_outdoor_classifier_hackp/

It uses Jekyll themes for a clean and modern look.

## Hugging Face Spaces

The classifier is also deployed on Hugging Face Spaces:
https://huggingface.co/spaces/adilsiraju/Indoor_outdoor_classifier

The GitHub Pages site uses the Hugging Face API for live predictions.

## Features
- Downloads images for 'Indoor' and 'Outdoor' classes using Bing and DuckDuckGo
- Cleans and verifies images
- Trains a ResNet-based classifier using FastAI
- Evaluates model performance with confusion matrix and top losses

## Usage
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install fastai bing_image_downloader ddgs fastdownload
   ```
3. Run the notebook `indoor_outdoor_classifier.ipynb` step by step.
4. Optionally, add more images to `area_types/Indoor` and `area_types/Outdoor` for better results.

## Folder Structure
```
area_types/
    Indoor/
    Outdoor/
indoor_outdoor_classifier.ipynb
```

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
