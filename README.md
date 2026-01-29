# 🏠 CaliHouse Insight: End-to-End Housing Analytics

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![Dashboard](https://img.shields.io/badge/UI-Gradio-purple)
![Status](https://img.shields.io/badge/Status-Complete-green)

## 📌 Overview
**CaliHouse Insight** is an interactive machine learning application designed to analyze and predict housing prices in California. 

Built with **Scikit-Learn** and **Gradio**, this project implements an end-to-end pipeline: from loading raw data and training regression models to deploying a user-friendly dashboard. It compares a baseline Linear Regression model against a robust Random Forest Regressor to ensure high prediction accuracy.

## 🚀 Key Features

### 1. Machine Learning Pipeline
- **Data Handling:** Automated fetching and splitting of the California Housing dataset.
- **Model Comparison:** - *Baseline:* Linear Regression (for establishing a performance floor).
  - *Advanced:* Random Forest Regressor (tuned with `n_estimators=200`, `max_depth=20`).
- **Metrics:** Evaluates models using **R² Score** and **RMSE** (Root Mean Squared Error).

### 2. Interactive Dashboard (Gradio)
The project includes a web-based UI with three main tabs:
- **🔮 Predict Price:** Input housing features (MedInc, HouseAge, AveRooms, etc.) to get an instant estimated price in USD.
- **📊 Visual Insights:** Dynamic rendering of plots:
  - Price Distribution
  - Feature Correlation Heatmap
  - Geospatial Price Map (Latitude vs. Longitude)
  - Feature Importance Rankings
- **📈 Model Metrics:** Real-time display of R² and RMSE scores for both models.

## 🛠️ Tech Stack
- **Core:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn
- **Visualization:** Matplotlib, Seaborn
- **Interface:** Gradio


## ⚙️ Installation & Usage

### Option 1: Run in Google Colab (Recommended)
1. Upload the `.ipynb` file to your Google Drive.
2. Open it with Google Colab.
3. Run all cells. The Gradio app will launch directly in the cell output or via a provided public link.

### Option 2: Run Locally
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/calihouse-insight.git](https://github.com/your-username/calihouse-insight.git)

```

2. **Install dependencies:**
```bash
pip install numpy pandas matplotlib seaborn gradio scikit-learn

```

3. **Run the Notebook:**
Open `california_housing_analytics.ipynb` in Jupyter Notebook or VS Code and execute all cells.

## 📊 Model Performance

*Typical results achieved during training:*

| Model | R² Score | RMSE |
| --- | --- | --- |
| **Linear Regression** | ~0.60 | ~0.72 |
| **Random Forest** | **~0.80+** | **~0.50** |

## Screenshots 
<img width="1917" height="828" alt="image" src="https://github.com/user-attachments/assets/ed300768-50bc-4612-9b4c-da03b81f232d" />
<img width="1870" height="745" alt="image" src="https://github.com/user-attachments/assets/46495c8f-b548-48c9-9609-f00ffd57de88" />
<img width="1919" height="820" alt="image" src="https://github.com/user-attachments/assets/355bb260-3c6e-4451-a798-dadf9eb91504" />
<img width="1919" height="828" alt="image" src="https://github.com/user-attachments/assets/fc08665b-b8cc-43a4-a500-7d0e545947c2" />
<img width="1919" height="839" alt="image" src="https://github.com/user-attachments/assets/a6cf47cb-c8d3-4bad-be13-aab1ac5de61c" />
<img width="1850" height="784" alt="image" src="https://github.com/user-attachments/assets/8325e82c-1515-4801-8032-2177dafe3038" />
<img width="1919" height="825" alt="image" src="https://github.com/user-attachments/assets/f9573f20-274d-47a5-8f71-0cf2cc337444" />
<img width="1919" height="829" alt="image" src="https://github.com/user-attachments/assets/4ccceaca-a896-4330-9832-31407be8d398" />

