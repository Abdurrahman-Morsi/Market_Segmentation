# Customer Segmentation and Analysis

## **Project Overview**
This project aims to identify distinct customer segments using machine learning techniques to enhance targeted marketing strategies and improve conversion rates for term deposit subscriptions.

## **Objective**
The goal is to analyze customer data and identify key segments that can be targeted more effectively, thereby increasing the likelihood of successful term deposit subscriptions.

## **Cluster Analysis**

|**Cluster**|**Median Contact Duration**|**90% Duration Under**| **Subscription Probability** | **Key Insights**|
|-----------|---------------------------|----------------------|------------------------------|-----------------|
| **0**|6 minutes|15 minutes|20.9%|Best for targeting; highest subscription rate.|
| **1**|13 minutes|24 minutes|4.5%|Lowest subscription rate; needs revised strategies.|
| **2**|13 minutes|22 minutes|5.6%|Moderate potential; optimize marketing efforts.|

## **Recommendations**
- **Cluster 0**: Target with personalized campaigns.
- **Cluster 1**: Reevaluate marketing strategies.
- **Cluster 2**: Optimize marketing balance.

## **Conclusion**
Segmentation provides actionable insights to improve term deposit subscriptions.

## **Repository Structure**
- [`data/`](bank-additional-full.csv) - Contains the raw data file.
- [`notebooks/`](customer_segmentation.ipynb) - Includes Jupyter notebooks used for exploratory data analysis and model building. This directory also contains two versions of the notebook: one with inputs and one without, available as PDF files.
- [`model/`](model.h5) - Contains the HDF file for the trained model.
- [`README.md`](README.md) - This Markdown file with project details and instructions.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Acknowledgements**
- Dataset: [Bank Marketing Dataset](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing) on Kaggle
- Autoencoder and PCA implementations adapted from [Keras Documentation](https://keras.io/) and [Scikit-learn Documentation](https://scikit-learn.org/stable/)
