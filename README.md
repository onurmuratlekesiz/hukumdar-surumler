# Hükümdar

Windows paketini bir klasöre çıkartın ve **Hükümdar.exe** dosyasını açın. ZIP yalnızca bu EXE'yi içerir; Python kurulumu gerekmez. Masaüstü penceresi Edge WebView2 kullanır. EXE masaüstü penceresinde açılır; tekrar çalıştırıldığında mevcut pencere öne getirilir. Pencere motoru başlatılamazsa hata mesajı gösterilir.

Uygulama internet olmadan hesaplama yapar. Sağ üstteki **Güncellemeler** düğmesiyle yeni sürümü kontrol edin; varsa **İndir**, ardından **Kur ve yeniden başlat** düğmesine basın. İndirilen dosya SHA-256 özetiyle doğrulanır. Kurulum son formu kaydeder, uygulamayı kapatır, eski EXE'nin yanına bir yedek bırakır ve yeni sürümü açar. Uygulama klasörüne yazma izni gerekir. Güncelleme bir tarife yılı seçmez veya kullanıcıya ait özel tarifeleri silmez.

Kayıtlar `%LOCALAPPDATA%\Hukumdar` klasöründedir; uygulama dosyasını değiştirmek bunları silmez. Güncelleme kurulum hataları aynı klasördeki `update.log` dosyasına yazılır. GitHub veya internet erişimi yoksa güncelleme ertelenir; yerel hesaplama devam eder. Dosyayı yazılabilir bir klasörde tutun.

**Betik engeli veya güncellemeden sonra açılmama:** 2.2.8 veya daha yeni ZIP paketini resmî sürüm sayfasından tarayıcıyla indirip uygulama kapalıyken bir klasöre çıkartın ve içindeki EXE'yi çalıştırın. Kayıt klasörünü silmeyin. 2.2.8'den başlatılan kurulum ve önceki sürüme dönüş, uygulamanın kendi EXE yardımcısını kullanır; PowerShell betiği çalıştırmaz ve güvenlik ayarlarını değiştirmez. Eski sürümdeki kurucu bu değişikliği içermediği için ilk geçiş elle yapılmalıdır. Kurucu hazır olmadan uygulama kapanmaz. Ayrıntılar `update-installer.log` ve `update.log` dosyalarındadır.

**Kurulumda “Signal timed out” uyarısı:** Eski sürümlerin kurulum isteği 10 saniyede kesilebilir; bu mesaj kurulumun sonucunu tek başına belirtmez. 2.2.8 veya daha yeni paketi tarayıcıdan indirip mevcut uygulama kapalıyken yeni klasörden çalıştırın. Açılan uygulamanın sürümünü kontrol edin. Yeni sürüm kurulum/geri dönüş yanıtını iki dakika, kurucunun başlamasını 30 saniye bekler.

İlk sürümdeki **Hükümdar 2026.exe** kullanıcıları yeni paketi bir kez elle indirip çıkartmalıdır; sonraki sürümler uygulama içinden güncellenebilir.

Kurum ağında güncelleme bağlantısı Windows'un sistem/kullanıcı proxy ve sertifika ayarlarını kullanır. Hata mesajı sertifika, proxy kimlik doğrulaması, DNS veya zaman aşımını belirtir. **Tarayıcıdan indir** düğmesi resmî sürüm sayfasını açar. 2.2.0'da bağlantı hatası alan kullanıcılar 2.2.1'i tarayıcıdan indirip eski EXE kapalıyken değiştirmelidir; kayıtlar korunur. Kurumun erişim kuralları bağlantıyı engelliyorsa bilgi işlem birimiyle görüşün.

Başvurma harcını makbuzdaki ödenmiş tutarla girin. Çıktı hukuki kontrol gerektiren taslaktır. UDF kapalıdır; Word veya TXT kullanın. Sulh/KVYO ve bazı arabuluculuk durumları ek olgular gerektirdiğinden otomatik sonuç üretilmez. Tarifeyi karar tarihine göre kontrol edin.

OML ortak proje imzasıdır. Bu uygulama yapay zekâ ile geliştirilmiştir.

**Hesap dökümü:** Sonuç bölümündeki **Nasıl hesaplandı?** düğmesi harç matrahını, oranı, ödenen harçları, bakiye/iade hesabını, AAÜT dilimlerini ve uygulanan sınırları, gider ve arabuluculuk dağılımını gösterir. Döküm kopyalanabilir; mevcut form değiştiğinde güncellenir.

**Tarife kaynağı:** Tarifeler ekranında AAÜT ve harç yürürlük dönemleri ayrı gösterilir. TBB ve GİB kaynakları açılabilir. Değiştirilen kalemler başlangıç ve kayıtlı değerleriyle belirtilir. Yeni eklenen yıllar özel tarife olarak işaretlenir. Takvim yılı seçimi AAÜT dönemini karar tarihine göre otomatik seçmez.

**Önceki sürüme dönüş:** Geçerli EXE yedeği varsa Güncellemeler ekranındaki açılır **Önceki sürüme dönüş** bölümünden geri yükleyebilirsiniz. Önce form kaydedilir; taslak ve tarifeler korunur. Yedeği silmeyin. 2.2.4 ve sonrasından başlatılan güncellemelerde yeni sürümün arayüzü üç dakika içinde hazır olduğunu bildirmezse ya da açılışta kapanırsa önceki EXE otomatik geri yüklenir. 2.2.3'ten yapılan ilk geçiş eski kurucuyla gerçekleştiğinden otomatik açılış kontrolü sonraki güncellemelerde devreye girer; eski kurucunun bıraktığı yedek, manuel geri dönüş için tanınır.

Sürümler: https://github.com/onurmuratlekesiz/hukumdar-surumler/releases/latest

Güncellemeler ekranı ilk açıldığında sürüm kontrol edilir. Tek ana düğme o anki işlemi gösterir: güncelleme varsa indirme, indirme tamamlanınca kurulum ve yeniden başlatma. Yeniden başlatmak için düğmeye basmanız gerekir. Tarayıcıdan indirme seçeneği yalnızca kontrol/indirme hatasında görünür.
