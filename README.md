# Deep Learning: Handwritten Digit Recognition with MNIST and RNA

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EiG3PPRkmNm8r9JaMcTJ64RmmgHtRHn0?usp=sharing)

## 📌 Project Overview
This repository demonstrates the implementation of an **Artificial Neural Network (RNA)** to classify handwritten digits from the classic **MNIST dataset**. Developed as part of my research and advanced studies in **Informatics Engineering at the Polytechnic Institute of Bragança (IPB)**, the project explores the use of Deep Learning to achieve high accuracy in visual pattern recognition.

## 🚀 Key Features
* **Neural Network Architecture**: Utilizes a Sequential model with a Flatten input layer, a Dense hidden layer (512 units) with `tanh` activation, and a Softmax output layer.
* **Data Preprocessing**: Implements image normalization (scaling pixel values to a 0-1 range) and One-Hot Encoding for labels using `to_categorical`.
* **Optimized Training**: Uses the **Adam optimizer** with a fine-tuned learning rate and `categorical_crossentropy` as the loss function.
* **Custom Input Testing**: Includes a script to read external digit data from a text file, allowing the model to predict user-provided handwritten samples.
* **Data Visualization**: Features integrated plotting with Matplotlib to visualize training samples and their respective labels.

## 🛠️ Tech Stack
* **Language**: Python
* **Deep Learning Framework**: TensorFlow / Keras
* **Numerical Processing**: NumPy
* **Visualization**: Matplotlib
* **Platform**: Google Colab

## 📊 Technical Insights
The model is configured to balance computational efficiency and predictive power:
* **Activation Functions**: Employs the Hyperbolic Tangent (`tanh`) in the hidden layer to handle non-linearities and `softmax` at the final stage for probabilistic multiclass distribution.
* **Efficiency**: Trained with a `batch_size` of 128 over 5 epochs, ensuring rapid convergence without compromising the accuracy achieved on the test set.
* **Input Handling**: Features robust error handling for external file reading, ensuring the pipeline remains functional even with missing local datasets.

## 📂 Repository Structure
* `mnist_dataset_rna.py`: Full implementation of the neural network, from data loading to custom prediction.
* `numero.txt`: (Optional/Generated) File containing pixel data for external digit testing.

---

## 👤 About the Author
**Pedro Ferreira Franco**
Brazilian Researcher in Bragança | MSc Student in Informatics Engineering at **IPB** 🇵🇹

I am a software developer, researcher, and triathlete with a passion for Robotics, IoT, and Artificial Intelligence. Currently researching AI-driven calibration for industrial robots at the **Polytechnic Institute of Bragança**.

🔗 **Connect with me:**
* **LinkedIn**: [pedro-ferreira-franco](https://www.linkedin.com/in/pedro-ferreira-franco/)
* **GitHub**: [PedroFerreiraFranco](https://github.com/PedroFerreiraFranco)
* **Instagram**: [@pedrofranco_11](https://www.instagram.com/pedrofranco_11/)

---
*Developed in Bragança, Portugal.*
