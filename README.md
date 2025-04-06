# DL-Assignment1-DNN-Activation-Depth
Deep Learning Assignment 1 – Implementation of DNNs with various activation functions and depth analysis. Includes visualization, performance comparison, and a presentation. By Abel Tadesse.
# Deep Learning Assignment 1 – DNN Activation Functions & Depth Analysis

## 👨‍🎓 Student Info
**Name:** Abel Tadesse
**Course:** Advanced Deep Learning (AAiT)  
**Assignment Title:** Assignment 1 (10 points)  
**Submitted on:** April 2, 2025  
**Instructor:** Dr. Fantahun Bogale  

---

## 📌 Objective

This assignment explores the behavior of Deep Neural Networks (DNNs) by:
- Implementing different **activation functions** (Sigmoid, Tanh, ReLU, Leaky ReLU, and Parametric ReLU).
- Demonstrating how ReLU addresses the **vanishing gradient problem**.
- Comparing the performance of different **ReLU variants**.
- Analyzing the effect of **network depth** on performance with at least five different depths.

---

## 🧪 Contents

### 1️⃣ Activation Functions (4 pts)
- Simple DNN models using:
  - Sigmoid
  - Tanh
  - ReLU
  - Leaky ReLU
  - Parametric ReLU
- Visualizations of activation curves
- Gradients and loss comparisons
- Explanation of how ReLU mitigates the vanishing gradient problem

### 2️⃣ Depth of ANNs (2 pts)
- Experiments with 5 different network depths
- Plots of **Test Accuracy vs Depth**
- Observations on underfitting, overfitting, and model capacity

### 3️⃣ Presentation (4 pts)
- Slide or PDF report summarizing:
  - Key results
  - Graphs/plots
  - Observations and conclusions

---

## 🖥️ How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/DeepLearning-Assignment1-DNN-Activation-Depth](https://github.com/ab3lT/DL-Assignment1-DNN-Activation-Depth.git
cd DL-Assignment1-DNN-Activation-Depth

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run examples
python activation_functions/dnn_relu_variants.py
python depth_analysis/dnn_depth_3.py
