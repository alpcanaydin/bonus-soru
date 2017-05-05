# Bonus Soru 🎉

https://www.youtube.com/watch?v=kRknZ6ejQ_8 adresinde bulunan genel JavaScript video'su için 50$ DigitalOcean kredisi ödüllü eğlencelik soru. Soruda kullanılacak hemen hemen her şey'i video'da anlatmaya çalıştım.

**React ve Redux ile Web Uygulaması Geliştirme Video Serisi:** https://www.youtube.com/playlist?list=PL-ohrY_IyV4CUNsDxXDkdT-aAVfrTPXll

Haber datası `data.json`, stop word'ler ise `stop_words.json` dosyasında bulunuyor.

### Yapılması Gereken
`data.json` dosyasındaki `Description` değerlerinde bulunan cümleler içerisindeki kelimelerin kaç defa kullanıldığını bulmak. `stop_words.json` dosyasındaki kelimelerin ise sayımdan çıkarılması gerekiyor.

### Dikkat Edilmesi Gerekenler.

* Büyük-küçük harfin kelimenin sayılmasına etki etmemesi gerekiyor. İZMİR ve izmir tamamen aynı kelimeler olarak sayılmalı.
* For loop kullanmak yasak. Onun yerine olabildiğince Array metodlarına yönelmek gerekiyor.
* Kelimeleri sayarken köklerine ayırmanıza **gerek yok**.
* Sonunda noktalama işareti bulunan kelimelere dikkat etmekte fayda var.
* Cevabınızı bu repo'ya issue olarak veya Youtube'da bu video'ya yorum olarak yazabilirisiniz.

### Beklenen Çıktı
Aşağıdaki sayılar tamamen rastgele yazılmıştır :)

```javascript
{
  izmir: 250,
  elektrik: 843,
  gece: 1350,
  dakika: 4520,
  hava: 3186
  // ...
}
```
