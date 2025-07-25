
# 🧠 Fashion Trend Prediction

This project uses machine learning techniques to predict future fashion trends based on historical and visual data. Leveraging clustering, PCA, and color analysis from image datasets, it aims to provide insights into evolving fashion aesthetics.

---

## 📁 Project Structure

- **Data Preprocessing**  
  Image data is preprocessed to extract color features and apply dimensionality reduction using PCA.

- **KMeans Clustering**  
  The dominant color trends in fashion images are clustered using the KMeans algorithm to identify emerging themes.

- **Color Palette Extraction**  
  Colors are extracted from fashion item images using `sklearn`, `OpenCV`, and `matplotlib`.

- **Visualization**  
  Clusters and their color palettes are visualized using bar plots and scatter plots (after PCA) to demonstrate groupings and trends.

---

## 📦 Dependencies

Make sure the following Python libraries are installed:

```bash
pip install numpy pandas matplotlib seaborn opencv-python scikit-learn
```

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/SanketSuradkar/Fashion-trend-prediction.git
   cd fashion-trend-prediction
   ```

2. Run the Jupyter notebook:
   ```bash
   jupyter notebook Fashion_Trend_Prediction.ipynb
   ```

---

## 📊 Key Concepts

- **Color Histograms**: Analyze dominant color palettes from images.
- **PCA (Principal Component Analysis)**: Reduce dimensionality for better clustering and visualization.
- **KMeans Clustering**: Identify similar fashion trends using unsupervised learning.

---

## 🔍 Example Output

- Color palettes of each image.
- Clustered visualizations of fashion images by color.
- Trend maps of color-based fashion groupings.

---

## 📌 TODO

- Integrate deep learning models (e.g., CNNs) for style recognition.
- Include time-series forecasting for trend dynamics.
- Build a web interface for visual exploration.

---

## 📜 License

Copyright (c) 2025 Sanket Suradkar

All rights reserved.

This project, "Fashion Trend Prediction", was developed as part of the final year engineering curriculum at 
KJ College of Engineering and Management Research, Pune.

Unauthorized copying, distribution, modification, or use of this work in whole or in part is strictly prohibited 
without express written permission from the author.

For inquiries, please contact: sanketsuradkar@[sandysuradkar12@gmail.com]
.

---


