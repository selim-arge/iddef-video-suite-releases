# 🎬 İDDEF Video Araçları

Bu depo, İDDEF Video Araçları masaüstü uygulamasının indirme dosyalarını ve sürüm notlarını barındırır.

## 🚀 Son Sürümü İndir (v2.0.1)
*Yayınlanma Tarihi: 17.11.2026*

* [🪟 Windows için İndir (iddef-video-suite-v2.0.1-amd64-setup.exe)](https://github.com/selim-arge/iddef-video-suite-releases/releases/download/v2.0.1/iddef-video-suite-v2.0.1-amd64-setup.exe)
* [🍎 macOS (Intel) için İndir (iddef-video-suite-v2.0.1-amd64.zip)](https://github.com/selim-arge/iddef-video-suite-releases/releases/download/v2.0.1/iddef-video-suite-v2.0.1-amd64.zip)
* [🍎 macOS (M1, M2, M3, M4) için İndir (iddef-video-suite-v2.0.1-arm64.zip)](https://github.com/selim-arge/iddef-video-suite-releases/releases/download/v2.0.1/iddef-video-suite-v2.0.1-arm64.zip)

**✨ Sürüm Notu (öne çıkanlar):**
* **Kullanım rehberi:** Ana sayfadaki **Nasıl kullanılır?** düğmesi, adımları anlatan küçük bir pencere açar. Rehber ilk açılışta kendiliğinden gösterilir ve açtığınız aracın adımına geçer.
* **Daha iyi QR okuma:** Okunması zor ve eğik duran QR kodlar daha kolay okunuyor.
* **Güvenli dışa aktarma:** Video Düzenleyici'de dışa aktarma iptal edilir ya da hata verirse aynı adlı eski dosyanız korunur.
* Sunucu doğrulamada hata verirse videolar artık **Hatali** klasörüne taşınmıyor; yükleme durur, dosyalar yerinde kalır.
* Aynı QR'a sahip ikinci video, uzantısı farklı olsa da **Tekrar** klasörüne gidiyor.
* **Kırp** ve **Döndür** menüleri artık açılırken yer değiştirmiyor.

Tüm değişiklikler için: **[v2.0.1 sürüm notları](https://github.com/selim-arge/iddef-video-suite-releases/releases/tag/v2.0.1)**

---

## 🛠️ Yükleme Talimatları

### 🪟 Windows
* İndirilen dosyaya çift tıklayarak açın.
* Eğer Windows güvenlik uyarısı verirse, önce **"Ek bilgi"** yazısına tıklayın, ardından **"Yine de çalıştır"** butonuna basarak yükleme işlemine devam edebilirsiniz.
* Uygulama açıksa kurulum onu kapatmayı önerir; **Tamam**'a basmanız yeterlidir. Önceki sürümü kaldırmanıza gerek yoktur.

### 🍎 macOS
* **macOS 13 (Ventura) veya daha yenisi gerekir.**
* Hangi dosyayı indireceğinizi öğrenmek için sol üstteki **Apple menüsü → Bu Mac Hakkında**'ya bakın: **"Yonga: Apple M…"** yazıyorsa **M1, M2, M3, M4** sürümünü, **"İşlemci: … Intel …"** yazıyorsa **Intel** sürümünü indirin.
* İndirilen **.zip** dosyasına çift tıklayın; çıkan **iddef-video-suite** uygulamasını **Uygulamalar (Applications)** klasörüne sürükleyip bırakın.
* Sistem *"Uygulama zaten yüklü"* uyarısı verirse **"Değiştir"** seçeneğine tıklayın.
* Uygulamayı açarken hata alırsanız **Terminal** uygulamasını açın ve şu adımları izleyin:
  1. Terminale `xattr -cr ` yazın (sonunda **mutlaka bir boşluk** bırakın).
  2. Uygulamalar klasörüne attığınız **iddef-video-suite** uygulamasını farenizle tutup Terminal penceresinin içine sürükleyip bırakın. (Kod otomatik olarak tamamlanacaktır).
  3. **Enter**'a basın. Artık uygulamayı sorunsuz açabilirsiniz.
* 1.5.0 veya daha eski bir sürümden geçiyorsanız Mac'te ilk açılışta dil seçimi bir kez sıfırlanabilir; dili yeniden seçmeniz yeterlidir. İlk bildirimden önce macOS izin ister.

### 🔄 Güncelleme
* **2.0.0 kullanıyorsanız** 2.0.1'e uygulama içinden geçebilirsiniz: güncelleme penceresinde **Şimdi Güncelle**'ye basın. Windows kurulum için bir kez yönetici onayı ister; uygulama kapanıp yeni sürümle açılır.
* **v1.5.0 veya daha eski bir sürüm** kullanıyorsanız yukarıdaki adımlarla bir kez elle kurun; eski sürümlerde uygulama içinden güncelleme yoktur.
* Etiketleme, yükleme veya dışa aktarma sürerken güncelleme başlamaz; iş bitince tekrar deneyin.
* Uygulama içinden güncelleme kurulamazsa, güncelleme penceresinden kurulum dosyasını tarayıcıda indirip elle kurabilirsiniz.

---

## 📜 Sürüm Geçmişi

### v2.0.0 (02.11.2026)
* Uygulamanın masaüstü altyapısı yenilendi; ekranlar ve kullanım aynı kaldı.
* **Uygulama içinden güncelleme**, klasör ve videolar için **sürükle-bırak** ve iş bitince **sistem bildirimleri** eklendi.
* Uygulama tek kopya açılır; güncelleme penceresi yalnızca bu bilgisayara uygun sürümü gösterir.
* Ayrıntılar: **[v2.0.0 sürüm notları](https://github.com/selim-arge/iddef-video-suite-releases/releases/tag/v2.0.0)**

### v1.5.0 (01.11.2026)
* Video düzenleyicide **Kırp** ve **Döndür** yeniden çalışıyor; MKV, AVI, WMV, MPEG ve iPhone HEVC videolar beklemeden açılıyor.
* QR okuma daha hızlı; aynı QR koduna sahip ikinci video "Tekrar" klasörüne taşınıyor.
* İnternet kesilince yükleyici kaldığı yerden devam ediyor; Donanım Ayarları'nda yeni **Sistem Testi**.
* Ayrıntılar: **[v1.5.0 sürüm notları](https://github.com/selim-arge/iddef-video-suite-releases/releases/tag/v1.5.0)**

### v1.2.0 (01.06.2026)
* **Yenilik:** Yavaş bağlantılar için video yükleme işlemi optimize edildi.

<br>

*Tüm geçmiş sürümlere, eklenen yeni özelliklere ve eski versiyon indirme linklerine Github'ın sağ tarafındaki **[Releases (Sürümler)](https://github.com/selim-arge/iddef-video-suite-releases/releases)** sekmesinden de ulaşabilirsiniz.*
