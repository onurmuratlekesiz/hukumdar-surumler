# Hükümdar

Windows paketini bir klasöre çıkartın ve **Hükümdar.exe** dosyasını açın. ZIP yalnızca bu EXE'yi içerir; Python kurulumu gerekmez. Masaüstü penceresi Edge WebView2 kullanır. EXE masaüstü penceresinde açılır; tekrar çalıştırıldığında mevcut pencere öne getirilir. Pencere motoru başlatılamazsa hata mesajı gösterilir.

Uygulama internet olmadan hesaplama yapar. Sağ üstteki **Güncellemeler** düğmesiyle yeni sürümü kontrol edin; varsa **İndir**, ardından **Kur ve yeniden başlat** düğmesine basın. İndirilen dosya SHA-256 özetiyle doğrulanır. Kurulum son formu kaydeder, uygulamayı kapatır, eski EXE'nin yanına bir yedek bırakır ve yeni sürümü açar. Uygulama klasörüne yazma izni gerekir. Güncelleme bir tarife yılı seçmez veya kullanıcıya ait özel tarifeleri silmez.

Kayıtlar `%LOCALAPPDATA%\Hukumdar` klasöründedir; uygulama dosyasını değiştirmek bunları silmez. Güncelleme kurulum hataları aynı klasördeki `update.log` dosyasına yazılır. GitHub veya internet erişimi yoksa güncelleme ertelenir; yerel hesaplama devam eder. Dosyayı yazılabilir bir klasörde tutun.

**Güncellemeden sonra açılmıyorsa:** 2.2.5 veya daha yeni ZIP paketini resmî sürüm sayfasından indirip yeni bir klasöre çıkartın ve içindeki EXE'yi çalıştırın. Kayıt klasörünü silmeyin. 2.2.5, yeniden başlatmayı eski sürümün geçici dosyalarından ayırır; kurucu başlamazsa uygulamayı kapatmaz. Kurum betik çalıştırmayı engellerse elle dosya değiştirerek güncelleyin; güvenlik ayarlarını değiştirmek gerekmez. Başlatma hataları `update-installer.log`, dosya değiştirme/açılış kontrolü `update.log` içindedir.

İlk sürümdeki **Hükümdar 2026.exe** kullanıcıları yeni paketi bir kez elle indirip çıkartmalıdır; sonraki sürümler uygulama içinden güncellenebilir.

Kurum ağında güncelleme bağlantısı Windows'un sistem/kullanıcı proxy ve sertifika ayarlarını kullanır. Hata mesajı sertifika, proxy kimlik doğrulaması, DNS veya zaman aşımını belirtir. **Tarayıcıdan indir** düğmesi resmî sürüm sayfasını açar. 2.2.0'da bağlantı hatası alan kullanıcılar 2.2.1'i tarayıcıdan indirip eski EXE kapalıyken değiştirmelidir; kayıtlar korunur. Kurumun erişim kuralları bağlantıyı engelliyorsa bilgi işlem birimiyle görüşün.

Başvurma harcını makbuzdaki ödenmiş tutarla girin. Çıktı hukuki kontrol gerektiren taslaktır. UDF kapalıdır; Word veya TXT kullanın. Sulh/KVYO ve bazı arabuluculuk durumları ek olgular gerektirdiğinden otomatik sonuç üretilmez. Tarifeyi karar tarihine göre kontrol edin.

OML ortak proje imzasıdır. Bu uygulama yapay zekâ ile geliştirilmiştir.

**Hesap dökümü:** Sonuç bölümündeki **Nasıl hesaplandı?** düğmesi harç matrahını, oranı, ödenen harçları, bakiye/iade hesabını, AAÜT dilimlerini ve uygulanan sınırları, gider ve arabuluculuk dağılımını gösterir. Döküm kopyalanabilir; mevcut form değiştiğinde güncellenir.

**Tarife kaynağı:** Tarifeler ekranında AAÜT ve harç yürürlük dönemleri ayrı gösterilir. TBB ve GİB kaynakları açılabilir. Değiştirilen kalemler başlangıç ve kayıtlı değerleriyle belirtilir. Yeni eklenen yıllar özel tarife olarak işaretlenir. Takvim yılı seçimi AAÜT dönemini karar tarihine göre otomatik seçmez.

**Önceki sürüme dönüş:** Geçerli EXE yedeği varsa Güncellemeler ekranındaki açılır **Önceki sürüme dönüş** bölümünden geri yükleyebilirsiniz. Önce form kaydedilir; taslak ve tarifeler korunur. Yedeği silmeyin. 2.2.4 ve sonrasından başlatılan güncellemelerde yeni sürümün arayüzü üç dakika içinde hazır olduğunu bildirmezse ya da açılışta kapanırsa önceki EXE otomatik geri yüklenir. 2.2.3'ten yapılan ilk geçiş eski kurucuyla gerçekleştiğinden otomatik açılış kontrolü sonraki güncellemelerde devreye girer; eski kurucunun bıraktığı yedek, manuel geri dönüş için tanınır.

Sürümler: https://github.com/onurmuratlekesiz/hukumdar-surumler/releases/latest

Güncellemeler ekranı ilk açıldığında sürüm kontrol edilir. Tek ana düğme o anki işlemi gösterir: güncelleme varsa indirme, indirme tamamlanınca kurulum ve yeniden başlatma. Yeniden başlatmak için düğmeye basmanız gerekir. Tarayıcıdan indirme seçeneği yalnızca kontrol/indirme hatasında görünür.
