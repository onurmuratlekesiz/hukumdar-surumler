# Hükümdar

Windows paketini bir klasöre çıkartın ve **Hükümdar.exe** dosyasını açın. ZIP yalnızca bu EXE'yi içerir; Python kurulumu gerekmez. Masaüstü penceresi Edge WebView2 kullanır. Pencere motoru başlatılamazsa uygulama tarayıcıya geçer.

Uygulama internet olmadan hesaplama yapar. Sağ üstteki **Güncellemeler** düğmesiyle yeni sürümü kontrol edin; varsa **İndir**, ardından **Kur ve yeniden başlat** düğmesine basın. İndirilen dosya SHA-256 özetiyle doğrulanır. Kurulum son formu kaydeder, uygulamayı kapatır, eski EXE'nin yanına bir yedek bırakır ve yeni sürümü açar. Uygulama klasörüne yazma izni gerekir. Güncelleme bir tarife yılı seçmez veya kullanıcıya ait özel tarifeleri silmez.

Kayıtlar `%LOCALAPPDATA%\Hukumdar` klasöründedir; uygulama dosyasını değiştirmek bunları silmez. Güncelleme kurulum hataları aynı klasördeki `update.log` dosyasına yazılır. GitHub veya internet erişimi yoksa güncelleme ertelenir; yerel hesaplama devam eder. Dosyayı yazılabilir bir klasörde tutun.

İlk sürümdeki **Hükümdar 2026.exe** kullanıcıları yeni paketi bir kez elle indirip çıkartmalıdır; sonraki sürümler uygulama içinden güncellenebilir.

Kurum ağında güncelleme bağlantısı Windows'un sistem/kullanıcı proxy ve sertifika ayarlarını kullanır. Hata mesajı sertifika, proxy kimlik doğrulaması, DNS veya zaman aşımını belirtir. **Tarayıcıdan indir** düğmesi resmî sürüm sayfasını açar. 2.2.0'da bağlantı hatası alan kullanıcılar 2.2.1'i tarayıcıdan indirip eski EXE kapalıyken değiştirmelidir; kayıtlar korunur. Kurumun erişim kuralları bağlantıyı engelliyorsa bilgi işlem birimiyle görüşün.

Başvurma harcını makbuzdaki ödenmiş tutarla girin. Çıktı hukuki kontrol gerektiren taslaktır. UDF kapalıdır; Word veya TXT kullanın. Sulh/KVYO ve bazı arabuluculuk durumları ek olgular gerektirdiğinden otomatik sonuç üretilmez. Tarifeyi karar tarihine göre kontrol edin.

OML ortak proje imzasıdır. Bu uygulama yapay zekâ ile geliştirilmiştir.

Sürümler: https://github.com/onurmuratlekesiz/hukumdar-surumler/releases/latest
