# 🩺 Tırnak Anomali Tespiti – Yapay Zekâ Destekli Hastalık Teşhis Sistemi

## 📘 Proje Hakkında

Bu çalışma, tırnaklarda oluşan anomalilerden yola çıkarak **olası sağlık problemlerinin erken teşhisine destek olmayı** amaçlayan yapay zekâ tabanlı bir sistemdir.  
Proje, **üniversite bitirme projesi kapsamında hazırlanmış** olup, tırnak yüzeyindeki **renk, şekil ve doku değişikliklerini** analiz ederek kullanıcıya ön tanı niteliğinde bilgilendirme sunar.

## 🧠 Proje Amacı

* Tırnak anomalilerini yapay zekâ ile tespit etmek
* Görüntü işleme ile tırnak tiplerini sınıflandırmak
* Mobil arayüz üzerinden kullanıcıya sonuçları sunmak
* Erken teşhise ve farkındalığa katkı sağlamak

## ⚙️ Sistem Mimarisi

Proje dört ana bileşenden oluşuyor:

1. **Veri Toplama ve Etiketleme**
   * CVAT aracı kullanılarak tırnak görüntüleri etiketlenmiştir.
2. **Model Eğitimi**
   * YOLOv8s ve CNN tabanlı modeller, PyTorch ortamında eğitilmiştir.
3. **API Entegrasyonu**
   * Python tabanlı API ile model sonuçları mobil arayüze aktarılmıştır.
4. **Mobil Uygulama**
   * React Native–Expo ile geliştirilmiş, Firebase veritabanı kullanılmıştır.

## 🖼️ Proje Görselleri

> Aşağıdaki görseller tamamen proje ekibine aittir. Yayın veya paylaşım için izin gerekmektedir.

**Mobil Arayüz Örnekleri**  
![Mobil Arayüz](./images/app_screenshot1.jpg)  
![Tırnak Anomalileri](./images/app_screenshot3.jpg)
![Analiz Sonucu](./images/app_screenshot2.jpg)


## 🧩 Kullanılan Teknolojiler

| Katman          | Teknoloji             |
| --------------- | --------------------- |
| Görüntü İşleme  | OpenCV, Python        |
| Derin Öğrenme   | YOLOv8s, CNN, PyTorch |
| Veri Etiketleme | CVAT                  |
| Mobil Uygulama  | React Native, Expo    |
| Veritabanı      | Firebase              |
| API             | Python (Flask)        |

## 📊 Model Performansı

* **Genel doğruluk:** %92-93  
* **Ortalama F1 Skoru:** 0.87  
* **Anomaliler:** Çomak tırnak, melanonişi, lökonişi, sarı tırnak ve diğer 11 sınıf

## 📜 Sonuç

Proje, tırnak anomalilerine dayalı **yapay zekâ destekli mobil sağlık çözümü** sunmaktadır.  
Hem bireysel kullanıcılar hem de sağlık çalışanları için **erken teşhisi destekleyici bir araç** olarak değerlidir.

## 🔒 Not

* Kod ve veri seti paylaşılmamaktadır (akademik makale süreci devam ediyor)  
* Görseller ve içerik tamamen proje ekibine aittir

## 📄 Lisans

Tüm hakları saklıdır. 

