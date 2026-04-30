# 🚀 Agricultural Object Detection & ML Analysis (AgriSoft Internship)

## 📌 Project Overview

This project was completed as part of an industrial internship at **TOO "AgriSoft"**.

The main objective was to analyze an agricultural dataset and evaluate machine learning model training results using real-world data.

The project combines **computer vision (annotated images)** and **data analysis (training metrics)** to demonstrate practical machine learning workflow.

---

## 🧠 Key Features

- 📊 Dataset analysis with annotated agricultural images
- 📦 Bounding box visualization (object detection)
- 📈 Training results analysis from CSV
- 📉 Performance metrics visualization (precision, recall, mAP, loss)
- 🧾 Clean and structured Jupyter Notebook
- 🔁 Reproducible workflow

---

## 📁 Project Structure

```
agrisoft-ml-internship/
│
├── dataset/
│   ├── images/
│   ├── labels/
│
├── notebooks/
│   └── analysis.ipynb
│
├── results/
│   ├── results.csv
│   ├── training_results.png
│
├── samples/
│   ├── train_batch0.jpg
│   ├── train_batch1.jpg
│   ├── train_batch2.jpg
│   └── labels.jpg
│
└── README.md
```

---

## 📊 Dataset Description

The dataset consists of agricultural field images with annotated bounding boxes.

Each bounding box represents a detected object (crop instance).  
The dataset contains **90,000+ annotated objects**, making it suitable for training deep learning models.

### 🔍 Dataset Characteristics:
- High object density
- Variability in lighting and environment
- Complex spatial distribution
- Consistent object proportions

---

## 📸 Sample Data

Annotated images include multiple bounding boxes per frame, demonstrating real-world complexity.

---

## 📈 Model Training Results

The training results are stored in a CSV file (`results.csv`) and include key performance metrics:

- Precision
- Recall
- mAP@0.5
- Loss values

### 📉 Visualization

The training process was visualized using Python:

```python
df.plot(figsize=(12,6))
```

This allows tracking model performance over training epochs.

---

## 🧪 Technologies Used

- Python 🐍
- Pandas 📊
- Matplotlib 📈
- Jupyter Notebook 📓

---

## ⚙️ How to Run

1. Open `analysis.ipynb`
2. Upload `results.csv`
3. Run all cells
4. View training graphs

---

## 📌 Results

- The dataset is large and complex
- Model shows learning behavior across epochs
- Visualization helps interpret performance
- Data analysis improves understanding of model behavior

---

## 🎯 Conclusion

This project demonstrates a full machine learning workflow:

✔ Dataset understanding  
✔ Data visualization  
✔ Model evaluation  
✔ Real-world application  

It highlights the importance of combining **data analysis and machine learning** in industrial environments.

---

## 👤 Author

**Aruzhan Saparkhankyzy**  
Astana IT University  
Computer Science  

---

## ⭐ Notes

This repository was created for educational and internship purposes.  
It reflects practical experience with real-world machine learning data.
