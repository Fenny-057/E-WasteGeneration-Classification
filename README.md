# ♻️ E-Waste Classification using Deep Learning & Metadata Fusion

This repository contains a deep learning-based solution for classifying electronic waste into 10 categories using transfer learning and simulated metadata. The project demonstrates model comparison, multimodal learning (image + structured data), and real-time deployment with Gradio.

📌 *This project was completed as part of an internship assignment submission.*

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `1. E_WasteClassification.ipynb` | Basic image classification using EfficientNetV2B0 with Gradio deployment and visualizations. |
| `2. E_WasteClassificationWeek2.ipynb` | Comparison of four CNN models — EfficientNetV2B0, EfficientNetV2B3, MobileNetV2, and ResNet50. EfficientNetV2B0 performed the best on the dataset. |
| `3. E_waste_generation_classification.ipynb` | Fusion of image features with simulated metadata (weight, voltage, portability, material score) using a multimodal neural network. Deployed using Gradio for real-time predictions. |

---

## 🧠 Key Features

- 🔍 Transfer learning with **EfficientNetV2B0**
- 🧩 Multimodal input: **image + metadata fusion**
- 📊 Model performance comparison across 4 CNNs
- 🎛️ Deployment with **Gradio** for real-time inference
- 🔤 Class predictions mapped to **actual product names**

---

## 📊 Dataset

- 10 e-waste classes (e.g., Battery, Mobile, Television, PCB, etc.)
- 2400 training images  
- 300 validation images  
- 300 testing images  
- Images resized to **128×128**, normalized for training  
- Metadata simulated per sample with:
  - `weight` (0.1–5.0 kg)  
  - `voltage` (1.5–220 V)  
  - `is_portable` (binary)  
  - `material_score` (0–1 float)

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/e-waste-classification.git
cd e-waste-classification
2. Open the desired notebook in Jupyter Notebook or Google Colab


📈 Results
✅ EfficientNetV2B0 showed best performance with ~93% accuracy
✅ Metadata fusion improved real-world relevance and classification robustness
✅ Model deployed for easy testing via Gradio interface

🧰 Tools & Libraries
Python 3.x
TensorFlow & Keras
NumPy, Matplotlib , PIL , cv2
Gradio (for web UI deployment)
Google Colab (for training and experimentation)


🙋‍♀️ Author
Fenny Markana
B.Tech in CSE (AI & ML)
Karnavati University (Unitedworld Institute of Technology)
📫 Email: patelfenny4770@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/fenny-markana-a919ba2ab

