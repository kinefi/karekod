[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-2ea44f?style=for-the-badge&logo=github)](https://kinefi.github.io/karekod)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=for-the-badge)](LICENSE)

# 🚀 Hızlı & Ücretsiz QR Kod Üretici

Süresi asla dolmayan, tamamen ücretsiz ve kayıt gerektirmeyen web tabanlı statik QR kod üretici.

Bütün işlemler doğrudan tarayıcınızda (JavaScript) gerçekleştiği için verileriniz hiçbir sunucuya gönderilmez ve kodlarınız ömür boyu çalışmaya devam eder.

---

## ✨ Özellikler

- 🔒 **Ömür Boyu Ücretsiz & Statik:** Yönlendirme sunucusu kullanmaz, oluşturulan kodların süresi dolmaz.
- 📦 **Gelişmiş Format Desteği:** 
  - **PNG:** Saydamlık destekli web ve dijital kullanım için.
  - **JPG:** Yüksek uyumlulukta genel görsel kullanımı için.
  - **SVG:** Temiz, ölçeklenebilir vektörel çizimler için.
  - **PDF:** A4 formatında doküman çıktısı için.
  - **TIFF:** Matbaa, profesyonel baskı ve arşivleme için.
- 📋 **Panoya Kopyalama:** Tek tıkla oluşturulan QR kodu doğrudan panoya kopyalayabilirsiniz.
- 🔑 **İçeriğe Özel Tutarlı Dosya İsimleri:** Web Crypto API (SHA-256) kullanılarak dosya adı girdinin içeriğinden üretilir. Aynı metin/URL her zaman aynı benzersiz dosya adını alır (örneğin `a665a459.png`).
- 🌙 **Otomatik Koyu Tema:** Sistem tercihlerinize (Dark/Light mode) otomatik olarak uyum sağlar.
- ⌨️ **Hızlı Kullanım:** `Enter` tuşu desteği ile anında QR kod oluşturma.
- 🎨 **Özelleştirilebilir Renkler:** Çizgi ve zemin renklerini dilediğiniz gibi seçebilirsiniz.
- ⚡ **Anında Üretim:** Sunucu bekleme süresi olmadan milisaniyeler içinde QR kod oluşturur.
- 🛡️ **Gizlilik & Güvenlik Dostu:** İstemci taraflı (client-side) çalışır, verileriniz sunuculara iletilmez. Güvenli SRI (Subresource Integrity) doğrulaması içerir.

---

## 🛠️ Kullanılan Teknolojiler

- **HTML5 & CSS3** - Responsive tasarım, CSS Değişkenleri ve Medya Sorguları (`prefers-color-scheme`)
- **JavaScript (ES6+)** - Dinamik form yönetimi, Async/Await ve Web Crypto API (`crypto.subtle`)
- **QRCode.js** - İstemci taraflı QR kod oluşturma kütüphanesi
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
