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
- The system was trained on 297 images, achieving varying levels of accuracy with different architecture approaches, with the CNN-based architecture showing 82% accuracy.
- The results indicate that direct training could lead to overfitting, hence incremental learning and self-learning with feedback from experts is crucial for balanced class detection accuracy.

## Solution’s value
Integrating a convolutional autoencoder into the CT scan diagnostic process is expected to enhance the medical imaging standard significantly. While the precise improvements in efficiency and accuracy are subject to further research, preliminary findings suggest considerable potential. This technological advancement aims to not only expedite the diagnostic process but also to support healthcare professionals in providing timely and accurate patient care. However, to accurately quantify the impact of our convolutional autoencoder as a Decision Support Tool, extensive research, including pilot studies and data analysis, is essential. This research will compare the tool's performance against current diagnostic practices and refine its capabilities for optimal clinical application. 

## Conclusion
 Our project represents a major step forward in medical imaging technology. By developing a self-supervised convolutional autoencoder as a Decision Support Tool, our goal is to significantly improve the process of CT scan diagnostics. This tool is designed to aid, not replace, the radiologist's expertise, ensuring that the final diagnostic decision always rests with the medical professional. As we continue our research, we are committed to fully realizing the potential of this technology, setting a new benchmark in patient care and healthcare efficiency.


## Bibliography
- Sharma, S., Kaur, M., & Saini, D. (2019). Lung cancer detection using convolutional neural network. International Journal of Engineering and Advanced Technology, 8(6), 3256–3262. https://doi.org/10.35940/ijeat. F8836.088619. 
- Lung Anomaly Detection System (LADS) Using SVM based on Firefly Algorithm. (2017). International Journal of Science and Research (IJSR), 6(7), 540–544. https://doi.org/10.21275/art20175294 
- Sato, J., Suzuki, Y., Wataya, T., Nishigaki, D., Kita, K., Yamagata, K., Tomiyama, N., & Kido, S. (2023). Anatomy-aware Self-supervised Learning for Anomaly Detection in Chest Radiographs. iScience https://arxiv.org/pdf/2205.04282.pdf

## Contact
- For inquiries or contributions, please contact the authors via the provided email addresse in the poster.
