# Aygaz_Goruntu_isleme_Bootcamp

# Aygaz Görüntü İşleme Bootcamp 🎓

## Proje Amacı 🔎
Bu projenin amacı, Convolutional Neural Networks (CNN) modellerinin temel prensiplerini pekiştirerek hayvan türlerini sınıflandırma görevinde uygulamalı olarak kullanmaktır. Proje kapsamında, 10 farklı hayvan sınıfının ayrımı yapılacak ve modelin performansı çeşitli test senaryolarıyla değerlendirilecektir.

### Hayvan Sınıfları:
- Collie
- Dolphin
- Elephant
- Fox
- Moose
- Rabbit
- Sheep
- Squirrel
- Giant Panda
- Polar Bear

## Proje Özellikleri
- CNN modelinin tasarlanması ve test edilmesi
- Farklı ışık koşullarında performans analizi
- Renk sabitliği algoritmaları ile manipülasyon etkisinin azaltılması
- Üç farklı test senaryosunun raporlanması ve çözüm önerileri

## Kütüphaneler 📚
Proje için kullanılan başlıca kütüphaneler:
- os, numpy, cv2 (OpenCV)
- sklearn (train_test_split, LabelEncoder)
- tensorflow.keras (ImageDataGenerator, Sequential, Conv2D, MaxPooling2D, Dense, Dropout)
- matplotlib (görselleştirme)

## Veri Seti Hazırlığı 💎
Veri seti, "Animals with Attributes 2" veri setinden belirli sınıfların seçilmesiyle oluşturulmuştur. Her sınıftan maksimum 650 görsel alınarak dengeli bir veri seti oluşturulmuştur.

## Model Mimarisi
1. *Giriş Katmanı:* 128x128x3 boyutunda
2. *Evrişim Katmanları:* 32 adet filtre ile
3. *Havuzlama Katmanları:* MaxPooling2D
4. *Tam Bağlantılı Katmanlar:* 128 nöron ve çıkışta 10 nöron ile softmax aktivasyonu

## Eğitim Süreci
Model, Adam optimizasyon algoritması ve categorical crossentropy kayıp fonksiyonu kullanılarak eğitilmiştir. Eğitim süreci boyunca doğruluk ve kayıp değerleri raporlanmıştır.

## Kullanım
Proje, Jupyter Notebook ortamında çalışmak üzere tasarlanmıştır. Gerekli kütüphanelerin yüklenmesi ve veri setinin hazırlanması ile başlanabilir.

### İhtiyaç Duyulan Kütüphaneler

pip install numpy opencv-python tensorflow scikit-learn matplotlib

# BU PROJEYİ MELİKE NUR ÇOTAK İLE BERABER YAPTIĞIMIZI GRURLA SÖYLEMEK İSTİYORUM KATKILARI İÇİN ÇOK TEŞEKKÜRLER
