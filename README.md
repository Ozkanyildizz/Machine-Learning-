# 🤖 Python ile A'dan Z'ye Makine Öğrenmesi ve Derin Öğrenme

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras)

Bu depo, kapsamlı "Python ile Makine Öğrenmesi" eğitimi boyunca geliştirdiğim projeleri, aldığım notları ve uyguladığım algoritmaları içermektedir.

Eğitim süresince veri ön işlemeden başlayıp, denetimli/denetimsiz öğrenme, doğal dil işleme (NLP), pekiştirmeli öğrenme (RL) ve derin öğrenme (Deep Learning) konularına kadar geniş bir yelpazede uygulamalar yapılmıştır.

---

## 📚 Müfredat ve Kazanımlar

Bu repo aşağıdaki ana başlıklar altında toplanmış çalışmaları içerir:

### 1. 🧹 Veri Ön İşleme (Data Preprocessing)
Makine öğrenmesi modellerinin başarısı için kritik olan veri hazırlığı aşamaları.
* **Eksik Veriler (Missing Values):** Ortalama ile doldurma (Imputation).
* **Kategorik Veriler:** LabelEncoder ve OneHotEncoder dönüşümleri.
* **Veri Bölme:** Train/Test Split stratejileri.
* **Ölçekleme (Scaling):** StandardScaler ve MinMaxScaler ile veriyi normalize etme.

### 2. 📈 Tahmin Algoritmaları (Regression)
Sayısal verilerin tahmini ve trend analizi.
* **Doğrusal Modeller:** Simple & Multiple Linear Regression.
* **Polinom Regresyon:** Doğrusal olmayan ilişkilerin modellenmesi.
* **SVR (Support Vector Regression):** Destek vektörleri ile tahmin.
* **Ağaç Bazlı Modeller:** Decision Tree ve Random Forest Regressor.
* **Değerlendirme:** $R^2$ Score ve Adjusted $R^2$ analizleri.

### 3. 🎯 Sınıflandırma (Classification)
Verilerin belirli sınıflara ayrılması (Örn: Diyabet Tespiti, Iris Çiçeği).
* **Logistic Regression:** Olasılık tabanlı sınıflandırma.
* **K-NN (K-Nearest Neighbors):** Komşuluk tabanlı sınıflandırma.
* **SVM (Support Vector Machine):** Kernel trick kullanımı.
* **Naive Bayes:** Olasılık temelli (Gaussian/Bernoulli) sınıflandırma.
* **Model Değerlendirme:** Confusion Matrix, Accuracy Paradox, ROC Eğrisi.

### 4. 🧩 Kümeleme (Clustering) & Birliktelik (Association)
Etiketlenmemiş verilerdeki desenlerin keşfi (Unsupervised Learning).
* **K-Means:** K-Means++ ve "Elbow Yöntemi" ile optimum küme sayısını bulma.
* **Hiyerarşik Kümeleme:** Dendrogram analizi.
* **Birliktelik Kuralı:** Apriori Algoritması (Sepet Analizi).

### 5. 🤖 Pekiştirmeli Öğrenme (Reinforcement Learning)
Ajan (Agent) tabanlı öğrenme sistemleri.
* **UCB (Upper Confidence Bound):** Keşfetme-Sömürme (Explore-Exploit) dengesi.
* **Thompson Sampling:** Olasılıksal yaklaşım.

### 6. 💬 Doğal Dil İşleme (NLP)
Metin madenciliği ve duygu analizi.
* **Metin Temizliği:** Stop words, Stemming, Tokenization.
* **Bag of Words:** CountVectorizer ile metni sayısal vektöre çevirme.
* **Uygulama:** Restoran yorumları üzerinden duygu analizi (Sentiment Analysis).

### 7. 🧠 Derin Öğrenme (Deep Learning)
Yapay Sinir Ağları ve modern mimariler.
* **ANN (Artificial Neural Networks):** Keras ile ileri/geri yayılım ağları.
* **CNN (Convolutional Neural Networks):** Görüntü işleme ve sınıflandırma (Giriş seviyesi).
* **Boyut İndirgeme:** PCA (Principal Component Analysis) ve LDA.
* **Model Seçimi:** K-Fold Cross Validation ve GridSearch (Hiperparametre optimizasyonu).
* **Bonus:** XGBoost algoritması kullanımı.

---

## 🛠️ Kullanılan Teknolojiler

Projelerimde aşağıdaki kütüphaneleri aktif olarak kullandım:

| Kütüphane | Amaç |
| :--- | :--- |
| **NumPy** | Matris işlemleri ve sayısal hesaplamalar |
| **Pandas** | Veri manipülasyonu ve DataFrame yönetimi |
| **Matplotlib / Seaborn** | Veri görselleştirme ve grafik çizimi |
| **Scikit-Learn** | Klasik ML algoritmaları |
| **Keras / TensorFlow** | Derin Öğrenme modelleri |
| **NLTK** | Doğal Dil İşleme |

---

## 📂 Proje Dizin Yapısı

Repo içerisindeki klasörleme mantığı şu şekildedir:

```text
.
├── 1_Veri_On_Isleme/          # Eksik veriler, Scaling, Encoding kodları
├── 2_Regresyon/               # Linear, Polynomial, SVR, Random Forest kodları
├── 3_Siniflandirma/           # Logistic, KNN, SVM, Naive Bayes kodları
├── 4_Kumeleme_Birliktelik/    # K-Means, Apriori kodları
├── 5_RL_Pekistirmeli/         # UCB, Thompson Sampling
├── 6_NLP/                     # Metin işleme ve yorum analizi
├── 7_DeepLearning/            # ANN, CNN ve PCA uygulamaları
└── Data/                  # (maaslar.csv, veriler.csv vb.)
```
1. Depoyu klonlayın:
   ```bash
   git clone  https://github.com/Ozkanyildizz/Machine-Learning-.git
   ```
2. Gerekli Kütüphaneleri kurun:
    ```bash 
   pip install -r requirements.txt
   ```

---

<div align="center">

### 👤 Yazar / Author

**Özkan Yıldız**

*Bilgisayar Mühendisliği Öğrencisi* 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/%C3%B6zkan-yildiz/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/Ozkanyildizz)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:yildizozkan211@gmail.com)

</div>

---

