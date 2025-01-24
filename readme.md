# Image Captioning, Tagging, and Description with Google Gemini

This Streamlit app enables users to perform image captioning and tag extraction and describe image using the Google Generative AI service. It utilizes Streamlit for the user interface and Google's Generative AI library for image analysis.

## Access the Web Version
Explore the app [here](https://image-caption-tagger.streamlit.app/).

## Features
- Image Upload: Users can upload images in jpg, png, or jpeg formats.
- Caption Generation: The app generates captions for the uploaded image.
- Tag Extraction: Extracts hashtags related to the image.
- Image Description: Provides a brief description of the uploaded image 
- Error Handling: Validates user-entered API keys and displays specific error messages.
- Result Display: View the uploaded image alongside its generated caption and tags along with description.

## Usage
- Install dependencies:
  ```bash
   pip install -r requirements.txt
- Run the Streamlit app:
  ```bash
  streamlit run app.py
- Enter your Google Studio API key when prompted and upload an image for analysis.

## Dependencies
- Python 3.10 or above
- Streamlit
- PIL (Python Imaging Library)
- Google Generative AI library
  
## Why Use This App?
- Simplicity: Streamlined interface for effortless image analysis.
- Insightful Information: Obtain concise yet informative captions and tags for images along with brief description, thus explaining the image.
- Versatility: Useful for content creators, marketers, and anyone seeking descriptive insights from images.

This app aims to provide a user-friendly platform harnessing the capabilities of Google Gemini, making image understanding and interpretation accessible to everyone.

