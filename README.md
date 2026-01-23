# 🛒 Data Mining Project - Online Retail Analysis

A comprehensive data mining project analyzing transactional data from an online retail store using machine learning techniques including customer segmentation, association rules, and classification.

## 📋 Project Overview

This project performs exploratory data analysis and applies data mining techniques to the [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail), containing ~540,000 transactions from a UK-based online store (December 2010 - December 2011).

### 🎯 Objectives

- Analyze sales patterns and customer behavior
- Segment customers using RFM (Recency, Frequency, Monetary) analysis
- Discover product associations using Market Basket Analysis
- Build predictive models for customer classification

## 🔬 Methods Applied

| Method | Description | Purpose |
|--------|-------------|---------|
| **PCA** | Principal Component Analysis | Dimensionality reduction for visualization |
| **K-Means** | Clustering algorithm | Customer segmentation |
| **Apriori** | Association rules mining | Product recommendations |
| **Random Forest** | Ensemble classification | Customer segment prediction |

## 📊 Key Analyses

### 1. Exploratory Data Analysis (EDA)
- Monthly sales trends and seasonality
- Top products by revenue
- Geographic sales distribution
- Customer activity over time

### 2. RFM Customer Segmentation
- **Recency**: Days since last purchase
- **Frequency**: Number of transactions
- **Monetary**: Total spending amount

### 3. Market Basket Analysis
- Frequent itemset mining with Apriori algorithm
- Association rules with support, confidence, and lift metrics
- Product pairing recommendations

### 4. Customer Classification
- Random Forest classifier with temporal validation
- Silhouette score validation for clustering quality

## 📁 Project Structure

```
Data-Mining-Project/
├── ProjektAED.ipynb        # Main analysis notebook (EDA + Data Mining)
├── analiza_rfm.ipynb       # Detailed RFM analysis with ML validation
├── OnlineRetail.csv        # Dataset (UCI Online Retail)
├── pyproject.toml          # Project dependencies
├── uv.lock                 # Dependency lock file
├── .python-version         # Python version specification
├── LICENSE                 # MIT License
└── README.md               # This file
```

## 🛠️ Installation

### Prerequisites
- Python 3.12+
- [uv](https://github.com/astral-sh/uv) package manager (recommended)

### Setup

```bash
# Clone the repository
git clone https://github.com/Blazejost/Data-Mining-Project.git
cd Data-Mining-Project

# Install dependencies with uv
uv sync

# Or with pip
pip install matplotlib mlxtend pandas scikit-learn seaborn
```

## 🚀 Usage

1. **Run the main analysis notebook:**
   ```bash
   jupyter notebook ProjektAED.ipynb
   ```

2. **Run the detailed RFM analysis:**
   ```bash
   jupyter notebook analiza_rfm.ipynb
   ```

## 📦 Dependencies

- `pandas` >= 3.0.0 - Data manipulation
- `matplotlib` >= 3.10.8 - Visualization
- `seaborn` >= 0.13.2 - Statistical visualization
- `scikit-learn` >= 1.8.0 - Machine learning algorithms
- `mlxtend` >= 0.24.0 - Association rules mining

## 📈 Key Findings

### Customer Segments (K-Means Clustering)
- **Cluster 0 (Regular)**: ~3,175 customers - Average engagement
- **Cluster 1 (VIP)**: ~13 customers - High frequency & monetary value
- **Cluster 2 (At-Risk)**: ~1,109 customers - Low recent activity

### Association Rules Highlights
- Strong product associations found among decorative items
- Color variants of same products frequently purchased together
- Lift values up to 24x indicating strong positive correlations

## 📊 Dataset Information

| Attribute | Description |
|-----------|-------------|
| InvoiceNo | Invoice number (unique per transaction) |
| StockCode | Product code |
| Description | Product name |
| Quantity | Quantity purchased |
| InvoiceDate | Date and time of transaction |
| UnitPrice | Price per unit (GBP) |
| CustomerID | Customer identifier |
| Country | Country of customer |

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Dataset: [UCI Machine Learning Repository - Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)
- Dr. Daqing Chen, Director: Public Analytics group, London South Bank University
