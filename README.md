# House Prices Prediction - Regression Project with LightGBM

This repository contains a Jupyter Notebook for the House Prices Prediction competition on Kaggle. The notebook demonstrates data preprocessing and the use of the LightGBM algorithm to predict house prices. This project is part of my portfolio to showcase my skills in data science and machine learning.
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
## Table of Contents
Introduction
Data Description
Methodology
Algorithm Used
Results
Conclusion
Acknowledgements
Author
License

## Introduction
Predicting house prices is a critical task in real estate and finance. This project aims to build a regression model to predict house prices using a dataset provided by Kaggle. The notebook includes data preprocessing, feature engineering, model training, and evaluation steps.
## Data Description
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence. With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## Methodology
1. **Data Preprocessing**
  - Handling missing values: Missing values were filled with the mean, median, or mode.
  - Encoding categorical variables: Categorical variables were transformed into numerical values using label encoding and one-hot encoding.
  - Skewness correction: The target variable (SalePrice) was log-transformed to approximate a normal distribution.
2. **Exploratory Data Analysis (EDA)**
  - Data visualization: Various plots were used to understand the relationships between features and the target variable.
  - Correlation analysis: Correlations between features were analyzed, and highly correlated features were identified.

3. **Feature Engineering**
  - Creating new features: A total of 299 new features were derived from existing ones.
  - Feature selection: The most effective features were selected, and unnecessary features were removed to improve model performance.
4. **Model Training**
  - Training the LightGBM model: The LightGBM regressor was trained on the training data.
  - Hyperparameter optimization: Grid search and cross-validation were used to find the best hyperparameters.
5. **Model Evaluation**
  - Performance metric: The model's performance was evaluated using RMSE (Root Mean Squared Error).
  - Cross-validation: Cross-validation was used to assess the model's generalization ability.

## Algorithm Used
The regression algorithm used in this project:
  - LightGBM Regressor

## Results
  **Number of Features:** 81 (Before feature engineering)
  **Target Variable:** SalePrice (Log-transformed)
  **New Features Created:** 371 (After feature engineering) 
  **Model Performance Metric:** Evaluated using RMSE
  **Best Model RMSE Value:** 0.12814848433361306 (After Log-transformed)
## Conclusion
This project demonstrates how the LightGBM algorithm can be applied to predict house prices. Detailed information about the model's usage and performance is provided. The results show that the model can accurately predict house prices.
  
### Acknowledgments
  - Kaggle for providing the dataset and competition platform.
  - The data science community for sharing knowledge and resources.

## Author
- Ömer Faruk Aytunç

For more details and the complete notebook, visit the [Kaggle Notebook](https://www.kaggle.com/code/omerfarukaytunc/housepricepredict-regression).

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

# Konut Fiyatları Tahmini - LightGBM ile Regresyon Projesi
Bu depo, Kaggle'daki Konut Fiyatları Tahmini yarışması için bir Jupyter Notebook içermektedir. Notebook, veri ön işleme ve LightGBM algoritmasını kullanarak konut fiyatlarını tahmin etmeyi göstermektedir. Bu proje, veri bilimi ve makine öğrenimi konusundaki becerilerimi sergilemek amacıyla portföyümün bir parçasıdır.
Konut Fiyatları - İleri Düzey Regresyon Teknikleri

## İçindekiler
Giriş
Veri Açıklaması
Yöntem
Kullanılan Algoritma
Sonuçlar
Sonuç
Teşekkür
Yazar
Lisans

## Giriş
Konut fiyatlarını tahmin etmek, gayrimenkul ve finans alanında kritik bir görevdir. Bu proje, Kaggle tarafından sağlanan bir veri kümesini kullanarak konut fiyatlarını tahmin etmek için bir regresyon modeli oluşturmayı amaçlamaktadır. Notebook, veri ön işleme, özellik mühendisliği, model eğitimi ve değerlendirme adımlarını içermektedir.

## Veri Açıklaması
Bir ev alıcısına hayalindeki evi tarif etmesini sorsanız, muhtemelen bodrum tavanının yüksekliği veya doğu-batı demiryoluna yakınlığı ile başlamaz. Ancak bu veri kümesi, yatak odası sayısı veya beyaz çitli bir bahçeden çok daha fazlasının fiyat müzakerelerini etkilediğini kanıtlıyor. Iowa, Ames'teki konutların (neredeyse) her yönünü tanımlayan 79 açıklayıcı değişkenle bu yarışma, her evin nihai fiyatını tahmin etmenizi zorlar.

## Yöntem
1. **Veri Ön İşleme**
  - Eksik değerlerin ele alınması: Eksik değerler ortalama, medyan veya mod ile dolduruldu.
  - Kategorik değişkenlerin kodlanması: Kategorik değişkenler, etiket kodlama ve tek sıcaklık kodlama kullanılarak sayısal değerlere dönüştürüldü.
  - Çarpıklık düzeltmesi: Hedef değişken (Satış Fiyatı) normal dağılıma yaklaştırmak için log dönüşümüne tabi tutuldu.
2 **Keşifsel Veri Analizi (EDA)**
  - Veri görselleştirme: Özellikler ile hedef değişken arasındaki ilişkileri anlamak için çeşitli grafikler kullanıldı.
  - Korelasyon analizi: Özellikler arasındaki korelasyonlar analiz edildi ve yüksek korelasyonlu özellikler belirlendi.
3. **Özellik Mühendisliği**
  - Yeni özelliklerin oluşturulması: Mevcut özelliklerden toplam 299 yeni özellik türetildi.
  - Özellik seçimi: En etkili özellikler seçildi ve gereksiz özellikler model performansını artırmak için çıkarıldı.
4. **Model Eğitimi**

  - LightGBM modelinin eğitimi: LightGBM regressor eğitim verileri üzerinde eğitildi.
  - Hiperparametre optimizasyonu: En iyi hiperparametreleri bulmak için Grid Search ve çapraz doğrulama kullanıldı.
5. **Model Değerlendirmesi**

  - Performans metriği: Modelin performansı RMSE (Kök Ortalama Kare Hatası) kullanılarak değerlendirildi.
  - Çapraz doğrulama: Modelin genelleme yeteneğini değerlendirmek için çapraz doğrulama kullanıldı.
## Kullanılan Algoritma
Bu projede kullanılan regresyon algoritması:
  **LightGBM Regressor**
## Sonuçlar
**Özellik Sayısı:** 81 (Özellik mühendisliğinden önce)
**Hedef Değişken:** Satış Fiyatı (Log dönüşümlü)
**Oluşturulan Yeni Özellikler:** 299 (Özellik mühendisliğinden sonra)
**Model Performans Metriği:** RMSE kullanılarak değerlendirildi
**En İyi Model RMSE Değeri:** 0.12814848433361306 (Log dönüşümünden sonra)
## Sonuç
Bu proje, LightGBM algoritmasının konut fiyatlarını tahmin etmek için nasıl uygulanabileceğini göstermektedir. Modelin kullanımı ve performansı hakkında ayrıntılı bilgiler sağlanmaktadır. Sonuçlar, modelin konut fiyatlarını doğru bir şekilde tahmin edebildiğini göstermektedir.

## Teşekkür
Kaggle, veri seti ve yarışma platformunu sağladığı için.
Bilgi ve kaynak paylaşan veri bilimi topluluğuna.
## Yazar
Ömer Faruk Aytunç
Daha fazla ayrıntı ve tam notebook için Kaggle Notebook sayfasını ziyaret edin.

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır - ayrıntılar için LICENSE dosyasına bakın.
   
