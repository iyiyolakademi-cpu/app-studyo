# AppStüdyo — Özel Ekran ve Alt Menü

Kodsuz uygulama oluşturucu projesinin ilk editör sürümü.

## Aktif modüller (yalnızca 2)
- **Özel Ekran:** Ekran ekle/sil, başlık düzenle, zengin metin görsel editörü veya ayrı HTML / CSS / JavaScript kaynak kodu yaz.
- **Alt Menü:** En fazla 5 gezinme öğesi, ekran hedefi seçme, etiket değiştirme, sıralama, menüyü açma/kapatma.

## Diğer işlevler
- Birden fazla proje, proje adı ve marka rengi
- Kaynak kodunu ayrı sandbox iframe içinde çalıştıran telefon önizlemesi
- Otomatik tarayıcı kaydı ve JSON yedekleme / içe aktarma
- Masaüstü ve mobil uyumlu tasarım

## Çalıştırma
`index.html` dosyasını açın veya GitHub Pages üzerinden yayınlayın. Repository Settings → Pages → Deploy from branch → main / root.

## Sınırlar ve güvenlik
Bu aşama **tasarım prototipidir**, Android/iOS paketleri üretmez. Kullanıcı girişleri, bulut kaydı, gerçek içerik yönetimi, e-ticaret ve ödeme modülleri eklenmemiştir. HTML/CSS/JS kodu önizlemede kısıtlı (sandbox + CSP) bir çerçevede çalışır; bu tam güvenlik garantisi değildir. Kaynak kodunu yalnızca güvendiğiniz yerden alın. Zengin metin ve JSON içe aktarma deneme amaçlıdır. Projeleri JSON olarak yedekleyin; tarayıcı verileri silinirse yerel kayıt kaybolur.

Sonraki aşama: Supabase kimlik doğrulama, kullanıcıya özel proje depolama ve gerçek uygulama üretimi.
