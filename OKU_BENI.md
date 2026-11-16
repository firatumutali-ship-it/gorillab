# Gorilla Lab VR — Özellik güncellemesi

## Haritadaki fiziksel istasyonlar
- SHOP tezgâhı: Yaklaşınca E ile açılır. Gold ile Neon renk, Altın renk ve Mavi aura alınabilir.
- TECH TREE istasyonu: Yaklaşınca E ile açılır. Gold ile Sapan, Yay, Ok paketi, Kılıç, Enerji Blaster ve üç yükseltme satın alınabilir.
- ROOM COMPUTER: Yaklaşınca E ile açılır. VR panelindeki sayı tuşlarıyla 4 haneli oda kodu ayarlanabilir.
- İstasyon tezgâhlarına çarpışma kutuları eklendi. Canavarların Shop alanına girişi engellendi.

## Oynanış
- Oyuncu avatarında kol parçaları gizlendi; eller görünür kalır.
- Silah satın aldıktan sonra sağ elde silah modeli görünür. F ile yakındaki hedefe saldırılır. Yay kullanımı ok tüketir.
- Hileci botlar mevcut bot sisteminde ara sıra doğar. Normal hileciler Fly; nadir hileciler Fly, Noclip veya Invincible özelliği alabilir.
- Hileci parıltısı ve etiketi yalnızca Staff / Admin / Owner tarafından görülür.
- Staff rolündeyken yakındaki hileci botu B ile banlayabilirsin. Her ban Gold verir; Ban Ödülü yükseltmesi ödülü artırır.
- Günlük görev ekranı J ile açılır. Her gün rastgele bir görev seçilir. Staff için ayrıca hileci banlama görevi bulunur.
- Günlük giriş ödülü mevcut sistem üzerinden +10 Gold olarak verilir.

## Staff Room
- Botların Staff Room içine girmesi engellenir; etkinlikte giriş kapısının dışında toplanırlar.
- Staff içeri girince botlar "LAN STAFF GELDİ OHA" diye bağırır.
- Staff herhangi bir hammer ile çıkınca botlar kaçar.

## Kontroller
- E: Yakındaki Shop / Tech Tree / Computer istasyonunu kullan
- F: Satın alınmış silahla saldır
- B: Staff olarak yakındaki hileci botu banla
- J: Günlük görevleri göster
- Esc: Açık paneli kapat
- VR: Açılan istasyon panellerine elini uzatıp düğmelere dokun

## Önemli test notu
- JavaScript sözdizimi kontrol edildi ve ZIP arşivi doğrulandı.
- Meta Quest üzerinde gerçek cihaz testi bu paket hazırlanırken yapılamadı; ilk açılışta VR kontrolü ve istasyonların konumları denenmelidir.
- Oda kodu yerel tarayıcıda saklanır. Projedeki multiplayer menüsü tek başına tam çevrimiçi oda sunucusu değildir.

## Dosyalar
- `index.html` ve `Goril Lab VR.html`: Oyun
- `manifest.webmanifest`: PWA bilgileri
- `sw.js`: çevrimdışı önbellek
