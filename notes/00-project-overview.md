# Project Overview

## Problem Definition
### Problem
- Xâu dựng mô hình dự đoán giá nhà dựa trên các đặc trưng về địa chỉ, khu vực, kích thước, trạng thái,...
- Trải qua một process AI hoàn chỉnh: tìm hiểu -> thu thập & xử lý dữ liệu -> huấn luyện mô hình -> fine-tune, đánh giá và deploy
- Triển khai và so sánh các kỹ thuật cơ bản và nâng cao hơn
- Phục vụ cho mục đích nghiên cứu, bổ sung exp/cv

### Technical
- Supervised learning
- Regression task
- Batch-based training

### Tools
- Platforms: kaggle + local
- Version Control: git & Github
- Packages: 
    - NumPy, Pandas, Matplotlib, TensorFlow
    - 

## Data Information
### Datasets: 
- Datasets: House Price Prediction Dataset Vietnam - 2024
- Source: [kaggle datasets](https://www.kaggle.com/datasets/nguyentiennhan/vietnam-housing-dataset-2024) 
    - Nguyen Tien Nhan · Updated a year ago
    - The data was crawled from batdongsan.vn
- Description:  This dataset contains information about various housing properties in Vietnam. It includes detailed attributes of each property, such as its location, physical characteristics, and legal and furnishing status, along with the price. This dataset can be useful for real estate analysis, price prediction models, and market trend analysis.
- Overview:
    - ~30.2k instances
    - 12 features
    - phần lớn là category và number, chỉ có 1 cột text chưa được xử lý
    - số lượt cate feature nhiều nhưng số loại giá trị mỗi feat không nhiều


### California Housing Prices 
- Source: datasets từ chapter 2 homl
    - [kaggle datasets](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
    - StatLib repository
    - CAM NUGENT · UPDATED 8 YEARS AGO

- Description:  
    * This is the dataset used in the second chapter of Aurélien Géron's recent book 'Hands-On Machine learning with Scikit-Learn and TensorFlow'. It serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables and sits at an optimal size between being to toyish and too cumbersome.

    * The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.

- Overview:
    - 20.6k instances
    - 10 features: phần lớn là number và 1 category
    - rất ít bị Nan, rất clean

- Content: The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. Be warned the data aren't cleaned so there are some preprocessing steps required! The columns are as follows, their names are pretty self explanitory:
    - longitude
    - latitude
    - housing_median_age
    - total_rooms
    - total_bedrooms
    - population
    - households
    - median_income
    - median_house_value
    - ocean_proximity

- Acknowledgements:
    * This data was initially featured in the following paper:  
    Pace, R. Kelley, and Ronald Barry. "Sparse spatial autoregressions." Statistics & Probability Letters 33.3 (1997): 291-297.

    * And republic to kaggle by CAM NUGENT:  
    "I encountered it in 'Hands-On Machine learning with Scikit-Learn and TensorFlow' by Aurélien Géron."

    * Aurélien Géron wrote:  
    This dataset is a modified version of the California Housing dataset available from: Luís Torgo's page (University of Porto)