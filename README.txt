HÜR TAŞ YAPI YÖNETİM — başlangıç PWA paketi

İçerik: index.html, style.css, app.js, manifest.json, sw.js ve uygulama ikonları.

Kurulum için bu dosyalar HTTPS destekleyen statik bir web barındırma hizmetine yüklenmelidir. Ardından URL iPhone Safari'de açılır ve Paylaş > Ana Ekrana Ekle yapılır. İlk açılışta internet açık olsun ki uygulama dosyaları çevrimdışı kullanım için önbelleğe alınabilsin.

Gizlilik: Uygulama müşteri ve işletme verilerini sunucuya gönderen bir özellik içermez; kayıtlar localStorage ile bu web uygulamasının cihazdaki yerel alanında tutulur. Yedekleme JSON dosyası olarak kullanıcı tarafından başlatılır. Safari/site verileri silinirse veya uygulama kaldırılırsa yerel kayıtlar kaybolabilir; düzenli yedek alın.

Bu bir başlangıç sürümüdür. Stok hareketinin cari hesaba otomatik bağlanması, tedarikçi borçları, maaş/personel, PDF belgeleri, fotoğraflar ve ayrıntılı raporlar henüz eklenmemiştir. Gerçek kayıtlar öncesinde test edin.
