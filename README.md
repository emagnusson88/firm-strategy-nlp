# Firm Strategy and Financial Performance with Natural Language Processing

Using a bag of words model from annual report text to predict whether or not consumer packaged goods (CPG) companies will outperform the S&P 500


## Project Structure
```
firm-strategy-nlp 
│   README.md
│   Code
│   Report
│   Firm_Strategy_NLP_Report.pdf
│
└───Code
│   │   stock_data_import.ipynb -collecting historical stock prices with Alpha Vantage API
│   │   read_text.ipynb -generating bag of words
│   │   exploratory_data_analysis.ipynb -exploring distribution of terms across annual reports
│   │   pca.ipynb -performing principal component analysis on bag of words model
│   │   clustering.ipynb -kmeans clustering for grouping companies by terminology
│   │   PCA + Models_FINAL.ipynb -comparing binary classifiers
│
└───Report
│   │   LaTeX reporting file with .png files
│
└───Firm_Strategy_NLP_Report
    │   Final project report
  

