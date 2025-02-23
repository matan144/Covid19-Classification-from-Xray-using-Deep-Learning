# Covid19-Classification-from-Xray-using-Deep-Learning
Covid19 Classification from Xray using Deep Learning

Project Description

This project implements a deep learning CNN for automated chest X-ray classification, with a primary focus on detecting COVID-19 cases alongside bacterial pneumonia and normal lung images. Leveraging TensorFlow and Keras, the solution seamlessly integrates data ingestion, preprocessing, and augmentation to address real-world challenges such as class imbalance and data variability.

Key components include:

    Data Acquisition & Integration:
    The project consolidates multiple public datasets—including the IEEE COVID-19 Chest X-Ray Dataset and a Kaggle-sourced pneumonia dataset—into unified training and testing sets. Custom filtering ensures that only clinically relevant images (e.g., posteroanterior views) are included.

    Preprocessing & Augmentation:
    A robust preprocessing pipeline converts images to grayscale, resizes them to 512×512, and normalizes pixel intensities. Data augmentation techniques (e.g., random flips, brightness/contrast adjustments, noise injection, and test-time augmentation) are strategically employed to boost generalization and mitigate overfitting.

    Modeling & Evaluation:
    Two distinct modeling strategies are explored: a custom-built convolutional neural network (CNN) and a transfer learning approach using pre-trained architectures (e.g., ResNet50 and MobileNetV2). The project includes comprehensive performance evaluation using confusion matrices, accuracy, precision, recall, specificity, and t-SNE visualization to assess feature embedding quality.

    Addressing Imbalanced Data:
    The solution implements multiple strategies—under-sampling, over-sampling, and class weighting—to effectively manage imbalanced class distributions, ensuring that minority classes receive adequate representation during training.

This innovative, modular approach not only serves as a blueprint for tackling complex medical imaging tasks but also lays the groundwork for future research into scalable and accurate diagnostic tools.
