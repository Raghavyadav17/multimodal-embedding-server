# Multimodal Embedding Server

This repository contains a FastAPI server that serves multimodal embeddings. The server processes text, image, audio, and video data to generate embeddings using HuggingFace models like MIT-B0 or ResNet-50.

## Features

- **Text Embedding**: Generate embeddings from text using pre-trained models.
- **Image Embedding**: Generate embeddings from images using Vision Transformers or CNN models.
- **Audio & Video Embedding**: Endpoints available for processing audio and video (currently under development).

## Setup and Installation

Follow the steps below to set up the server on your local machine.

### Install Dependencies 
To install the required dependencies, use pip:
```bash
pip install -r requirements.txt
```
This will install the following dependencies:

FastAPI: The web framework to build the API server.

Uvicorn: ASGI server to run the FastAPI application.

Torch: PyTorch, a framework for deep learning models.

Transformers: Hugging Face’s library for pre-trained models like MIT-B0 and ResNet-50.

Pillow: Python Imaging Library (PIL) for image processing.

NumPy: Fundamental package for scientific computing.

Requests: For making HTTP requests (e.g., for fetching external resources).

OpenCV: For video processing.


