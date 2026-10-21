# AppStüdyo ✦

Kod yazmadan mobil uygulama tasarlamayı hedefleyen AppStüdyo'nun **ilk aşama web editörü**.

## Kullanım

`index.html` dosyasını bir web tarayıcısında açın. Projeler, ekranlar ve bileşenler üzerinden uygulama taslağı oluşturun.

### Mevcut işlevler
- Yeni proje oluşturma ve projeler arasında geçiş
- Ekran ekleme, yeniden adlandırma ve silme
- Başlık, metin, buton, kart, görsel yer tutucu, ayırıcı, etiket, form alanı bileşenleri
- Telefon üzerinde canlı tasarım önizlemesi
- Bileşen düzenleme, kopyalama, silme ve sıra değiştirme
- Uygulama adını ve marka rengini özelleştirme
- Tarayıcıda yerel otomatik kayıt (`localStorage`)
- JSON dışa/içe aktarma
- Masaüstü ve mobil uyumlu panel

## Geliştirme durumu

Bu depo şu anda bir **arayüz prototipi** içerir. Henüz gerçek APK/AAB/IPA üretimi, Supabase üyeliği ve bulut depolaması, gerçek ödeme, bildirim ve uygulama mağazalarına otomatik yayın özellikleri bulunmaz. Public depo kaynak kodunu herkese açar; projeler ve kullanıcı verileri şimdilik kullanan kişinin tarayıcısında saklanır.

## GitHub Pages ile yayınlama

1. Repo **Settings** → **Pages** açın.
2. **Build and deployment** → **Deploy from a branch** seçin.
3. Branch olarak **main**, klasör olarak **/(root)** seçip kaydedin.
4. Yayın gerçekleştiğinde site adresi normalde `https://iyiyolakademi-cpu.github.io/app-studyo/` olur. Yayın tamamlanmadan bağlantı çalışmayabilir.

## Sonraki aşama

Uygulama şablonları ve gelişmiş sürükle-bırak düzenleme; Supabase Auth, Storage ve Row Level Security; ardından gerçek mobil derleme altyapısı.

> Güvenlik: API anahtarlarını veya servis anahtarlarını bu public depoya koymayın. Gerçek kullanıcı verileri için yetkilendirme ve sunucu politikaları kurulmadan sistemi ticari kullanıma açmayın.
