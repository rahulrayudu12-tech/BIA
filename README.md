# Business Intelligence & Analytics (BIA) Lab

Practical data science and business analytics implementations focusing on customer segmentation, text sentiment classification, and sports performance analytics.

## 📁 Repository Contents

| File | Type | Description |
|---|---|---|
| `Untitled0.ipynb` | Jupyter Notebook | **Customer Segmentation (K-Means Clustering)**: Identifies distinct customer groups based on annual income and spending score using Scikit-Learn's `KMeans`, elbow method analysis, and centroid visualization. |
| `Untitled1.ipynb` | Jupyter Notebook | **Sentiment Analysis (NLP)**: Text processing and classification pipeline for customer reviews using `CountVectorizer` and a `MultinomialNB` (Multinomial Naive Bayes) model with evaluation metrics and confusion matrices. |
| `customer_kmeans_dataset.csv` | Dataset | Tabular dataset with customer IDs, annual income (in Lakhs), and spending score metrics. |
| `BTA_Cricket_Sports_Analytics_Lab.xlsx` | Dataset / Lab | Sports performance and cricket analytics dataset for exploratory lab analysis. |

## 🛠️ Tech Stack & Libraries

- **Language:** Python 3.x
- **Data Manipulation:** `pandas`, `numpy`
- **Machine Learning:** `scikit-learn` (`KMeans`, `MultinomialNB`, `CountVectorizer`, `train_test_split`)
- **Data Visualization:** `matplotlib`, `seaborn`
- **Environment:** Jupyter Notebook / Google Colab

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rahulrayudu12-tech/BIA.git
   cd BIA
   ```

2. **Install required packages:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. **Run the notebooks:**
   ```bash
   jupyter notebook
   ```
   Open `Untitled0.ipynb` or `Untitled1.ipynb` and run all cells.
