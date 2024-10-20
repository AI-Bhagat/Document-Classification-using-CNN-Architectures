# DA526_IPML: Document Classification Using Deep Learning

With the rapid increase in data generation, there is a growing need for sophisticated systems to classify and label large datasets for downstream tasks. Deep learning has seen significant success in recent years, particularly in computer vision, where Convolutional Neural Networks (CNNs) have consistently demonstrated their effectiveness. While transformer-based models with attention mechanisms are emerging as powerful tools, this project focuses on CNN-based methods for document classification.

## Project Scope
This project focuses on **document classification**, a subset of image classification. Unlike typical object classification tasks, such as those seen in the Fashion-MNIST dataset, document classification requires an understanding of both the spatial structure of a document and the contextual (textual) information it contains. There are two primary approaches:

1. **OCR-Based Solutions:** Extract text from the document to use its contextual information.
2. **CNN-Based Solutions:** Rely solely on spatial layout to classify documents.

Although ensemble approaches combining these methods are possible, this project focuses on CNN-based classification using only spatial information. The motivation for this approach is that humans can categorize documents with high accuracy based on spatial structure alone. Moreover, CNN-based methods are faster and more efficient than OCR-based methods, which can be time-consuming and may not reliably extract textual data.

## Dataset
The models are trained and evaluated on the **RVL-CDIP dataset**, a widely-used dataset for document classification tasks.

## Objective
The objective of this project is to develop and evaluate different CNN architectures for document classification using spatial features, and to analyze the performance of each model.

---
