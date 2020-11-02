# BİLGİLENDİRME

Veriseti 83 adet görüntüden oluşmuş olup bu görüntülerden 72'si hasta, 11'isağlıklıdır. voTT etiketleme aracı ile  72 adet görüntü etiketlenmiştir. voTT klasörü içerisinde etiketli verilerin json dosyaları yer almaktadır.

Roboflow aracı üzerinden RetinaNet Keras formatında csv dosyası çıkarma seçeneği seçilerek bu görüntülerden _annotationsFromRoboflow.csv isimli csv dosyası elde edilmiştir.

Daha sonra bu csv dosyası üzerinde düzenlemeler yapılarak retinaNet.csv dosyası program içerisinde kullanılmıştır. Verisetinde Stone olarak etiketli veriler S, dj_cateter olarak etiketlenen veriler C olarak isimlendirilmiştir.

Bu verisetinde sadece hasta verileri yer almaktadır. Sağlıklı kişilerin görüntülerinde etiketleme yapılmadığı için VoTT aracından export edilmemiştir.

Baseline sınıflandırma sonucu 96.92% (5.10%) bulunmuştur.

