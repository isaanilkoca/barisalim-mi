# barisalim mi?

Küsmüş sevgiliye gönderilen küçük bir web deneyimi. Mektubu yazan kişi bir link üretir, karşı taraf mektubu açar ve cevabını yine bir linkle geri yollar.

Canlı: https://isaanilkoca.github.io/barisalim-mi/

## Akış
1. **Mektubu yazan:** iki isim ve serbest bir mektup yazar, tema seçer, linki oluşturup gönderir.
2. **Alıcı:** ikiye bölünmüş bir kalp görür. "Hâlâ kırgınım" butonu imleçten ya da parmaktan kaçar (yay-sönüm fiziği), her denemede kalp biraz onarılır.
3. Düşen kalp parçalarını toplar, zarf açılır, mektup daktilo gibi yazılır.
4. Alıcı cevabını yazar ve bir özet seçer. Cevap ayrı bir linke dönüşür ve mektubu yazana gönderilir.
5. **Mektubu yazan:** cevap linkini açar, cevabı okur.

## Teknik
- Tek dosya (`index.html`), bağımlılık yok.
- Sunucu ve veritabanı yok: isimler, mektup ve cevap linkin `#d=` / `#r=` kısmında (URL-güvenli base64) taşınır, hiçbir şey saklanmaz.
- SVG kalp animasyonu, canvas ışık tozu ve parçacıklar, WebAudio ile dosyasız ses.
- 3 tema (bordo, krem, gece), `prefers-reduced-motion` desteği.
- GitHub Pages ile ücretsiz barındırılır.

## Sonraki adımlar
Özel alan adı, fotoğraf ekleme, ödeme ve kalıcı kayıt için sunucu tarafı.
