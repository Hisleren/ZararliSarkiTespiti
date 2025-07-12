# 🎧 Müzik Dinliyorum, Ne Dinlediğimi Biliyorum

Bu proje, gençlerin dinlediği şarkı sözlerini analiz ederek zararlı içerik (şiddet, madde kullanımı, alkol vb.) barındıran parçaları otomatik olarak tespit eden bir yapay zeka sistemidir. Özellikle aile paketi üzerinden çocuklarını korumak isteyen ebeveynler için geliştirildi.

---

## 📌 Proje Hakkında

📱 **Hedef Uygulama**: Fizy  
🧠 **Proje Sahibi**: Hisleren Aytekin  
🏁 **Hackathon**: Turkcell Hackathon  
🗂️ **Model Türü**: Metin sınıflandırma  
🛠️ **Kullanılan Teknolojiler**:  
- Python  
- scikit-learn  
- Google Colab  
- Doğrusal sınıflandırma algoritmaları  
- Özelleştirilmiş veri kümesi  

---

## 🎯 Amaç

Gençlerin yoğun olarak müzik dinlediği günümüzde, şarkıların içerdiği mesajların davranışları nasıl etkilediği önemlidir. Bu proje:

- Zararlı içerik barındıran şarkı sözlerini tespit eder.  
- Şarkıların yanına otomatik uyarı işareti eklemeyi önerir.  
- Ailelerin, çocuklarının dinledikleri şarkıları takip edebilmesini sağlar.  

---

## 🧪 Veri Kümesi

Bu proje için özel bir veri kümesi oluşturulmuştur.  
- **9 adet** zararlı içerik barındıran şarkı sözü  
- **8 adet** temiz/popüler şarkı sözü  
- Kaynak: Mehmet Işık'ın çalışmaları ve halk arasında bilinen şarkılar  

Veri kümesi küçük olsa da model prototip geliştirme amacıyla yeterli sonuç vermiştir.

---

## ⚙️ Nasıl Çalışır?

1. Kullanıcıdan gelen şarkı sözü alınır.
2. Model, sözü analiz eder.
3. İçerik zararlıysa: 🚫 Uyarı simgesi önerilir.
4. Aile hesabı aktifse: Veliye bildirim yapılır ve içerik kısıtlanabilir.

---
