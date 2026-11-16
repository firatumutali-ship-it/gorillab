# Goril Lab VR - Güncellenmiş sürüm

## Eklenen / tamamlanan özellikler
- SHOP: Kozmetik mağazası; coin ile renk ve kozmetik satın alma.
- TECH TREE: Gold ile Hileci Tarayıcı, Ödül Artışı ve Nadir Hileci Algısı yükseltmeleri.
- Hileci botlar: Yaklaşık %14 doğma ihtimali; normal hileciler Fly kullanır.
- Nadir hileciler: Daha düşük ihtimalle Noclip, Invincible veya Fly yeteneklerinden biriyle doğar.
- Hilecilerin parlaması ve HILECI etiketi yalnızca STAFF / ADMIN / OWNER rolünde görünür.
- STAFF yönetim bilgisayarındaki GÖREV sekmesi yalnızca yetkili rolde görünür.
- Hileci botu STAFF bilgisayarından banlamak +10 Gold verir; Ödül Artışı yükseltmesi ödülü artırır.
- STAFF odasına bot girişi engellendi. Botlar odanın içine değil girişine toplanır.
- STAFF odaya girince botlar "LAN STAFF GELDİ OHA" diye bağırır ve girişte bekler.
- STAFF odadan herhangi bir hammer ile çıkınca botlar kaçar.
- Nadir Invincible botlar hammer darbelerinden etkilenmez; yine de yönetim bilgisayarından banlanabilir.

## Kontroller / notlar
- Quest tarayıcısında oyunu açıp VR başlat. Masaüstü test için URL sonuna `?desktop` eklenebilir.
- Staff kodları mevcut projedeki gibi: `1907` Owner, `4242` Admin, `1234` Staff. Yayına koymadan önce bunları değiştir.
- Multiplayer menüsü projede henüz tamamlanmış çevrimiçi altyapı değildir.

## Dosyalar
- `index.html` ve `Goril Lab VR.html`: Oyun
- `manifest.webmanifest`: PWA bilgileri
- `sw.js`: çevrimdışı önbellek
