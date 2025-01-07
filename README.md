# ML-24-25-09-Creating-Text-from-images-with-OCR-API

## Project Overview
The goal of this project is to implement an OCR solution that leverages the Terrasect SDK. The C# application should load images from an input folder. Your task is to develop an application that preprocesses images by shifting, rotating, or applying other suitable transformations. After preprocessing, the application should extract text using the Terrasect API.
The quality of the extracted text depends on factors such as image quality, lighting conditions, the angle of the image, and potentially other variables, which should be assessed during the project.
The final solution must function as a console application that accepts various parameters. The output should be clear and include the extracted text from different preprocessed images. Additionally, the final result must provide a comparison of the extraction quality between various preprocessing approaches.


## Introduction
This project implements an Optical Character Recognition (OCR) solution using the Terrasect SDK in a C# console application. The application loads images from a specified input folder, preprocesses them using transformations like shifting, rotating, or other suitable methods, and then extracts text from these images using the Terrasect OCR API.

The goal is to enhance the accuracy and quality of text extraction by applying different preprocessing techniques, assessing their impact, and providing a detailed comparison of the extraction quality.

## Features

- **Image Preprocessing**: The application preprocesses images by adjusting for rotation, shifting, and other transformations to improve OCR accuracy.
- **OCR Text Extraction**: Uses the Terrasect API to extract text from the processed images.
- **Comparison of Methods**: The application compares the OCR results from various preprocessing approaches to evaluate which transformations yield the best results.
- **Console-based Application**: The solution is implemented as a simple, easy-to-use console application that accepts parameters for customization.

## Requirements

- **Terrasect SDK**: The Terrasect API is used for text extraction. You will need access to the Terrasect SDK (API key or configuration).
- **.NET SDK**: The project is built using C#. You will need the .NET SDK (version 9.0.0 or later) to build and run the project.

## Getting Started
Following tools are needed for setting up the project

1. Microsoft visual studio
2. .NET 9.0 target framework
4. Tesseract API
3. Go to the Samples folder where ConsoleApp is present. From there run the Program.cs file to run the new Spatial Learning Experiment.
### Clone the Repository

#### Parameters:
- `--input-folder`: Path to the folder containing images for OCR.
- `--output-folder`: Path where the output text files will be saved.
- `--transformation`: Type of image transformation (e.g., `rotate`, `shift`, `none`). You can experiment with different transformations for the best OCR results.

## Preprocessing Techniques

This project implements various image preprocessing techniques to improve text extraction accuracy:

- **Shifting**: Shifting the image slightly to adjust for misalignment.
- **Rotating**: Rotating the image to compensate for tilted or angled scans/photos.
- **Rescaling**: Resizing images for better clarity and optimal OCR detection.
- **Noise Reduction**: Techniques to remove background noise or distortions that may hinder OCR accuracy.


## Comparison and Results

Once the OCR process is complete, the application will generate a comparison of the quality of text extraction based on different preprocessing methods. This comparison can be used to assess which transformations lead to the best results.

The results are stored as text files in the `output-folder`, and each file corresponds to the OCR results for a specific image.

## Technologies Used

- **C#** for implementing the core logic and application.
- **Terrasect SDK** for OCR capabilities.
- **.NET SDK** for building and running the project.
- **Image Processing Techniques** (rotation, shifting, scaling, etc.) to enhance OCR accuracy.

## Acknowledgements

- **Terrasect API**: For providing the OCR SDK used in this project.
- **.NET Community**: For creating the robust .NET framework.
