# Self-Supervised Anomaly Detection in CT Scans

## Introduction & Motivation
This project utilizes autoencoders to significantly enhance anomaly detection in CT scan diagnostics. By automating the anomaly detection, this system aims to facilitate the diagnostic decision-making process, address the critical need for heightened accuracy in an overwhelmed healthcare system, and provide radiologists with sophisticated, automated tools to process anomalies detection.

## Project Goals
- Improve medical diagnosis technology by increasing its precision while optimizing available medical resources.
- Develop an automated system for detecting anomalies in CT-scan images, improving medical diagnosis and management of health resources.

## Overview of the Proposed Framework
The framework consists of an Encoding and Decoding process using ConvNets and DeConvNets, respectively. The architecture aims to reconstruct the input data and identify anomalies through reconstruction errors.

### Feature Extraction
- Utilizes ConvNets for encoding and DeConvNets for decoding.
- Employs a bottleneck architecture to capture essential features.

### Anomaly Mapping
- Implements an anomaly map function to highlight differences between original and reconstructed images.
- Utilizes filtering and segmentation functions to minimize false positives.

### Anomaly Classification
- Determines a threshold for the Mean Absolute Error (MAE) score to classify anomalies.

## Results & Discussion
- The system was trained on 297 images, achieving varying levels of accuracy with different architecture approaches, with the CNN-based architecture showing 78% accuracy.
- The results indicate that direct training could lead to overfitting, hence incremental learning and self-learning with feedback from experts is crucial for balanced class detection accuracy.

## Conclusion & Perspectives
- The project succeeded in automating lesion segmentation without the need for manual marking.
- Future work includes improving the user interface, implementing the model on other types of images (MRI, X-ray), and adapting the model to scan different parts of the body.

## Bibliography
A list of references is provided for further reading and understanding of the underlying technologies and methodologies used in this project.

## Contact
- For inquiries or contributions, please contact the authors via the provided email addresse in the poster.
