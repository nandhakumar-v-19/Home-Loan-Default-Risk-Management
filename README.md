# Home-Loan-Default-Risk-Management
A data-driven project focused on predicting and managing home loan default risk using advanced Machine Learning and Data Analytics techniques. This repository explores financial risk assessment through EDA, feature engineering, and model optimization, aiming to help financial institutions minimize credit loss and improve lending decisions.

This project uses a large dataset hosted on **Kaggle**.  
Due to size constraints (>2.5 GB), the dataset is not uploaded here.

## 📊 Dataset Source
[Kaggle Dataset – Home Loan Default - Risk Management Dataset](https://www.kaggle.com/datasets/nandhakumarvaiandds/home-loan-default-risk-management)

## 🚀 How to Load Dataset in Colab
```python
!pip install kaggle
!mkdir -p ~/.kaggle
!echo '{"username":"YOUR_KAGGLE_USERNAME","key":"YOUR_KAGGLE_API_KEY"}' > ~/.kaggle/kaggle.json
!chmod 600 ~/.kaggle/kaggle.json
!kaggle datasets download -d suvaathii/plant-disease-images
!unzip -q plant-disease-images.zip -d dataset/
