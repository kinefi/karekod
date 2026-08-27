[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-2ea44f?style=for-the-badge&logo=github)](https://kinefi.github.io/karekod)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=for-the-badge)](LICENSE)

# 🚀 Hızlı & Ücretsiz QR, Barkod & ISBN Üretici

Süresi asla dolmayan, tamamen ücretsiz ve kayıt gerektirmeyen web tabanlı statik QR kod, 1D Barkod ve ISBN (Kitap Barkodu) üretici.

Bütün işlemler doğrudan tarayıcınızda (JavaScript) gerçekleştiği için verileriniz hiçbir sunucuya gönderilmez ve kodlarınız ömür boyu çalışmaya devam eder.

---

## ✨ Özellikler

- 🔒 **Ömür Boyu Ücretsiz & Statik:** Yönlendirme sunucusu kullanmaz, oluşturulan kodların süresi dolmaz.
- 📊 **Çoklu Kod Tipi Desteği:**
  - **QR Kod:** 2D Matrix formatı (URL, uzun metinler için).
  - **Barkod:** 1D CODE128 formatı (ürün kodları, kargo takibi ve alfanümerik veriler için).
  - **ISBN / Kitap Barkodu:** 1D EAN-13 formatı (matbaa ve yayıncılık standartlarına tam uyumlu, otomatik Modulus 10 kontrol hanesi hesaplamalı).
- 📦 **Gelişmiş Format Desteği:** 
  - **PNG:** Yüksek çözünürlüklü dijital kullanım için.
  - **JPG:** Yüksek uyumlulukta genel görsel kullanımı için.
  - **SVG:** Temiz, baskıda bulanıklaşmayan ölçeklenebilir vektörel çizimler için.
  - **PDF:** A4 formatında otomatik hizalanmış doküman çıktısı için.
  - **TIFF:** Matbaa, profesyonel baskı ve arşivleme için.
- 📋 **Panoya Kopyalama:** Tek tıkla oluşturulan kodu doğrudan panoya kopyalayabilirsiniz.
- 🔑 **Akıllı Dosya İsimlendirme:** 
  - **ISBN için:** Doğrudan girdiğiniz ISBN numarası dosya adı yapılır (örneğin `978-625-00-4629-6.png`).
  - **QR ve Standart Barkod için:** Web Crypto API (SHA-256) kullanılarak girdinin içeriğinden tutarlı benzersiz isim üretilir (örneğin `a665a459.png`).
- 🌙 **Otomatik Koyu Tema:** Sistem tercihlerinize (Dark/Light mode) otomatik olarak uyum sağlar.
- ⌨️ **Hızlı Kullanım:** `Enter` tuşu desteği ile anında kod oluşturma.
- 🎨 **Özelleştirilebilir Renkler:** Çizgi ve zemin renklerini dilediğiniz gibi seçebilirsiniz.
- 📐 **Baskı Kalitesi:** Yüksek çözünürlüklü çizim parametreleri ve kenar boşlukları (Quiet Zone) ile okuyucu uyumluluğu artırılmıştır.
- 🛡️ **Gizlilik & Güvenlik Dostu:** İstemci taraflı (client-side) çalışır, verileriniz sunuculara iletilmez. Güvenli SRI (Subresource Integrity) doğrulaması içerir.

---

## 🛠️ Kullanılan Teknolojiler

- **HTML5 & CSS3** - Responsive tasarım, CSS Değişkenleri ve Medya Sorguları (`prefers-color-scheme`)
- **JavaScript (ES6+)** - Dinamik form yönetimi, Async/Await ve Web Crypto API (`crypto.subtle`)
- **QRCode.js** - İstemci taraflı QR kod oluşturma kütüphanesi
- **JsBarcode** - İstemci taraflı 1D Barkod (CODE128 ve EAN-13) oluşturma kütüphanesi
- **jsPDF** - İstemci taraflı PDF belgesi oluşturma kütüphanesi

---

## 🚀 Yerel Kurulum (Local Setup)

Bu projeyi bilgisayarınızda çalıştırmak için herhangi bir sunucu veya paket yöneticisine (npm/pip) ihtiyacınız yoktur.

1. Depoyu klonlayın: `git clone https://github.com/kinefi/karekod.git`
2. Proje klasörüne gidin.
3. `index.html` dosyasını çift tıklayarak herhangi bir tarayıcıda açın.

---

## 📝 Lisans

Bu proje Apache 2.0 lisansı altında lisanslanmıştır. Detaylar için [LICENSE](./LICENSE) dosyasına bakabilirsiniz.
