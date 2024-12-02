# Predicting stock return 

## Tools used in project
* [poetry](https://python-poetry.org/): quản lý thư viện Python
* [LightGBM](https://lightgbm.readthedocs.io/en/stable/) Train LGBM 
* [Sklearn](https://scikit-learn.org/1.5/modules/model_evaluation.html) Split sample, đánh giá hiệu quả mô hình qua các metrics
* [MLForecast](https://nixtlaverse.nixtla.io/mlforecast/index.html): Xử lý dữ liệu time series


## Project structure
* `predict_stock.ipynb`: model training scripts
* `dataset`: stock data của 4 mã cổ phiếu
* `pyproject.toml`: file chứa dependencies của dự án

## Project flow
Sử dụng notebook để chạy các phần chương trình
1. Data import
2. EDA
3. Feature engineering
4. Model training and evaluation
5. 