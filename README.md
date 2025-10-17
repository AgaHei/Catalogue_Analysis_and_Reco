# 🏔️ The North Face Product Analysis: Unsupervised Machine Learning

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-green.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

*Mandatory project for Bloc 3 certification (Machine Learning Engineer) at Jedha*

---

## 📋 Project Overview

This project demonstrates the power of **unsupervised machine learning** for product catalog analysis and intelligent recommendation systems. Using 500 authentic North Face product descriptions, we employ text processing, clustering, and topic modeling to discover hidden patterns and create meaningful product groupings.

**🎯 Objective**: Transform raw product text into actionable business intelligence through unsupervised learning techniques.

## 🔬 Technical Approach

### **From Supervised to Unsupervised Learning**
This project builds on supervised text classification principles (like Reuters news categorization) but tackles the more challenging problem of **discovering patterns without labeled data**. The key insight: both approaches rely on converting text to numerical representations, but unsupervised methods let the data reveal its own natural structure.

### **Core Methodology**

    Raw Text → TF-IDF Vectorization → Clustering + Topic Modeling → Business Insights


## 🛠️ Technologies & Libraries

- **Text Processing**: spaCy, pandas, regex
- **Feature Engineering**: scikit-learn (TfidfVectorizer)
- **Clustering**: HDBSCAN, DBSCAN, cosine similarity
- **Topic Modeling**: Latent Semantic Analysis (TruncatedSVD)
- **Visualization**: matplotlib, seaborn, WordCloud
- **Data Analysis**: numpy, pandas

## 📊 Key Findings & Results

### **Clustering Performance**
- **HDBSCAN**: ✅ 20 meaningful clusters with minimal outliers
- **DBSCAN**: ❌ 80% products labeled as outliers (too restrictive)

### **Discovered Product Themes**
| Cluster | Semantic Theme | Key Products |
|---------|---------------|--------------|
| Technical Outerwear | Softshell, breathable, waterproof | Alpine jackets, climbing gear |
| Base Layers | Merino wool, moisture-wicking | Performance underwear, thermal tops |
| Sustainable Apparel | Eco-friendly, recycled materials | Conscious collection items |
| Promotional Gear | Branded, logo merchandise | Company swag, promotional items |

### **Topic Modeling Results**
- **15 Latent Topics** identified using LSA
- **Semantic Grouping**: Products cluster by functionality rather than traditional categories
- **Cross-Cluster Insights**: Shared topics reveal customer affinity patterns

## 🎯 Business Applications

### **E-commerce Enhancements**
- **Smart Recommendations**: "Users browsing alpine softshells get technical layering suggestions"
- **Improved Navigation**: Organize by functionality (breathable, waterproof) vs categories (jackets, pants)
- **Inventory Strategy**: Identify natural product bundles for cross-selling

### **Customer Experience**
- **Contextual Relevance**: Recommendations based on technical requirements, not just product type
- **Discovery Enhancement**: Expose customers to products via semantic similarity
- **Personalization Foundation**: Topic profiles enable advanced recommendation algorithms

## 📈 Machine Learning Insights

### **Algorithm Comparison**
| Method | Strength | Use Case |
|--------|----------|----------|
| **HDBSCAN** | Handles variable density clusters | Diverse product catalogs |
| **DBSCAN** | Precise, tight clusters | Uniform data distributions |
| **LSA/TruncatedSVD** | Semantic dimensionality reduction | Topic discovery in text |

### **Feature Engineering Impact**
- **TF-IDF Weighting**: Successfully highlighted distinctive product features
- **Cosine Similarity**: Optimal for capturing semantic relationships in text
- **spaCy Preprocessing**: Crucial for handling technical outdoor gear terminology

## 📁 Project Structure

    ├── Project_The_North_Face.ipynb # Main analysis notebook
    ├── sample-data.csv # Product descriptions dataset
    └── README.md # Project documentation


## 🚀 Key Notebook Sections

1. **Text Preprocessing** - spaCy lemmatization and TF-IDF vectorization
2. **Clustering Exploration** - DBSCAN vs HDBSCAN comparison
3. **Recommender System** - Cluster-based product suggestions
4. **Topic Modeling** - LSA for semantic theme discovery
5. **Semantic Enrichment** - Mapping topics to clusters for interpretability

## 💡 Key Learning Outcomes

- **Unsupervised Learning Pipeline**: From raw text to actionable insights
- **Algorithm Selection**: Systematic evaluation of clustering approaches
- **Text-to-Numbers Transformation**: Foundation for any text ML application
- **Business Translation**: Converting technical findings into commercial value



## 🎓 Educational Context

This project was completed as part of the Machine Learning Engineer certification (Bloc 3) at Jedha. 

