# Fake_face_detection

## 📂 Dataset

This project uses the **FaceForensics++ (FF++)** dataset for training and evaluation.

The dataset is downloaded automatically in Google Colab using **KaggleHub**, so it is **not included in this repository** due to its large size.

Dataset contains:
- Real face images
- Deepfake (Fake) face images

---

## 📁 Project Structure

```
Fake_face_detection/
│
├── face_detection.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Fake_face_detection.git
```

2. Open the project directory.

```bash
cd Fake_face_detection
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Open **face_detection.ipynb** in **Google Colab** or **Jupyter Notebook**.

5. The notebook will automatically download the FaceForensics++ dataset using **KaggleHub** before training or testing the model.

---

## 📊 Features

- Deepfake face detection
- Automatic dataset download using KaggleHub
- Face extraction using FaceNet
- Deep learning model built with PyTorch
- Real vs Fake face classification
- Model training and evaluation
