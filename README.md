# 🛒 Superstore Satış Analizi

Bu proje, bir süpermarketin satış verileri üzerinden çeşitli analizleri içermektedir.
Superstore satış verileri üzerinde yapılan temel veri analizi çalışmasını içermektedir.  
Veri analizi Google Colab ortamında gerçekleştirilmiş, sonuçlar grafiklerle desteklenmiştir.

## 📁 Veri Seti

- `train.csv`: Satış verilerini içerir.

## 📊 Yapılan Analizler

### ✅ v1: İlk Dosya Yükleme ve İnceleme
- CSV dosyası yüklendi
- İlk 5 satır ve sütunlar incelendi

### ✅ v2: Aylık Satış Analizi
- `Order Date` sütunu datetime formatına çevrildi
- Aylık toplam satışlar hesaplandı ve grafik çizildi

![sales_chart](superstore_v2_chart.png)

### ✅ v3: En Çok Satılan 5 Alt Kategori

- Alt kategori bazında toplam satışlar hesaplandı
- En yüksek satışa sahip 5 kategori belirlendi

![Top5_SubCategories](superstore_v3_chart.png)

## 🔍 Kullanılan Teknolojiler

- Python 🐍
- Pandas
- Matplotlib
- Google Colab
- GitHub

---

## 📈 Yapılan Analizler

1. 📍 **En çok satış yapılan ilk 5 şehir**
2. 📊 **Kategoriye göre toplam satış analizi**
3. 📆 **Aylık toplam satış grafiği (resample yöntemiyle)**
4. 🔎 Eksik veri ve tarih biçimi kontrolü (`errors='coerce'` kullanıldı)

---

## 🚀 Nasıl Kullanılır?

1. Bu repoyu `git clone` ile bilgisayarına çekin.
2. `superstore_analysis_v3.ipynb` dosyasını Google Colab ya da Jupyter Notebook ile açın.
3. Gerekli kütüphaneleri yükleyin ve hücreleri çalıştırın.

---

## 📌 Notlar

- Bu analiz, başlangıç düzeyinde veri görselleştirme ve zaman serisi analizi çalışmasıdır.
- Daha ileri analizler (ortalama teslim süresi, segment bazlı müşteri analizi vb.) bir sonraki sürümde planlanmaktadır.

---

## 👨‍💻 Geliştirici

- Yasin Bağrıaçık  
- [GitHub Profilim](https://github.com/yassinbagriacik)

---
