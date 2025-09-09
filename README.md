# SteelTech - Çelik Konstrüksiyon Yönetim Sistemi

**25+ yıllık deneyimle çelik konstrüksiyon alanında uzman çözümler sunan KVC Mühendislik için geliştirilmiş kapsamlı yönetim ve tanıtım platformu.**

## 📋 Proje Hakkında

SteelTech, çelik konstrüksiyon firmalarının operasyonlarını dijitalleştiren, modern ve kullanıcı dostu bir platform sunar. Admin paneli ile işletme yönetimi, mobil uygulama ile müşteri deneyimi ve web sitesi ile kurumsal tanıtım özelliklerini bir arada bulundurur.

## ✨ Temel Özellikler

### 🔧 Admin Panel Özellikleri

- **Dashboard Yönetimi**
  - Anlık sipariş takibi ve istatistikler
  - Proje ilerleme durumları
  - Ürün stok yönetimi
  - Hızlı işlem butonları

- **Sipariş Yönetimi**
  - Müşteri bilgileri ve iletişim detayları
  - Sipariş durumu takibi (Beklemede, Onaylandı, Teslim Edildi)
  - Ödeme yöntemi ve tutar takibi
  - Detaylı sipariş raporlaması

- **Proje Yönetimi**
  - Büyük ölçekli projelerin takibi
  - İlerleme yüzdesi ve timeline
  - Proje kategorileri (Endüstriyel, Ticari, Özel Projeler)
  - Maliyet ve bütçe yönetimi

- **Ürün Kataloğu Yönetimi**
  - Çelik profil ve sac çeşitleri
  - 3D model entegrasyonu
  - Fiyat ve stok güncelleme
  - Kategori bazlı düzenleme

- **3D Model Sistemi**
  - GLB formatında model yükleme
  - Model optimizasyonu ve sıkıştırma
  - Çoklu format desteği (GLB, GLTF, OBJ, FBX, DAE, 3DS)
  - Otomatik boyut optimizasyonu

- **Şirket Bilgileri**
  - İletişim detayları yönetimi
  - Hizmet saatleri düzenleme
  - Logo ve görsel yönetimi
  - Sosyal medya entegrasyonu

### 📱 Mobil Uygulama Özellikleri

- **Ana Sayfa ve Tanıtım**
  - Şirket vizyonu ve misyonu
  - 25+ yıllık deneyim vurgusu
  - Hizmet alanları tanıtımı
  - Hızlı erişim menüleri

- **Hizmet Kategorileri**
  - 🏭 **Endüstriyel Yapılar** - Fabrika ve üretim tesisleri
  - 🏢 **Ticari Binalar** - Ofis ve iş merkezleri  
  - 🏪 **Depo & Hangar** - Büyük açıklıklı yapılar
  - ⭐ **Özel Projeler** - Tasarım ve üretim

- **Ürün Kataloğu**
  - Detaylı çelik profil listesi
  - Teknik çizimler ve ölçüler
  - Güncel fiyat bilgileri
  - Sepete ekleme ve satın alma

- **Referans Projeler**
  - Tamamlanan ve devam eden projeler
  - Proje durumu ve ilerleme takibi
  - Müşteri referansları
  - Görsel galeri

- **3D Model Görüntüleme**
  - Mobil cihazlarda 3D model inceleme
  - Zoom, döndürme ve detay görüntüleme
  - AR (Artırılmış Gerçeklik) desteği
  - Model indirme seçenekleri

- **İletişim ve Destek**
  - Doğrudan arama ve WhatsApp
  - E-posta ile iletişim
  - Konum ve adres bilgileri
  - Çalışma saatleri

## 🖼️ Ekran Görüntüleri

### Admin Panel

| Dashboard | Sipariş Yönetimi | Proje Takibi |
|-----------|------------------|--------------|
| ![Dashboard](admin-dashboard.png) | ![Siparişler](admin-orders.png) | ![Projeler](admin-projects.png) |

| Ürün Yönetimi | 3D Model Sistemi | Şirket Bilgileri |
|---------------|------------------|------------------|
| ![Ürünler](admin-products.png) | ![3D Modeller](admin-3d-models.png) | ![Şirket](admin-company.png) |

### Mobil Uygulama

| Ana Sayfa | Ürün Kataloğu | Ürün Detayı |
|-----------|---------------|-------------|
| ![Ana Sayfa](mobile-home.png) | ![Katalog](mobile-catalog.png) | ![Detay](mobile-product.png) |

| Referans Projeler | 3D Modeller | İletişim |
|-------------------|-------------|----------|
| ![Projeler](mobile-projects.png) | ![3D](mobile-3d.png) | ![İletişim](mobile-contact.png) |

## 🚀 Teknoloji Stack

### Frontend
- **Flutter** - Mobil uygulama geliştirme
- **HTML5** - Web arayüzü
- **CSS3** - Stil ve animasyonlar
- **JavaScript** - İnteraktif özellikler

### Backend
- **Firebase** - Bulut veritabanı ve hosting
- **Firebase Authentication** - Kullanıcı yönetimi
- **Firebase Storage** - Dosya ve medya depolama
- **Firebase Cloud Functions** - Sunucu tarafı işlemler

### 3D Model Desteği
- **GLB/GLTF** - Ana 3D format
- **Three.js** - Web 3D görüntüleme
- **Model Viewer** - Mobil 3D görüntüleme
- **AR Core/ARKit** - Artırılmış gerçeklik

## 📦 Kurulum

### Gereksinimler
- Flutter SDK (3.0+)
- Firebase CLI
- Node.js (16+)
- Android Studio / Xcode

### Backend Kurulumu
```bash
# Firebase projesini başlat
firebase init

# Cloud Functions için gerekli paketleri yükle
cd functions
npm install

# Firebase'e deploy et
firebase deploy
```

### Mobile App Kurulumu
```bash
# Repoyu klonla
git clone https://github.com/your-username/steeltech-app.git
cd steeltech-app

# Bağımlılıkları yükle
flutter pub get

# Android için çalıştır
flutter run

# iOS için çalıştır (macOS gerekli)
flutter run -d ios
```

### Web Admin Panel Kurulumu
```bash
# Web dizinine git
cd web-admin

# Bağımlılıkları yükle
npm install

# Geliştirme sunucusunu başlat
npm run dev

# Production build
npm run build
```

## 📊 Özellik Detayları

### Sipariş Yönetimi
- Otomatik sipariş numarası oluşturma
- Müşteri profili ve geçmiş siparişler
- E-posta ve SMS bildirimleri
- PDF fatura ve teklif oluşturma

### Proje Takibi
- Gantt chart ile timeline görünümü
- Milestone ve checkpoint sistemi
- Foto galeri ve ilerleme raporları
- Müşteri onay süreçleri

### 3D Model Sistemi
- Dosya boyutu optimizasyonu (max 50MB)
- Otomatik thumbnail oluşturma
- Çoklu model formatı desteği
- Mobil AR görüntüleme

### Stok Yönetimi
- Gerçek zamanlı stok takibi
- Düşük stok uyarıları
- Otomatik yeniden sipariş
- Tedarikçi entegrasyonu

## 🔧 Yapılandırma

### Firebase Konfigürasyonu
```javascript
// firebase-config.js
const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "steeltech-app.firebaseapp.com",
  projectId: "steeltech-app",
  storageBucket: "steeltech-app.appspot.com",
  messagingSenderId: "123456789",
  appId: "your-app-id"
};
```

### Environment Variables
```bash
# .env dosyası
FIREBASE_API_KEY=your_api_key
FIREBASE_PROJECT_ID=steeltech-app
STRIPE_SECRET_KEY=your_stripe_key
ADMIN_EMAIL=admin@kvchendislik.com
```

## 📈 Performans Optimizasyonları

- **Lazy Loading** - Sayfa ve component bazlı
- **Image Compression** - Otomatik boyut optimizasyonu
- **Caching Strategy** - Firebase caching ile hızlı erişim
- **3D Model Optimization** - LOD (Level of Detail) sistemi
- **Progressive Web App** - Offline çalışma desteği

## 🛡️ Güvenlik

- Firebase Authentication ile güvenli giriş
- Role-based access control (Admin/User)
- Data validation ve sanitization
- Secure file upload (virus tarama)
- HTTPS zorunluluğu

## 🤝 Katkıda Bulunma

1. Projeyi fork edin
2. Feature branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Branch'i push edin (`git push origin feature/yeni-ozellik`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 📞 İletişim

**KVC Mühendislik**
- 📧 Email: admin@ststore.com
- 📱 Telefon: +90 540 415 2002
- 🌐 Website: https://www.kvcmuhendislik.com.tr/
- 📍 Adres: Sepetlipınar Mah. Arpalık Cad. Başiskele Küçük Sanayi Sit. No: 118/ 1-11, BAŞİSKELE, KOCAELİ

## 🎯 Roadmap

- [ ] **v2.0** - AR/VR entegrasyonu
- [ ] **v2.1** - AI destekli maliyet hesaplama
- [ ] **v2.2** - IoT sensör entegrasyonu
- [ ] **v2.3** - Blockchain bazlı sertifikasyon
- [ ] **v3.0** - Multiplatform desktop uygulaması

---

**⭐ Bu projeyi beğendiyseniz yıldızlamayı unutmayın!**
