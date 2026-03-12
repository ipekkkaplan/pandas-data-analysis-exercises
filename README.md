# Pandas Veri Analizi Uygulamaları (Titanic & Tips)

Bu depo, veri bilimi ve analitiği dünyasının en temel kütüphanesi olan **Pandas** ile gerçekleştirilmiş kapsamlı veri manipülasyonu ve analiz çalışmalarını içermektedir.

## Projenin Amacı
Bu çalışma, gerçek veri setleri üzerinde karşılaşılan problemleri (eksik veri, yanlış veri tipleri, karmaşık filtreleme ihtiyaçları) Pandas kütüphanesi fonksiyonlarıyla profesyonel şekilde çözmeyi amaçlar.

## Kullanılan Teknolojiler & Kütüphaneler
* **Python 3.x**
* **Pandas:** Veri manipülasyonu ve analizi.
* **Seaborn:** Veri setlerinin temini ve görselleştirme desteği.

## Öne Çıkan Başlıklar

## Titanic Veri Analizi
* **Eksik Veri Yönetimi:** `age` ve `deck` gibi kritik sütunlardaki boş değerlerin medyan ve mod yöntemleriyle doldurulması.
* **Koşullu Filtreleme:** Hayatta kalma oranlarının cinsiyet, yaş ve yolcu sınıfı bazında incelenmesi.
* **Veri Tipleme:** Kategorik verilerin optimizasyonu.

## Tips (Bahşiş) Veri Analizi
* **Gelişmiş Gruplama:** Gün ve zaman dilimlerine göre hesap ve bahşiş ortalamalarının `groupby` ve `agg` ile analizi.
* **Yeni Değişken Üretimi:** Toplam ödeme tutarı üzerinden yeni özellikler (features) eklenmesi.
* **Veri Sıralama:** En yüksek harcama yapan müşterilerin `sort_values` ile tespiti.

## Dosya Yapısı
* `Pandas_Case_Study_Titanic_Tips.ipynb`: Tüm analiz süreçlerini ve kod çıktılarını içeren ana Notebook dosyası.

## Nasıl Çalıştırılır?
1. Bu depoyu klonlayın: `git clone https://github.com/kullanici-adiniz/depo-adiniz.git`
2. Jupyter Notebook veya Google Colab üzerinden dosyayı açın.
3. Gerekli kütüphaneleri yükleyin: `pip install pandas seaborn`
