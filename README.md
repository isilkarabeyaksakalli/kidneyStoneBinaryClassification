

Veriseti 83 adet görüntüden oluşmuş olup bu görüntülerden 72'si hasta, 11'i sağlıklıdır. voTT etiketleme aracı ile  72 adet görüntü etiketlenmiştir. voTT klasörü içerisinde orijinal görüntüler ve etiketli görüntülerin json dosyaları yer almaktadır.

Roboflow aracı üzerinden RetinaNet Keras formatında csv dosyası çıkarma seçeneği seçilerek bu görüntülerden _annotationsFromRoboflow.csv isimli csv dosyası elde edilmiştir.  

Verisetinde tek bir görüntüde birden fazla taş ve kateter bulunabildiği için aynı görüntü için birden fazla taş ve kateter konumları satır bazında çıkarılmıştır. 

Elde edilen bu csv dosyası üzerinde düzenlemeler yapılarak retinaNet.csv dosyası program içerisinde kullanılmıştır. İmage isimleri silinmiş, Stone olarak etiketli veriler S, dj_cateter olarak etiketlenen veriler C olarak değiştirilmiştir.

Baseline sınıflandırma sonucu 96.98% (3.70%) bulunmuştur.

Not: Bu verisetinde sadece hasta verileri yer almaktadır. Sağlıklı kişilerin görüntülerinde etiketleme yapılmadığı için VoTT aracından export edilmemiştir.


