# 🖼️ CIFAR-10 Image Classification with CNN  

A deep learning project to classify images from the **CIFAR-10 dataset** into **10 categories**:  
`airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck`.  

The model is built using a **Convolutional Neural Network (CNN)** with stacked convolution + pooling layers, followed by fully connected layers and a **softmax output** for multi-class classification.  

---

## 📌 Project Overview  
- **Dataset**: CIFAR-10 (60,000 color images, 32x32 pixels, 10 classes)  
- **Task**: Multi-class classification (10 categories)  
- **Approach**:  
  - Preprocess and normalize images  
  - Design CNN architecture with Conv2D + Pooling layers  
  - Add fully connected layers with Dropout  
  - Train using categorical cross-entropy and Adam optimizer  
  - Evaluate on test set and visualize results  

---

## 🛠️ Tech Stack  
- Python  
- TensorFlow / Keras (for CNN model)  
- NumPy, Pandas  
- Matplotlib, Seaborn (for visualization)  

---

📊 Results
	•	Achieved strong accuracy on CIFAR-10 test set (>75% depending on architecture).
	•	Dropout and data augmentation improved generalization.
	•	Learning curves show stable convergence with Adam optimizer.
 
---

📌 Future Work
	•	Experiment with deeper CNNs (ResNet, VGG).
	•	Add hyperparameter tuning (learning rate, batch size, epochs).
	•	Deploy model with Flask/Streamlit for real-time predictions.

⸻

✨ Acknowledgements
	•	CIFAR-10 Dataset
	•	TensorFlow/Keras Documentation
	•	Scikit-learn for preprocessing utilities
