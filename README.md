# Classification Model Comparison

This repository contains a classification analysis project comparing three popular machine learning algorithms using the **Wine dataset**:

- Logistic Regression
- k-Nearest Neighbors (k-NN)
- Decision Tree

## Objective

To build, evaluate, and compare the performance of classification models using key metrics such as:
- Accuracy
- Precision
- Recall
- F1-Score

## Dataset

The dataset used is the built-in `load_wine` dataset from the `sklearn.datasets` module. It includes 13 numerical features characterizing wine samples from three different cultivars.

## Project Structure

- `Classification_Analysis_Notebook.ipynb` — Jupyter Notebook with full data preprocessing, model building, evaluation, and visualization.
- `Classification_Model_Comparison_Report_With_Images.docx` — Final APA-style report with discussion, evaluation metrics, and embedded visualizations.
- `figures/` — (optional) Folder containing the heatmaps and charts used in the report.

## Key Visualizations

- Confusion Matrices for all models
- Correlation Heatmap of features
- Bar plot comparing macro average precision, recall, and F1-score

## Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to Use

1. Clone this repository:
```bash
git clone https://github.com/your-username/classification-model-comparison.git
cd classification-model-comparison
```

2. Install required packages (if using virtualenv):
```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook to explore the code:
```bash
jupyter notebook Classification_Analysis_Notebook.ipynb
```

## Author

This project was developed as part of a Business Analytics Lab exercise on classification model evaluation.

## License

This project is open-source and available under the [MIT License](LICENSE).
