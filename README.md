# Conversational AI with Image Recognition

This project is a conversational AI application that integrates image recognition capabilities. It uses a pre-trained model from the `transformers` library to generate responses based on user queries and images.

## Features

- Load and display images
- Send text queries along with images
- Receive AI-generated responses based on the input image and query
- GUI built with Tkinter

## Usage

1. Run the GUI application:
    ```sh
    python gui.py
    ```
2. Use the GUI to load an image, enter a query, and get a response from the AI.

## Project Structure

- `app.py`: Contains the core logic for loading the model and processing images and queries.
- `gui.py`: Implements the graphical user interface using Tkinter.

## Dependencies

- `transformers`
- `torch`
- `Pillow`
- `tkinter`



