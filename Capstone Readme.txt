# Customer Segmentation with PCA and K-Means

This project explores customer segmentation using unsupervised learning techniques. The goal was to group similar customers based on behavior and demographics to help guide more targeted marketing strategies.

## Project Summary

I worked with a marketing dataset that included customer demographics, spending patterns, and campaign engagement. After cleaning and preprocessing the data, I applied Principal Component Analysis (PCA) to reduce dimensionality and then used K-Means clustering to identify meaningful segments.

### Main Steps:
- Cleaned and standardized the dataset
- Reduced feature space using PCA while retaining most of the variance
- Evaluated different cluster sizes using inertia and silhouette scores
- Interpreted and visualized the final clusters in 2D space

## Results

The analysis revealed four distinct customer groups with clear differences in income, spending habits, and campaign responsiveness. These insights can help marketing teams prioritize high-value segments and personalize outreach efforts.

## Tools Used
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Matplotlib & Seaborn for visualization

## Files in this Repo
- `segmentation.ipynb`: The full notebook with code, charts, and commentary
- `README.md`: Project summary and context
- (Optional) `requirements.txt` if you want to recreate the environment

## Getting Started

To run the notebook locally:
1. Clone the repo
2. Install required packages
3. Launch Jupyter and open `segmentation.ipynb`

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
pip install -r requirements.txt
jupyter notebook
