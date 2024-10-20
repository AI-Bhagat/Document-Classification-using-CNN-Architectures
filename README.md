# 📄 Document Classification Using Deep Learning

With the rapid increase in data generation, there is a growing need for sophisticated systems to classify and label large datasets for downstream tasks. **Deep learning** has seen significant success in recent years, particularly in computer vision, where **Convolutional Neural Networks (CNNs)** have consistently demonstrated their effectiveness. While transformer-based models with attention mechanisms are emerging as powerful tools, this project focuses on **CNN-based methods** for document classification.

---

## 🎯 Project Scope
This project focuses on **document classification**, a subset of image classification. Unlike object classification tasks, such as those seen in the Fashion-MNIST dataset, document classification requires understanding both:

- 📐 **Spatial Structure** of the document
- 📝 **Contextual (Textual) Information** within the document

### Two Primary Approaches:
1. **OCR-Based Solutions**: Extract text from the document to leverage its contextual information.
2. **CNN-Based Solutions**: Classify documents based on spatial layout alone.

⚡ While ensemble approaches that combine both methods exist, this project focuses on the faster and more efficient **CNN-based classification using spatial information** only. This approach is motivated by the fact that humans can accurately classify documents based on spatial layout alone, without needing to read the text. Additionally, CNNs are faster and avoid the limitations of OCR, such as unreliable text extraction.

---

## 🗂️ Dataset
The models are trained and evaluated on the **RVL-CDIP dataset**, a well-known and extensive dataset for document classification tasks.

---

## 🚀 Objective
The objective of this project is to:

- 🛠️ **Develop and evaluate CNN architectures** for document classification using spatial features.
- 📊 **Analyze the performance** of each model to determine the most effective approach.

Feel free to explore the code, data, and results within this repository!

---

## 🔗 Additional Resources
- [Medium Article I wrote about this](https://medium.com/@atulbhagat.ba/classifying-documents-using-neural-networks-f4a86fd9b94c)
- [RVL-CDIP Dataset](https://www.cs.cmu.edu/~aharley/rvl-cdip/)
- [Convolutional Neural Networks (CNNs) Overview](https://towardsdatascience.com/a-comprehensive-introduction-to-different-types-of-cnns-6fa2ed2d891a)

