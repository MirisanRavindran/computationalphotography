https://youtu.be/D28VTIDo77c


# Computational Photography

## Project Overview

This project focuses on various computational photography techniques implemented in a web service that allows users to edit their images directly on their computer. The application offers tools for cropping, applying filters, and converting images to grayscale. Additionally, the project includes a machine learning component for traffic sign recognition and vehicle type classification.

## Features

### Cropping Tool

The cropping tool is designed to allow users to select and crop any image from their computer. Key features include:

- **Aspect Ratio Selection**: Users can choose from multiple predefined aspect ratios (e.g., 1:1, 4:3, 16:9) to maintain the desired shape while cropping. The tool ensures that the selected aspect ratio is preserved regardless of how the cropping window is resized.
- **Freeform Cropping**: Users can also opt for a freeform mode, which allows them to adjust the cropping window to any shape or size without being constrained by fixed aspect ratios.
- **Preview Functionality**: After selecting the desired crop area, users can preview the cropped image to ensure it meets their requirements.
- **Image Resolution Maintenance**: The tool tracks each pixel in the original image and uses image interpolation techniques to maintain the image resolution even when zoomed in on a specific portion of the image.
- **Download Option**: Once satisfied with the crop, users can download the cropped image to their computer.

### Filters

The filtering tool provides a simple yet powerful way to apply Gaussian blur to any selected image. Features include:

- **Image Selection**: Users can choose any image from their computer to apply the filter.
- **Gaussian Blur Application**: The tool applies a Gaussian blur effect to the selected image, softening the image and reducing noise.
- **Download Option**: Users can download the blurred image to their computer for further use.

### Grayscale Conversion

The grayscale conversion tool allows users to convert any selected image to grayscale. Features include:

- **Image Selection**: Users can choose any image from their computer to convert.
- **Grayscale Conversion**: The tool processes the image to remove color information, resulting in a grayscale version of the image.
- **Download Option**: Users can download the grayscale image to their computer.

## Machine Learning Components

### Traffic Sign Recognition

The project includes a machine learning model for traffic sign recognition. This component is designed to assist in various applications related to road safety by recognizing and interpreting traffic signs. Key features include:

- **Image Upload**: Users can upload any image containing a traffic sign.
- **Prediction**: The model predicts the type of traffic sign present in the uploaded image. It can recognize various signs such as speed limits, stop signs, and yield signs.
- **Training Data**: The model was trained on a dataset with 58 classes of traffic signs, each class containing approximately 120 images. Preprocessing techniques such as grayscale conversion, histogram equalization, and normalization were used to enhance the images for better model performance.
- **Accuracy**: The model achieved an accuracy of 98.80% on the validation set after 10 epochs of training, indicating high reliability in classifying traffic signs correctly.

### Vehicle Type Classification

In addition to traffic sign recognition, the project includes a machine learning model for vehicle type classification. This component categorizes images of vehicles into different types, enhancing the overall functionality of the application. Key features include:

- **Image Upload**: Users can upload images of vehicles.
- **Prediction**: The model classifies the uploaded vehicle image into one of several categories, such as cars, trucks, buses, and motorcycles.
- **Training Data**: The model was trained on a dataset sourced from Kaggle, containing diverse images of vehicles categorized into four classes. Preprocessing techniques similar to those used in traffic sign recognition were applied.
- **Accuracy**: The model's accuracy improved from an initial 35.5% to 89.3% after 30 epochs of training, demonstrating significant improvement and reliable performance in vehicle classification.

## Installation and Setup

1. **Clone the Repository**: Clone the repository to your local machine using the command:
   ```sh
   git clone <repository-url>
   ```
2. **Install Dependencies**: Navigate to the project directory and install the required dependencies:
   ```sh
   npm install
   ```
3. **Run the Application**: Start the application using the provided instructions:
   ```sh
   npm start
   ```
4. **Access the Web Interface**: Open your web browser and navigate to `http://localhost:8080` to access the application and utilize the cropping, filtering, grayscale conversion, and machine learning tools.

## Conclusion

The computational photography project demonstrates the integration of image processing tools and machine learning to create a versatile web service for image editing and analysis. The project showcases advanced techniques in both fields, providing users with powerful tools for their image-related needs.



