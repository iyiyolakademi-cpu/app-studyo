# AppStüdyo — Profesyonel Ekran Oluşturucu

Mobiroller benzeri modüler bir uygulama oluşturma platformu geliştirme projesi.

## Güncel modüller
- **Özel Ekran:** Çoklu ekran, zengin metin düzenleyici veya ayrı HTML, CSS ve JavaScript kod editörü.
- **Alt Menü:** En fazla beş gezinme öğesi, ekranlara bağlama, sıralama ve görünürlük.

## Editör iyileştirmeleri
- Geniş ve yüksekliği ayarlanabilir kaynak kodu yazma alanı
- Tam ekran kod düzenleme modu (Esc ile çıkış)
- Kod alanında Tab tuşuyla girinti
- Telefon önizlemesini genişletme
- Seçili ekranı HTML olarak indirme
- İyi Yol Akademi tarzı örnek uygulama ekranı şablonu
- Tarayıcıya otomatik proje kayıtları; JSON içe ve dışa aktarma
- Masaüstü ve mobil cihazlarda kullanılabilir panel

## Başlatma
`index.html` dosyasını açın. GitHub Pages etkinse `https://iyiyolakademi-cpu.github.io/app-studyo/` bağlantısından erişebilirsiniz.

## Akademi şablonu
Özel bir ekran seçin, **Akademi Örneği** düğmesine basın ve önizlemeyi inceleyin. Bu eylem seçili ekranın içeriğini değiştirir, öncesinde JSON yedek alın.

## Gerçek ürün için eksikler
Bu sürüm tarayıcıda çalışan bir prototiptir. APK/AAB/IPA derleme, çok kullanıcılı bulut veri tabanı, kimlik doğrulama, medya depolama ve mağazaya gönderim henüz yoktur. HTML dışa aktarma **tek ekran** üretir, tam mobil paket üretmez. Kaynak kodu önizlemesi sandbox iframe içinde çalışır fakat tam güvenlik garantisi sağlamaz. Sadece güvendiğiniz kaynak kodlarını kullanın. Tarayıcı depolaması silinirse JSON yedeği olmayan veriler kaybolabilir.

## Yol haritası
1. Üretim düzeyinde proje ve ekran veri modeli; editörde sürüm geçmişi.
2. Supabase Auth + güvenli RLS + bulutta proje kaydı.
3. Medya ve içerik kütüphanesi, gerçek menü ve sayfa navigasyonu.
4. Mobil uygulama üretim altyapısı ve Android/iOS test/yayınlama.
