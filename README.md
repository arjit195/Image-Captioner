# Image Captioner

This project is an **Image Captioning** tool that generates captions for images using a pre-trained transformer model. It utilizes the **BLIP** (Bootstrapped Language-Image Pre-training) model from the `Salesforce` repository to generate descriptive captions for input images.

## Features

- **Image Upload**: Allows users to upload an image through a web interface.
- **Caption Generation**: Automatically generates a textual description of the image using a pre-trained model.
- **Gradio Interface**: Uses the `Gradio` library to create a simple and interactive web UI for image captioning.

## Dependencies

- `Pillow (PIL)` – For image processing.
- `transformers` – For loading and using the BLIP model and processor.
- `gradio` – For creating a user-friendly web interface.

## Installation

To install the necessary dependencies, use the following command:

```bash
pip install Pillow transformers gradio
