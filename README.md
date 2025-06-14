#  Big Data ile Makine Öğrenmesi Analizi

Bu proje, büyük veri setleri üzerinde çeşitli makine öğrenmesi algoritmalarını kullanarak dolandırıcılık tespiti ve sınıflandırma üzerine odaklanır. Veri ön işleme, dengesiz veri sorunlarıyla başa çıkma ve model değerlendirme adımlarını içerir.

---

##  Proje İçeriği

Notebook içerisinde aşağıdaki adımlar gerçekleştirilmiştir:

### 1.  Veri Yükleme ve İnceleme
- Pandas kullanılarak veri yüklenmiş
- Kayıp değerler, veri dağılımları ve dengesizlikler analiz edilmiştir

### 2.  Veri Ön İşleme
- Kategorik değişkenlerin dönüştürülmesi
- Özellik ölçekleme (StandardScaler)
- Veri kümesindeki sınıf dengesizliğini gidermek için **NearMiss** yöntemi uygulanmıştır

### 3.  Modelleme
Aşağıdaki makine öğrenmesi algoritmaları eğitilmiş ve test edilmiştir:

- **Lojistik Regresyon**
- **Random Forest**
- **Decision Tree**
- **K-Nearest Neighbors**
- **Gradient Boosting Classifier**
- **AdaBoost Classifier**
- **XGBoost Classifier**

### 4.  Model Performans Karşılaştırması

Modeller şu metriklerle karşılaştırılmıştır:

- Accuracy (Doğruluk)
- Precision (Kesinlik)
- Recall (Duyarlılık)
- F1 Score
- ROC AUC
- PR AUC
- Specificity

Detaylı karşılaştırma tabloları görselleştirilmiştir.

---

##  Kullanılan Kütüphaneler

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `imbalanced-learn`
- `xgboost`

---

##  Nasıl Kullanılır?

1. Gerekli paketleri yükleyin:
```bash
pip install -r requirements.txt
```

2. Notebook'u çalıştırın:
```bash
jupyter notebook bigData.ipynb
```

3. Her hücreyi sırayla çalıştırarak analiz sürecini takip edin.

---

##  İletişim

Projeyle ilgili sorularınız veya katkı talepleriniz için:  
**Nazar Sıla Kazdal**
