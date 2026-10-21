# AppStüdyo — Uygulama Oluşturma Stüdyosu

Mobiroller benzeri bir iş akışından esinlenen fakat kendine ait tasarıma ve koda sahip uygulama oluşturma platformu prototipi.

## Aktif modüller
1. **Özel Ekran:** Zengin metin veya HTML/CSS/JavaScript kaynak kodu; kod sekmeleri, tam ekran düzenleme, HTML çıktısı, ekran kopyalama/silme/sıralama, akademi örneği.
2. **Alt Menü:** En fazla 5 bağlantı; menü adı, ekran hedefi, öğe sıralama ve alt menüyü kapatma.

## Panel
- Genel Bakış, Modül Kütüphanesi, İçerik Düzenle, Alt Menü, Tasarım & Marka, Yayınlama
- Sol tarafta sürükle-bırak ekran listesi, ortada geniş çalışma alanı, sağda canlı telefon/geniş ekran önizlemesi
- Proje oluşturma ve seçimi; otomatik tarayıcı kaydı; JSON içe/dışa aktarma
- İyi Yol Akademi tarzı örnek ekran oluşturma
- Taslak yayınlama kontrol listesi

## Kullanım
`index.html` dosyasını açın veya GitHub Pages üzerinde `main` dalının root klasörünü yayınlayın. İnternet yayını etkinse adres: https://iyiyolakademi-cpu.github.io/app-studyo/

## Güvenlik ve sınırlamalar
Bu bir **web tabanlı editör prototipidir**, gerçek APK/AAB/IPA üreticisi değildir. Kullanıcı oturumları, Supabase bulut kayıtları, ekip rolleri, ödeme, medya yükleme, native mobil derleme ve mağaza yayını henüz kurulu değildir. Veri tarayıcı localStorage alanında kalır ve veri kaybını önlemek için JSON yedeklenmelidir. Özel kaynak kodu sandbox iframe ile kısıtlanmış olsa da güvenli olduğu garanti edilemez: yalnızca güvendiğiniz kodları kullanın. Çıktı HTML'si, seçilen **tek ekranı** oluşturur ve güvenilmeyen kod için güvenli yayın ortamı değildir.

## Planlanan sonraki aşama
1. Gerçek kullanıcı hesapları, Supabase RLS ve proje depolama.
2. Dosya/medya yönetimi, geri alma-sürüm geçmişi ve güçlü kod editörü.
3. Mobil uygulama çalışma zamanı, Android ve iOS derleme ve mağaza yayınlama altyapısı.
