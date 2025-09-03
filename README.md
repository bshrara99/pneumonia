# Chest X-Ray Pneumonia Classification

This project builds a **Convolutional Neural Network (CNN)** to classify chest X-ray images as **Normal** or **Pneumonia**.

---

## Steps

1. **Download Dataset**  
   - Chest X-Ray Pneumonia dataset from [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

2. **Load and Preprocess Data**  
   - Resize images to **224×224**.  
   - Normalize pixel values.  
   - Apply **data augmentation** to the training set.

3. **Build CNN**  
   - `Conv2D + MaxPooling` layers for feature extraction.  
   - `Flatten + Dense` layers for classification.  
   - Output layer with **2 neurons** (softmax activation).

4. **Compile and Train**  
   - Optimizer: **Adam**.  
   - Loss: **Sparse Categorical Cross-Entropy**.  

5. **Evaluate Model**  
   - **Test accuracy:** ~83%.  
   - **Confusion matrix** and **classification report** show better performance on *Pneumonia* class than *Normal*.  

6. **Visualize Performance**  
   - Training/validation accuracy and loss curves.  
   - Signs of **overfitting** observed.


---
