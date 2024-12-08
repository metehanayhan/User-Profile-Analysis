[EN]
# Age and Generation Prediction Project

## Project Overview

This project aims to tackle the challenges of working with an extremely imbalanced dataset by applying both regression and classification methods. Imbalanced datasets are a common challenge in data science, often compromising model accuracy and reliability. To mitigate these issues, we implemented a range of strategies and models to achieve strong performance across both classification and regression tasks. The focus of this project is on predicting the age and generational group (Millennial, Gen X, Boomer) of users based on their profiles from the OKCupid dating platform. By employing supervised machine learning techniques, the project aspires to build model capable of accurately determining these demographic details from the provided profile data.

## Methodology

1. **Data Preprocessing**
   - Removed rows with missing values.
   - Combined multiple essay columns into a single text feature.
   - Encoded categorical variables using Label Encoding.
   - Transformed specific features like `body_type`, `diet`, `education`, and `drinks` into more general categories.

2. **Exploratory Data Analysis (EDA)**
   - Explored distributions of various features like age, body type, and education.
   - Visualized correlations between features.
   - Identified potential outliers and handled missing data.

3. **Feature Engineering**
   - Created new features such as text length from essays.
   - Generated dummy variables for categorical features.

4. **Model Training**
   - Split the data into training and test sets.
   - Trained different machine learning models (e.g., Linear Regression, Logistic Regression) to predict age and generation.
   - Used metrics like R² score, Mean Squared Error (MSE), and classification accuracy to evaluate model performance.

5. **Model Evaluation**
   - Evaluated the trained models on test data.
   - Analyzed confusion matrices and classification reports for generation prediction.
   - Performed error analysis to improve model accuracy.

## Results

The final models demonstrated satisfactory performance in predicting user age and generation.

[TR]

# Age and Generation Prediction Project

## Proje Genel Bakış

Bu proje, oldukça dengesiz bir veri setiyle çalışmanın zorluklarını ele almayı ve hem regresyon hem de sınıflandırma yöntemlerini kullanarak çözüm üretmeyi amaçlamaktadır. Veri setlerindeki dengesizlik, model doğruluğunu ve güvenilirliğini genellikle olumsuz etkiler. Bu sorunları hafifletmek için çeşitli stratejiler ve modeller uygulanmıştır. Proje, OKCupid adlı platformdaki kullanıcı profillerinden yola çıkarak, yaş ve jenerasyon grubu (Millennial, Gen X, Boomer) tahmini yapmayı hedeflemektedir. Gözetimli makine öğrenimi teknikleri kullanılarak, sağlanan profil verilerinden demografik detayları doğru bir şekilde belirleyebilecek modeller oluşturulması amaçlanmıştır.

---

## Yöntem

1. **Veri Ön İşleme**
   - Eksik veri içeren satırlar temizlendi.
   - Birden fazla metin sütunu (örneğin, essay sütunları) tek bir metin özelliğinde birleştirildi.
   - Kategorik değişkenler Label Encoding yöntemiyle kodlandı.
   - `body_type`, `diet`, `education`, ve `drinks` gibi belirli özellikler daha genel kategorilere dönüştürüldü.

2. **Keşifsel Veri Analizi (EDA)**
   - Yaş, vücut tipi ve eğitim gibi çeşitli özelliklerin dağılımları incelendi.
   - Özellikler arasındaki korelasyonlar görselleştirildi.
   - Potansiyel aykırı değerler belirlendi ve eksik veriler ele alındı.

3. **Özellik Mühendisliği**
   - Essay metinlerinden metin uzunluğu gibi yeni özellikler oluşturuldu.
   - Kategorik özellikler için dummy değişkenler oluşturuldu.

4. **Model Eğitimi**
   - Veri eğitim ve test setlerine bölündü.
   - Yaş ve jenerasyon tahmini için Linear Regression ve Logistic Regression gibi çeşitli makine öğrenimi modelleri eğitildi.
   - Model performansını değerlendirmek için R² skoru, Mean Squared Error (MSE) ve sınıflandırma doğruluğu gibi metrikler kullanıldı.

5. **Model Değerlendirme**
   - Eğitilen modeller test verisi üzerinde değerlendirildi.
   - Jenerasyon tahmini için karışıklık matrisleri ve sınıflandırma raporları analiz edildi.
   - Model doğruluğunu artırmak için hata analizi yapıldı.

---

## Sonuçlar

Son modeller, kullanıcıların yaşını ve jenerasyonlarını tahmin etmede tatmin edici bir performans göstermiştir. Elde edilen sonuçlar, dengesiz veri setleri üzerinde güçlü tahmin modelleri oluşturmanın mümkün olduğunu ortaya koymaktadır.
