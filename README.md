## SalientLens: Unveiling the Hidden Patterns in Images
SalientLens is an image recognition tool that uses saliency mapping to highlight important areas in images for better visual interpretation. It leverages TensorFlow for deep learning and Gradio for a seamless web interface, enabling users to interact with a trained image recognition model and visualize saliency maps for model predictions.
## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Overview](#overview)
- [Endpoints](#endpoints)
- [Contact](#contact)
## Features
- Interactive Web Interface: Built with Gradio for easy deployment and user interaction.
- Saliency Mapping: Visualize important areas of an image as determined by the model, highlighting what the model focuses on when making predictions.
- TensorFlow Image Classification: Uses a trained image recognition model to predict categories of the input image.
- User-Friendly: No need for coding; simply upload an image, view the prediction, and examine the saliency map.
## Requirements
- Python 3.7+
- TensorFlow 2.0+
- Gradio 3.0+
- NumPy
- Matplotlib
- Pillow
## Installation

### Clone the repository
```bash
git clone https://github.com/yourusername/salientlens.git
cd salientlens

```
### Create a virtual environment 
```bash
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`

```
### Install the dependencies
```bash
pip install -r requirements.txt

```

### Run the application
```bash
python ir.py
```
### Launch the web interface
Once the app is running, visit http://localhost:7860 in your browser to interact with the interface.
## Usage 
SalientLens provides an intuitive web interface powered by Gradio. To get started:
- Visit the application at http://localhost:7860 after running it.
- Upload an image (e.g., an image of a cat, dog, or object).
- View the predicted class and see the corresponding saliency map highlighting areas that influenced the model's decision.
### Example Input
- Image of an animal, object, or scene to classify.
- Supported formats: PNG, JPG, JPEG, etc.
### Example Output
- Predicted Class: "Cat" or "Dog" (depends on the trained model)
- Saliency Map: A heatmap displaying which parts of the image were most important in the model's decision-making process.

## Overview
### Upload Page (Gradio Web Interface)
The Gradio interface is designed for simplicity. You upload an image, and the tool gives you predictions along with saliency maps that show which parts of the image are most influential for classification.

![image](https://github.com/user-attachments/assets/943a8756-ab65-4353-a3cf-7642d7ff41b0)

### Results Page (Saliency Map Visualization)
The saliency map visualizes the areas of the image the model deems most important for prediction. This helps users understand which features the model is focusing on, improving transparency and trust in AI models.

![image](https://github.com/user-attachments/assets/5ddd1205-e475-4e12-afe0-3c05ba130517)
![image](https://github.com/user-attachments/assets/78077ca5-6b3a-4f61-9af4-6895673a7839)


## Endpoints

### Web Interface
- Input: Image file upload (JPG, PNG, etc.)
- Output: Predicted class and corresponding saliency map.

### Example Requests
To interact with the web interface:
- Upload an image.
- View the predicted class and saliency map.

## Contact
For any questions or inquiries, please contact the project maintainer:
- Name: Shreya Garg
- Email: shreyagarg754@gmail.com
- GitHub: Itsshreyagarg

