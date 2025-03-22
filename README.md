# Fisher Linear Discriminant (FLD) Handwritten Digit Classifier  

This repository contains a **handwritten digit classifier** based on the **Fisher Linear Discriminant (FLD)**. The model uses **Linear Discriminant Analysis (LDA)** to reduce dimensionality and classify digits efficiently.  

## 📌 Features  
- **Fisher’s Linear Discriminant (FLD)** for optimal class separation.  
- **Trained on the MNIST dataset** or a similar handwritten digit dataset.  
- **Lightweight & efficient**—no deep learning required!  
- **Implemented in Jupyter Notebook** for easy experimentation and visualization.  

## 🚀 Installation & Usage  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/digit-classifier-fld.git
cd digit-classifier-fld
```

### 2️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook  
Open Jupyter Notebook and run:  
```sh
jupyter notebook
```
Then open and execute `digit_classifier.ipynb`.  

## 📊 Methodology  

1. **Data Preprocessing:** Normalization and feature extraction from digit images.  
2. **Dimensionality Reduction:** FLD applied to find the best projection for class separation.  
3. **Classification:** Projected features used to classify digits efficiently.  
4. **Evaluation:** Model tested on a test set to measure accuracy.  

## 📜 License  
This project is licensed under the MIT License.  
