# Parkinson's Activity Recognition Analysis

This project analyzes accelerometer data to classify human activities (e.g., sitting, standing, shaking) using Python. It processes raw sensor data to identify patterns that may be relevant for monitoring Parkinson's disease symptoms.

## 📂 Project Structure
- `perkinson_all.ipynb`: The main Python notebook containing the analysis, signal processing, and machine learning models.
- `datasets/`: Folder containing all raw accelerometer data and activity logs.
  - *See the README inside this folder for detailed data descriptions.*

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have the required libraries installed (pandas, numpy, scipy, sklearn).
3. Open `perkinson_all.ipynb` in Jupyter Notebook or Google Colab.
4. Run the cells to process the data from the `datasets/` folder.

## 📊 Methodology
The analysis includes:
- **Data Loading:** recursively reading accelerometer files.
- **Signal Processing:** FFT (Fast Fourier Transform) analysis.
- **Machine Learning:** Classification of activity types using Random Forest.
