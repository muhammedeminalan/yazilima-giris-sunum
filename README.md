# Yazılıma Giriş — Hangi Alan Bana Göre?

**Yazılım Dünyasına İlk Adımı Atmak İçin Kapsamlı Rehber Sunumu**

## 📋 Proje Hakkında

Bu interaktif HTML sunumu, yazılım dünyasına yeni başlayanlar için hazırlanmış kapsamlı bir rehberdir. 8 farklı yazılım alanı, 8 popüler programlama dili ve kariyer rehberliği içerir.

## 🏗️ Proje Yapısı (Clean Architecture)

```
Yazılıma+Giriş+—+Hangi+Alan+Bana+Göre_/
├── assets/
│   ├── css/
│   │   └── styles.css          # Merkezi CSS dosyası (taşma/overlap hataları düzeltildi)
│   └── js/
│       └── navigation.js       # Merkezi JavaScript navigasyon sistemi
├── 01-giris-kapak.html         # Giriş sayfası
├── 02-hedefler.html            # Hedefler
├── 03-ortak-temel.html         # Ortak temel kavramlar
├── ...                         # (35 sayfa toplam)
├── 35-sonuc-motivasyon.html    # Kapanış sayfası
└── README.md                   # Bu dosya
```

## 📖 İçerik Yapısı

### Sayfa 1-5: Giriş ve Temel Bilgiler
- **01-giris-kapak.html**: Kapak sayfası
- **02-hedefler.html**: Sunumdan kazanımlar
- **03-ortak-temel.html**: Tüm alanlarda ortak kavramlar
- **04-alan-secimi-test.html**: Kendini değerlendirme testi
- **05-rehber-harita.html**: Genel rehber harita

### Sayfa 6-15: Yazılım Alanları
- **06-mobil-uygulama.html**: Mobil Uygulama Geliştirme (iOS, Android, Flutter)
- **07-web-gelistirme.html**: Web Geliştirme (Frontend, Backend)
- **08-siber-guvenlik.html**: Siber Güvenlik (Penetrasyon, Kriptografi)
- **09-veri-bilimi.html**: Veri Bilimi (AI, ML, Analitik)
- **10-gomulu-sistemler.html**: Gömülü Sistemler (IoT, Robotik)
- **11-backend-gelistirme.html**: Backend Geliştirme (API, Veritabanı)
- **12-devops-bulut.html**: DevOps & Bulut (CI/CD, AWS, Docker)
- **13-oyun-gelistirme.html**: Oyun Geliştirme (Unity, Unreal)
- **14-alanlar-ozet.html**: Alanlar özeti
- **15-diger-alanlar.html**: Diğer özel alanlar

### Sayfa 16: İçindekiler
- **16-icerik-tablosu.html**: Tam içindekiler tablosu (hızlı erişim)

### Sayfa 17-24: Programlama Dilleri
- **17-python-dili.html**: Python (AI/ML, Web, Veri)
- **18-javascript-typescript.html**: JavaScript & TypeScript (Web, Node.js)
- **19-java-kotlin.html**: Java & Kotlin (Enterprise, Android)
- **20-swift-dili.html**: Swift (iOS, macOS)
- **21-c-cpp-dilleri.html**: C & C++ (Sistem, Oyun, Performans)
- **22-csharp-dili.html**: C# (Unity, .NET, Windows)
- **23-go-dili.html**: Go (Cloud, Microservices)
- **24-rust-dili.html**: Rust (Sistem, Güvenlik)

### Sayfa 25-27: İleri Konular
- **25-yapay-zeka.html**: Yapay Zeka temelleri
- **26-makine-ogrenmesi.html**: Makine Öğrenmesi detayları
- **27-full-stack.html**: Full-Stack Development

### Sayfa 28-32: Kariyer ve Pratik Bilgiler
- **28-kariyer-yollari.html**: Kariyer seçenekleri
- **29-kariyer-planlama.html**: Freelance vs Şirket
- **30-ogrenme-kaynaklari.html**: Öğrenme kaynakları
- **31-sss-teknik.html**: Teknik SSS
- **32-sss-kariyer.html**: Kariyer SSS

### Sayfa 33-35: Kapanış
- **33-araclar-ekosistem.html**: Geliştirme araçları
- **34-proje-fikirleri.html**: Başlangıç proje önerileri
- **35-sonuc-motivasyon.html**: Motivasyon ve kapanış

## 🎯 Özellikler

### ✅ Clean Architecture
- **Merkezi CSS**: Tüm stiller `assets/css/styles.css` dosyasında
- **Merkezi JavaScript**: Navigasyon mantığı `assets/js/navigation.js` dosyasında
- **Modüler Yapı**: Her sayfa kendi konusuna odaklanmış
- **Okunabilir Kod**: Inline CSS/JS kaldırıldı, temiz HTML yapısı

### ✅ Düzeltilmiş Hatalar
- **Taşma (Overflow) Hataları**: `content-safe` sınıfı ile düzeltildi
- **Üst Üste Binme**: Z-index yönetimi ile düzeltildi
- **Navigation Z-Index**: Her zaman en üstte (z-index: 100)
- **Scrollbar Styling**: Custom scrollbar tasarımı

### ✅ Navigasyon Sistemi
- **Klavye Desteği**:
  - `← Sol Ok`: Önceki sayfa
  - `→ Sağ Ok` veya `Space`: Sonraki sayfa
  - `Home`: İlk sayfa
  - `End`: Son sayfa
  - `Esc`: İçindekiler sayfası (16)
- **Buton Navigasyonu**: Geri/İleri butonları
- **Sayfa Göstergesi**: "X / 35" formatında

### ✅ Responsive ve Görsel
- **Boyut**: 1280x720 (16:9 oranı)
- **Gradient Arka Planlar**: Indigo → Purple → Pink
- **Animasyonlar**: Float, pulse, fade-in efektleri
- **İkonlar**: Font Awesome 6.0.0
- **Tailwind CSS**: Utility-first CSS framework

## 🚀 Kullanım

### Sunumu Başlatma
```bash
# Dizine git
cd "Yazılıma+Giriş+—+Hangi+Alan+Bana+Göre_"

# İlk sayfayı aç (macOS)
open 01-giris-kapak.html

# Veya tarayıcıda doğrudan aç
# Çift tıklama: 01-giris-kapak.html
```

### Local Server ile Çalıştırma (Önerilen)
```bash
# Python 3 ile
python3 -m http.server 8000

# Tarayıcıda aç:
# http://localhost:8000/01-giris-kapak.html
```

### Navigasyon Kullanımı
1. **Klavye ile**: `←` ve `→` ok tuşları ile gezin
2. **Fare ile**: Sağ alt köşedeki butonlara tıklayın
3. **Hızlı Erişim**: `Esc` tuşu ile içindekiler sayfasına gidin

## 🛠️ Teknik Detaylar

### Kullanılan Teknolojiler
- **HTML5**: Semantic markup
- **CSS3**: Custom properties, animations, grid/flexbox
- **JavaScript (ES6+)**: Modern syntax, event handling
- **Tailwind CSS**: Utility classes (CDN)
- **Font Awesome**: Icon library (v6.0.0)

### CSS Sınıfları (Önemli)
```css
.slide              /* Ana slide container */
.navigation-container /* Navigation buton container */
.card               /* İçerik kartları */
.content-safe       /* Overflow korumalı içerik alanı */
.floating           /* Float animasyonu */
.badge              /* Etiketler */
```

### JavaScript API
```javascript
// Global nesne: window.slideNavigation
slideNavigation.goToPage(5)          // 5. sayfaya git
slideNavigation.goToNextPage()       // Sonraki sayfa
slideNavigation.goToPreviousPage()   // Önceki sayfa
slideNavigation.getCurrentPage()     // Mevcut sayfa numarası
slideNavigation.getPageTitle(10)     // Sayfa başlığı
```

## 📦 Dosya Boyutları
- **CSS**: ~12 KB (sıkıştırılmamış)
- **JavaScript**: ~5 KB (sıkıştırılmamış)
- **HTML (ortalama)**: ~3-8 KB/sayfa
- **Toplam**: ~350 KB (tüm dosyalar)

## 🎨 Renk Paleti

### Ana Renkler
- **Indigo**: `#6366f1` (Primary)
- **Purple**: `#8b5cf6` (Secondary)
- **Pink**: `#ec4899` (Accent)
- **Blue**: `#3b82f6` (Info)
- **Green**: `#10b981` (Success)
- **Red**: `#ef4444` (Danger)
- **Yellow**: `#f59e0b` (Warning)

### Gradient
```css
background: linear-gradient(135deg, 
    #e0e7ff 0%,   /* Indigo-100 */
    #f3e8ff 50%,  /* Purple-50 */
    #fce7f3 100%  /* Pink-100 */
);
```

## 📝 Güncelleme Geçmişi

### v2.0 - Clean Architecture Refactoring (2024)
- ✅ Merkezi CSS/JS dosyaları oluşturuldu
- ✅ Tüm inline stil ve scriptler kaldırıldı
- ✅ Dosya isimleri descriptive hale getirildi
- ✅ Taşma ve overlap hataları düzeltildi
- ✅ Navigation sistemi optimize edildi
- ✅ Z-index yönetimi iyileştirildi

### v1.0 - İlk Versiyon
- ✅ 35 sayfalık kapsamlı içerik
- ✅ 8 yazılım alanı + 8 programlama dili
- ✅ Klavye ve buton navigasyonu
- ✅ Responsive tasarım (1280x720)

## 🤝 Katkıda Bulunma

Bu bir eğitim projesidir. Öneriler ve düzeltmeler için issue açabilirsiniz.

## 📄 Lisans

Eğitim amaçlı kullanım için serbesttir.

## 👨‍💻 Yazar

**Yazılıma Giriş Rehber Ekibi**  
Tarih: 2025-12-16

---

## 🎓 Hedef Kitle

- Yazılıma yeni başlayanlar
- Alan seçiminde kararsız olanlar
- Yazılım kariyerine geçiş yapanlar
- Öğrenciler ve mentorlar

## 💡 Kullanım Senaryoları

1. **Bireysel Öğrenme**: Kendi hızında gezinme
2. **Sunum**: Sınıf veya workshoplarda gösterim
3. **Mentorluk**: Yeni başlayanlarla paylaşma
4. **Kariyer Danışmanlığı**: Alan seçimi rehberliği

---

**İyi Öğrenmeler! 🚀**
