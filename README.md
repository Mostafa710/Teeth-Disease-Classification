# 🦷 Teeth Disease Classifier

## 📌 Overview

This project is a **Deep Learning-based Teeth Disease Classifier** built using **TensorFlow/Keras**. It classifies tooth images into 7 categories and was developed in **three phases**:

1. **From Scratch Model** – Custom CNN architecture.  
2. **Pretrained & Fine-Tuned Models** – Explored and compared various architectures.  
3. **Deployment** – Deployed the best-performing model via **Streamlit**.

---

## 📂 Project Structure

```
├── teeth-disease-classifier.ipynb              # From scratch model implementation
├── teeth-disease-classifier-pre-trained.ipynb  # Pretrained and fine-tuned model experiments
├── app.py                                      # Streamlit deployment file
├── fine_tuned_InceptionV3_classifier.h5        # Saved best model
```

---

## 🧠 Model Development

### Phase 1 – From Scratch Model
- Designed and trained a **custom CNN**.
- Applied **data augmentation** and **regularization** to reduce overfitting.

### Phase 2 – Pretrained & Fine-Tuned Models
- Tested architectures like **InceptionV3**, **ResNet50**, and **VGG16**.
- Compared **frozen feature extractors** vs. **fine-tuning**.
- Selected **Fine-Tuned InceptionV3** as the best performer.

### Phase 3 – Deployment
- Built a **Streamlit web app** to classify uploaded tooth images instantly.
- Supports `.jpg`, `.jpeg`, `.png` formats.

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the repository
```
git clone https://github.com/Mostafa710/Teeth-Disease-Classification.git
cd Teeth-Disease-Classification
```

### 2️⃣ Install dependencies
Make sure you have Python 3.8+ installed, then run:
```
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app
```
streamlit run app.py
```

---

## 🖼️ Example

Upload a tooth image through the app interface and get:
- Predicted disease class
- Confidence score
<img width="1096" height="588" alt="Screenshot 2025-08-14 220252" src="https://github.com/user-attachments/assets/52a559ec-5931-4333-8700-cd086fffed93" />

---

## 🛠 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **NumPy, Pandas, Matplotlib**
- **Streamlit**

---

## 📬 Contact

For questions or collaboration, feel free to connect:

[LinkedIn](https://www.linkedin.com/in/mostafa-mamdouh-80b110228) | [Email](mailto:mostafamamdouh710@gmail.com)
