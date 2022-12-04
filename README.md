# Css Seçiciler
Css için 3 Farklı Seçici Türü ve Örnekleri

HTML bir web sitesinin vücudunu oluşturur. CSS ise o vücudun üzerindeki elbiseleri, aksesuarları
ve makyajı oluşturur. HTML kodları kullanılarak hazırlanan web sitelerinde, sayfa tasarımını
özelleştirmek için birtakım kodlar bulunmaktadır. HTML kodları günümüzde kullanılan web sitelerini
tasarlamak için tek başına yetersizdir. Sayfa tasarımını kolayca özelleştirmek, görsel açıdan
zenginleştirmek ve farklı ekran çözünürlüklerine sahip cihazlara uygun hâle getirmek için web sayfaları
hazırlanırken CSS kullanmak gerekmektedir

Satır İçi (Yerel) CSS Ekleme
Doğrudan HTML etiketinin içine CSS ekleme yöntemidir. HTML etiketinin “style” özelliğine değer
olarak CSS kodları girilir. Sadece CSS kodunun eklendiği HTML etiketinde stil değişiklikleri görülür.
Örneğin: <h1 style="background-color: lightblue;">heroinwenc#0001</h1>

Sayfa İçi (Genel) CSS Ekleme
HTML kodlarının <head> </head> bölümüne <style> </style> etiketi içinde CSS ekleme yöntemidir.
Yapılan stil değişiklikleri sadece tek sayfa için geçerlidir.

Sayfa Dışı (Haricî) CSS Ekleme
Web sayfasına uzantısı “css” olan bir stil dosyasını bağlayarak CSS ekleme yöntemidir. Web tasarımcıların
en çok tercih ettiği CSS ekleme yöntemidir. Tüm web sayfalarındaki stil özelliklerini
tek bir merkezden kontrol etmek için kullanılır.
Örneğin;
Head bloğu içine "<link rel="stylesheet" href="stil.css" />" yazın ve stil.css adlı bir dosyada özellik ve değerleri girin.
