# Customer-Segmentation
AVM müşteri segmentasyonu projesi: KMeans ile müşterilerin gelir ve harcama profiline göre segmentlenmesi, CSV çıktısı ve Looker Studio görselleştirmesi ile analiz.
(Looker Studio Dashboard Link: https://lookerstudio.google.com/s/g7C-lBTWht4)

Bu çalışmada müşteriler, yıllık gelir (Annual Income) ve harcama skoru (Spending Score) değişkenleri kullanılarak K-Means kümeleme algoritması ile segmentlere ayrılmıştır. Cinsiyet ve yaş metrikleri de kullanılarak analiz daha da geliştirilebilir.

Elbow yöntemi sonucunda en uygun küme sayısı k = 5 olarak belirlenmiştir.
Elde edilen segmentler, hem görsel analizler hem de küme merkezleri incelendiğinde birbirinden anlamlı şekilde ayrışmaktadır.

Pasta grafiği, müşteri kitlesinin büyük bölümünün orta ve düşük değerli segmentlerde yoğunlaştığını, buna karşın VIP müşteri grubunun sayıca az
olmasına rağmen yüksek harcama potansiyeline sahip olduğunu göstermektedir.

Scatter grafiklerde segmentlerin gelir ve harcama davranışları net biçimde ayrışmış olup, bu durum K-Means modelinin başarılı bir segmentasyon sağladığını
ortaya koymaktadır. Bu segmentasyon, işletmeler için:

VIP müşterilere özel kampanyalar,

Düşük harcama yapan gruplar için teşvik stratejileri,

Orta segment müşterilerin üst segmente taşınması

gibi veriye dayalı pazarlama ve satış stratejileri geliştirilmesine olanak
tanımaktadır.


| Segment Adı                                | Müşteri Profili              | İş Hedefi                                                | Önerilen Aksiyonlar                                                                                        |
| ------------------------------------------ | ---------------------------- | -------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| **VIP Müşteriler (Zengin & Çok Harcayan)** | Yüksek gelir, yüksek harcama | Müşteri sadakatini korumak ve yaşam boyu değeri artırmak | • Kişiselleştirilmiş kampanyalar<br>• Özel müşteri temsilcisi<br>• VIP etkinlik ve erken erişim fırsatları |
| **Zengin ama Az Harcayanlar**              | Yüksek gelir, düşük harcama  | Harcamayı artırmak                                       | • Premium ürün önerileri<br>• Deneme kampanyaları<br>• Kategori bazlı indirimler                           |
| **Genç & Hevesli Harcayıcılar**            | Orta gelir, yüksek harcama   | Sadakat oluşturmak                                       | • Sadakat programları<br>• Oyunlaştırılmış kampanyalar<br>• Mobil uygulama bildirimleri                    |
| **Orta Gelir – Düşük Harcama**             | Orta gelir, düşük harcama    | Sepet büyüklüğünü artırmak                               | • Paket/kombo satışlar<br>• Çapraz satış önerileri<br>• Düşük bütçeli kampanyalar                          |
| **Düşük Değerli Müşteriler**               | Düşük gelir, düşük harcama   | Maliyet optimizasyonu                                    | • Otomatik pazarlama<br>• SMS / e-posta kampanyaları<br>• Yüksek maliyetli aksiyonlardan kaçınma           |


Segment Bazlı Ürün & Kampanya Önerileri

1- VIP Müşteriler (Zengin & Çok Harcayan)

Öne Çıkan İhtiyaç: Özel hissetmek, ayrıcalık

Amaç: Sadakati korumak, yaşam boyu değeri artırmak

Ürün Önerileri; Premium & sınırlı sayıda ürünler, yüksek marjlı özel koleksiyonlar, kişiye özel paketler

Kampanya Önerileri; “Sadece Size Özel” indirimler, erken erişim (new collection preview), VIP günleri / özel alışveriş saatleri


2- Zengin ama Az Harcayanlar

Öne Çıkan İhtiyaç: Değer algısı, güven

Amaç: Harcama sıklığını ve sepet tutarını artırmak

Ürün Önerileri; Premium ürünlerin giriş seviyesi versiyonları, deneme boyu / starter paketler, kalite-vurgulu ürünler

Kampanya Önerileri; İlk alışverişe özel indirim, “Birlikte al – daha avantajlı” kampanyaları, ücretsiz kargo / iade avantajı


3- Genç & Hevesli Harcayıcılar

Öne Çıkan İhtiyaç: Trend, hız, eğlence

Amaç: Sadakat oluşturmak

Ürün Önerileri; Trend ve hızlı tüketilen ürünler, kampanya odaklı popüler ürünler, sınırlı süreli koleksiyonlar

Kampanya Önerileri; Oyunlaştırılmış kampanyalar (puan, rozet, çekiliş), sosyal medya entegrasyonlu indirimler, mobil uygulama özel fırsatları


4- Orta Gelir – Düşük Harcama

Öne Çıkan İhtiyaç: Fiyat avantajı

Amaç: Sepet büyüklüğünü artırmak

Ürün Önerileri; Paket & set ürünler, çok satan ekonomik ürünler, alternatif ürünler

Kampanya Önerileri; “2 al 1 öde” / “3 al %20 indirim”, sepet tutarı bazlı indirimler, dönemsel kampanyalar (maaş günü vb.)


5- Düşük Değerli Müşteriler

Öne Çıkan İhtiyaç: Ulaşılabilir fiyat

Amaç: Maliyetleri kontrol altında tutmak

Ürün Önerileri; İndirimli / outlet ürünler, stok eritme ürünleri, temel ihtiyaç ürünleri

Kampanya Önerileri; SMS / e-posta kampanyaları, toplu indirim günleri, otomatik kampanya kurguları



