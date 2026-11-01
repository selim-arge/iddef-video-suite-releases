# 🎬 İDDEF Video Araçları

Bu depo, İDDEF Video Araçları masaüstü uygulamasının indirme dosyalarını ve sürüm notlarını barındırır.

## 🚀 Son Sürümü İndir (v1.5.0)
*Yayınlanma Tarihi: 01.11.2026*

* [🪟 Windows için İndir (iddef-video-suite-v1.5.0-amd64-setup.exe)](https://github.com/selim-arge/iddef-video-suite-releases/releases/download/v1.5.0/iddef-video-suite-v1.5.0-amd64-setup.exe)
* [🍎 macOS (Intel) için İndir (iddef-video-suite-v1.5.0-amd64.zip)](https://github.com/selim-arge/iddef-video-suite-releases/releases/download/v1.5.0/iddef-video-suite-v1.5.0-amd64.zip)
* [🍎 macOS (M1, M2, M3, M4) için İndir (iddef-video-suite-v1.5.0-arm64.zip)](https://github.com/selim-arge/iddef-video-suite-releases/releases/download/v1.5.0/iddef-video-suite-v1.5.0-arm64.zip)

**✨ Sürüm Notu (öne çıkanlar):**
* Video düzenleyicide **Kırp** ve **Döndür** menüleri yeniden çalışıyor.
* MKV, AVI, WMV, MPEG ve iPhone HEVC videolar düzenleyicide beklemeden açılıyor.
* QR okuma daha hızlı: etiketleme yaklaşık üçte bir, iPhone HDR / 4K videolarda yaklaşık üç kat daha hızlı. Mac sürümü de aynı okuyucuyu kullanıyor.
* Aynı QR koduna sahip iki video artık birbirinin üzerine yazılmıyor; ikincisi "Tekrar" klasörüne taşınıyor.
* İnternet kesilince yükleyici videoları "Hatali" klasörüne atmıyor; bağlantı dönünce kaldığı yerden devam ediyor.
* Donanım Ayarları'nda yeni **Sistem Testi**; yükleme öncesi sıkıştırma için işlemci veya ekran kartı artık elle seçiliyor.
* Kurulum, açık olan uygulamayı kendisi kapatıyor ve Windows diline göre Türkçe ya da İngilizce açılıyor.

Tüm değişiklikler için: **[v1.5.0 sürüm notları](https://github.com/selim-arge/iddef-video-suite-releases/releases/tag/v1.5.0)**

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

---

## 📜 Sürüm Geçmişi

### v1.2.0 (01.06.2026)
* **Yenilik:** Yavaş bağlantılar için video yükleme işlemi optimize edildi.

<br>

*Tüm geçmiş sürümlere, eklenen yeni özelliklere ve eski versiyon indirme linklerine Github'ın sağ tarafındaki **[Releases (Sürümler)](https://github.com/selim-arge/iddef-video-suite-releases/releases)** sekmesinden de ulaşabilirsiniz.*
