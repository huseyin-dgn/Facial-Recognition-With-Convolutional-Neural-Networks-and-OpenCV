# 📘 Facial-Recognition-With-Convolutional-Neural-Networks-and-OpenCV

## 🎯 Proje Amacı

Bu proje, gerçek zamanlı yüz tanıma sistemlerinin derin öğrenme (CNN - TF) ve görüntü işleme (OpenCV) teknolojileriyle nasıl geliştirilebileceğini göstermeyi amaçlar.  
Canlı kamera görüntüleri üzerinden yüz tespiti ve tanıma işlemleri gerçekleştirilir.

---

## 🧠 Kullanılan Yöntemler

- ✅ Convolutional Neural Networks (CNN)
- ✅ Transfer Learning (ResNet50)
- ✅ OpenCV ile Kamera Akışı
- ✅ Veri Artırma (Augmentation)
- ✅ Gerçek Zamanlı Görüntü Sınıflandırma

---

## ⚠️ Uyarılar ve Bilgilendirme

### 1️⃣ Veri Seti Uyarısı
**VERİ SETİ BULUNMAMAKTADIR.**  
Bu proje, 4 sınıflı çıktı üretmektedir ve **kullanılmak istenilen herhangi bir veri seti ile uyumlu** olacak şekilde tasarlanmıştır.

---

### 2️⃣ Veri Düzenleme
`veri_düzenleme.ipynb` dosyasında **veri artırma (augmentation)** işlemleri uygulanmaktadır.  
Bu sayede modelin genelleme yeteneği artırılmıştır.

---

### 3️⃣ Model Eğitimi
`model.ipynb` dosyasında, **ResNet50** tabanlı transfer learning modeli kullanılarak eğitim işlemi gerçekleştirilmektedir.

---

### 4️⃣ Model Tahmini
`model_pred.ipynb` dosyasında, **eğitilmiş hazır model yüklenir** ve test verileri üzerinde tahminleme (predict) işlemi yapılır.

---

### 5️⃣ Gerçek Zamanlı Uygulama
`gercek_zaman.ipynb` dosyasında, **kamera görüntüsü gerçek zamana taşınır** ve gelen görüntüler anlık olarak sınıflandırılarak **gerçek zamanlı karar verilir**.

---

### 6️⃣ Alternatif CNN Modeli
`cnn_model.ipynb` dosyasından, istenirse **alternatif olarak CNN tabanlı bir modele de erişim sağlanabilir.**

---

### 7️⃣ Model Ağırlıklarına Erişim Sorunu
`.h5` uzantılı model dosyalarına **erişim sağlanamıyorsa** (örneğin GitHub bellek kısıtlaması nedeniyle),  
`model.ipynb` veya `cnn_model.ipynb` dosyaları üzerinden **modeli yeniden eğitip `.h5` formatında kaydedebilir** ve kullanabilirsiniz.

> 📌 Bu işlem, modelin yeniden eğitilmesini sağlar ve projenin çalışabilirliğini korur.

---


