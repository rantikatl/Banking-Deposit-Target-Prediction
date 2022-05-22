# Prediksi Target Kampanye Deposito

# Overview
- Dataset dapat diakses di [Kaggle](https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets)
- Pre-processing yang dilakukan: 
  - Normalisasi dan standardisasi data
  - Handling outliers menggunakan z-score
  - Handling imbalance menggunakan undersampling, oversampling, dan SMOTE
- Melakukan modeling dengan 9 model, dimana model terbaik adalah RandomForest dengan oversampling

# Problem
- Suatu bank ingin meningkatkan jumlah nasabah yang mendaftar deposito, dimana salah satu yang dapat dilakukan adalah telephonic marketing
- Telephonic marketing membutuhkan biaya besar, sehingga tidak bisa ditargetkan ke seluruh nasabah
- Perlu adanya metode yang tepat agar dapat memilih nasabah yang sesuai sehingga menghemat resource dari bank

# Goals
Meningkatkan conversion rate nasabah yang mendaftar deposito

# Objective
Membuat model machine learning untuk memprediksi nasabah yang akan diberikan kampanye deposito

# Business Metrics
- Conversion Rate (Jumlah nasabah yang mendaftar deposito setelah diberikan campaign)
- Acquisition Cost (Biaya telemarketing yang dikeluarkan selama campaign berlangsung)
