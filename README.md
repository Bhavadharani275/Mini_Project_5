# Mini-Project-5
**Project Title**: *🌞 SolarGuard: Intelligent Defect Detection on Solar Panels using  DeepLearning*

---

**Domain:** Renewable Energy and Computer Vision  
**Tools Used:** Streamlit, Pandas, Plotly, SQL, Google Colab, Deep Learning(CNN)

---

### 🌞 Project Overview
SolarGuard is a deep learning-based project designed to automatically **detect and classify defects in solar panels** from images.  
This helps improve **maintenance efficiency**, **energy output**, and **fault diagnosis accuracy**.

---

## 🧭 Approach

### 1️⃣ Data Preprocessing & Annotation
- Perform **image augmentation** to balance the dataset.  
- Resize images to a suitable dimension for deep learning models.  
- **Normalize** pixel values for better model performance.

### 2️⃣ Model Training
- Train multiple **CNN-based classification models**:
  - 🧩 **ResNet50**
  - ⚡ **EfficientNetB0**
  - 📱 **MobileNetV2**
- Models are fine-tuned using **transfer learning** on solar panel defect images.

### 3️⃣ Model Evaluation
- Evaluate model performance using key metrics:
  - ✅ **Accuracy**
  - 🎯 **Precision**
  - 📈 **Recall**
  - ⚖️ **F1-Score**

### 4️⃣ Deployment
- Deploy a **Streamlit web application** that allows users to:
  - Upload solar panel images  
  - Get **classification results** for panel conditions  
  - View **defect probability** and **maintenance recommendations**

---

## 📁 Dataset
The dataset consists of labeled solar panel images classified into six categories:

| Class | Description |
|:--|:--|
| 🐦 Bird-drop | Bird droppings on panel surface |
| ✨ Clean | Clean panels (no defect) |
| 🌫️ Dusty | Dust accumulation |
| ⚡ Electrical-damage | Circuit or cell issues |
| 💔 Physical-Damage | Cracks or breaks |
| ❄️ Snow-Covered | Snow obstruction |

📦 **Dataset Source:** [[Google Drive Link](https://drive.google.com/drive/folders/1jxvEPI01XIEj-1cwMvwL0Gto8-qyXN0g?usp=drive_link)][https://drive.google.com/drive/folders/1jxvEPI01XIEj-1cwMvwL0Gto8-qyXN0g?usp=drive_link] *

---

## 📊 Exploratory Data Analysis (EDA)
- **Class Distribution Visualization** using Plotly  
- **Brightness and Sharpness Analysis** of images  
- **Sample Image Visualization** by class  
- **Business Insights:**
  - Common fault types (e.g., Dust, Bird-drop)  
  - Prioritize cleaning & inspection cycles for frequent issues

---

## 📂 Project Structure

- `Solar_Panels.ipynb` — Main Colab notebook
- `Dataset` - Solar panel images by class (Dataset Source link)
  
---

## 🔹 How to Run in Google Colab

1. **Open the Notebook**  
   Upload or open `Solar_Panels.ipynb` in [Google Colab](https://colab.research.google.com/).

2. **Mount Google Drive**
    ```python
   from google.colab import drive
   drive.mount('/content/drive') 
   
4. **Run All Cells**  
   The notebook performs:  
   - EDA & Visualization  
   - Model Training  
   - Evaluation & Results Display  

---

## 👩‍💻 Author

**Bhavadharani**  
Mini-Project 5 — *SolarGuard: Intelligent Defect Detection on Solar Panels using  DeepLearning*
