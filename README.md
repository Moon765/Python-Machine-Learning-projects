<h1 align="center">🧑👩 Face-Based Gender Classification</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue?logo=python" alt="Python"/>
  <img src="https://img.shields.io/badge/OpenCV-Image%20Processing-green?logo=opencv" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn" alt="Scikit-Learn"/>
</p>

<p align="center">
  <b>✨ Gender detection system built with classical Machine Learning models ✨</b><br>
  Detects faces from images 🖼️, extracts features, and classifies gender using ML algorithms 📊.
</p>

---

<h2>📌 Project Overview</h2>
<p>
This project explores <b>gender classification</b> based on facial images using traditional <b>machine learning techniques</b>.  
Unlike deep learning methods, here we demonstrate the power of <b>K-Nearest Neighbors (KNN)</b>, <b>Decision Trees</b>, and <b>Random Forests</b> for face-based classification.
</p>

---

<h2>⚡ Features</h2>
<ul>
  <li>📷 <b>Face Detection</b> – Haar cascade classifiers with OpenCV</li>
  <li>🧩 <b>Feature Extraction</b> – grayscale conversion, resizing, flattening</li>
  <li>🤖 <b>Machine Learning Models</b> – KNN, Decision Tree, Random Forest</li>
  <li>🎯 <b>Hyperparameter Tuning</b> – GridSearchCV with cross-validation</li>
  <li>📊 <b>Evaluation Metrics</b> – Accuracy, Confusion Matrix, Model comparison</li>
</ul>

---

<h2>📂 Repository Structure</h2>


---

<h2>⚙️ Tech Stack</h2>
<ul>
  <li>🐍 Python (NumPy, Matplotlib)</li>
  <li>📷 OpenCV (Haar cascades for face detection)</li>
  <li>📊 Scikit-learn (ML models, GridSearchCV)</li>
</ul>

---

<h2>🚀 Workflow</h2>
<ol>
  <li>Load dataset (men/women images)</li>
  <li>Detect faces → preprocess (grayscale, resize, flatten)</li>
  <li>Split into training & test sets</li>
  <li>Train models (KNN, Decision Tree, Random Forest)</li>
  <li>Tune hyperparameters with GridSearchCV</li>
  <li>Evaluate → Accuracy & Confusion Matrix</li>
  <li>Compare models with bar chart</li>
</ol>

---

<h2>📊 Results</h2>
<ul>
  <li>✅ Models successfully classified gender with reasonable accuracy</li>
  <li>📈 Random Forest & KNN performed better than simple Decision Tree</li>
  <li>⚠️ Performance depends on dataset size & face detection quality</li>
</ul>

---

<h2>🌟 Future Improvements</h2>
<ul>
  <li>🔍 Improve dataset balance & size</li>
  <li>📐 Use PCA/LDA for dimensionality reduction</li>
  <li>🧠 Compare with Deep Learning (CNNs) for higher accuracy</li>
  <li>⚡ Deploy as a web or mobile app</li>
</ul>

---

<h2>👨‍💻 Author</h2>
<p>
Developed as part of an academic project on <b>machine learning for computer vision</b>.  
</p>

<p align="center">
  <i>“Classic ML models still shine in the right setting ✨”</i>
</p>
