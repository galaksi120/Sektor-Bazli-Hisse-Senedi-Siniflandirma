# Sektor-Bazli-Hisse-Senedi-Siniflandirma
# 📊 Hisse Senedi Sektör Tahmin Projesi
**Sektor-Bazlı Hisse Senedi Sınıflandırma**

Bu proje, **web scraping** ve **yfinance** entegrasyonu ile farklı sektörlerden **15 yıllık hisse senedi verisini** toplayarak, zaman serisi analizi ve makine öğrenmesi modelleri ile **sektör benzerliği tahmini** yapmayı amaçlamaktadır.  

---

## 🚀 Proje Özeti
- **Veri Toplama:**  
  - Web scraping ve `yfinance` ile 15 yıllık hisse senedi verileri toplandı.  
- **Veri Ön İşleme:**  
  - Eksik veriler temizlendi.  
  - Zaman serisi özellikleri, `tsfresh` kullanılarak çıkarıldı.  
- **Modelleme ve Hiperparametre Optimizasyonu:**  
  - Veriler etiketlenerek **5 katlı cross-validation** uygulandı.  
  - Kullanılan modeller: **Random Forest, Gradient Boosting, XGBoost, CatBoost**  
  - Her model için **GridSearchCV** ile hiperparametre optimizasyonu yapıldı.  
  - En yüksek doğruluk değerine sahip model seçildi.  
- **Tahmin:**  
  - Seçilen model ile yeni hisse senetlerinin eğitim finans teknoloji sektörlerinden hangisine **benzediği tahmin edildi**.  

---

## 📂 Kullanılan Teknolojiler
- **Python**  
- **yfinance** → Hisse senedi verisi çekme  
- **BeautifulSoup / Requests** → Web scraping  
- **Pandas / NumPy** → Veri işleme  
- **tsfresh** → Zaman serisi özellik çıkarımı  
- **scikit-learn** → Modelleme, Cross-validation, GridSearchCV  
- **XGBoost**  
- **CatBoost**  
- **Matplotlib  → Veri görselleştirme  

---

## 🔄 Çalışma Adımları
1. **Veri Toplama** → Web scraping + yfinance  
2. **Veri Temizleme** → Eksik değerlerin işlenmesi  
3. **Özellik Çıkarımı** → tsfresh ile zaman serisi özellikleri  
4. **Model Eğitimi** → RF, GB, XGBoost, CatBoost modelleri  
5. **Hiperparametre Optimizasyonu** → GridSearchCV  ile parametre ayarlamaları  
6. **Model Seçimi** → En yüksek doğruluk veren modelin belirlenmesi  
7. **Tahmin** → Yeni hisselerin sektör benzerliği tahmini  

---

## 📊 Sonuçlar
- Farklı modeller karşılaştırıldı.  
- **Hiperparametre optimizasyonu** sayesinde modellerin doğruluk oranı artırıldı.  
- En iyi performans gösteren model, yeni veriler üzerinde **sektör tahmininde** başarıyla kullanıldı.  
- Çıktılar, **yatırım araştırmaları** ve **sektör analizlerinde** destekleyici bir araç olarak değerlendirilebilir.  
