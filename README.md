# Enhancing Mental Health: Stress Level Prediction through a Machine Learning and NLP Approach

This repository contains the work of Raja Muppidi and Bhuvana Muriki, students of Applied Computing at Michigan Technological University. The project focuses on utilizing machine learning (ML) and natural language processing (NLP) to predict stress levels from textual data. Our approach leverages various ML models to analyze text data extracted from online platforms, aiming to enhance early diagnosis and intervention in mental health.

## Project Overview

Mental health issues, especially stress, pose a significant public health challenge. Traditional stress diagnosis methods, which are often subjective and time-consuming, are being supplemented by more scalable and objective ML techniques. This project employs advanced NLP methods to analyze unstructured text data, providing insights into an individual's psychological state.

### Team Members

- **Raja Muppidi**
  - Email: [rmuppidi@mtu.edu](mailto:rmuppidi@mtu.edu)
- **Bhuvana Muriki**
  - Email: [bmurki@mtu.edu](mailto:bmurki@mtu.edu)

## Repository Structure

- `Human Stress Detection.ipynb`: Jupyter notebook containing all the code for model training, evaluation, and comparative analysis.
- `Enhancing Mental Health- Stress Level Prediction Project Report.pdf`: Comprehensive project report detailing the methodology, experiments, results, and discussions.

## Models Used

- **Naive Bayes Classifier**: Serves as the baseline model for stress prediction.
- **LSTM (Long Short-Term Memory Network)**: Advanced model for capturing temporal dependencies in text data.
- **GRU (Gated Recurrent Unit)**: Similar to LSTM but with fewer parameters, optimized for quicker training without sacrificing much accuracy.
- **Ensemble Model**: Combines predictions from the above models to improve accuracy and robustness.

## Key Findings

- The GRU model slightly outperformed the LSTM in accuracy, precision, recall, and F1-score.
- The ensemble model showed the best overall performance, underscoring the efficacy of combining multiple models for stress prediction.

## Future Work

Future enhancements will focus on integrating additional data sources such as audio and biometric signals, exploring unsupervised learning techniques, and expanding the model's adaptability to specific demographic groups.

## Acknowledgements

We extend our gratitude to our advisor and the faculty at the Department of Applied Computing at Michigan Technological University for their guidance and support throughout this project.
