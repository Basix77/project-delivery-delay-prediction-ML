# 🚚 Delivery Delay Prediction

A Machine Learning project focused on predicting delivery delays based on logistics data.

### 🛠️ Technologies

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn` · `Google Colab`

### 📊 Project

The project includes:

* data preprocessing and cleaning
* exploratory data analysis
* data visualization
* feature analysis
* Machine Learning model training and evaluation

### 🎯 Goal

To explore whether logistics data can be used to identify patterns associated with delivery delays and build a model for delay prediction.

📓 The project was developed in **Google Colab**.

### 📈 Results

Models use only information available before delivery. `actual_delivery_hours`, `delivery_status` and `delivery_rating` are excluded, because they are known only after the delivery and would leak the answer to the model.

| Model | Accuracy | Recall (delayed) | Precision (delayed) |
|---|---|---|---|
| Decision Tree (max_depth=4) | 0.87 | 0.91 | 0.70 |
| KNN (k=3) | 0.84 | 0.74 | 0.69 |
| KNN (k=3, scaled) | 0.83 | 0.64 | 0.70 |

All models are evaluated on the same stratified 80/20 split (`random_state=42`).

<img width="523" height="66" alt="image" src="https://github.com/user-attachments/assets/3b72e8a0-322a-4c31-ae35-1874505974e1" />


<img width="660" height="493" alt="image" src="https://github.com/user-attachments/assets/206ffb90-521e-443a-b399-37201eb34332" />

<img width="993" height="630" alt="image" src="https://github.com/user-attachments/assets/7b23bc68-a4f9-4264-a133-52e18225b525" />

<img width="788" height="578" alt="image" src="https://github.com/user-attachments/assets/3968b2c2-b18a-4b90-b5f5-c817ed57118f" />



