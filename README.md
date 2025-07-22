# 🎓 İstanbul Zaim Üniversitesi OBS Mobil Uygulaması

Modern ve kullanıcı dostu **Öğrenci Bilgi Sistemi (OBS)** mobil uygulaması. React Native ve Expo Router ile geliştirilmiş, modüler ve reusable bileşenler kullanan bir uygulama.

![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-blue)
![React Native](https://img.shields.io/badge/React%20Native-0.79.5-green)
![Expo](https://img.shields.io/badge/Expo-~53.0.20-black)
![TypeScript](https://img.shields.io/badge/TypeScript-~5.8.3-blue)

## 📱 Ekran Görüntüleri
<p align="center">
  <img src="https://github.com/user-attachments/assets/12adfdc7-1f42-46ed-bf47-dc48c6f985ef" width="45%" />
  <img src="https://github.com/user-attachments/assets/5a669f95-e955-497b-acdd-e5345e09f67b" width="45%" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/44172cd9-ccca-40c0-8ea9-94eaf34749b8" width="45%" />
  <img src="https://github.com/user-attachments/assets/3bac1ee3-7925-4704-a844-614f0689025e" width="45%" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/b7f433c3-6255-4eaa-8fe3-f15541275f01" width="45%" />
  <img src="https://github.com/user-attachments/assets/c77c7598-62ad-4b5c-b0c3-69e32575c9ff" width="45%" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/18eb4e55-ad18-42bd-9c7c-71d939fdd5de" width="45%" />
  <img src="https://github.com/user-attachments/assets/48c677cd-6595-46e6-9daf-21c02b538115" width="45%" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/833c8a81-f20a-4579-8625-41877ca35507" width="45%" />
  <img src="https://github.com/user-attachments/assets/d9dff8eb-0a94-4288-b86f-f54f9ef0dfc7" width="45%" />
</p>




Uygulama, İstanbul Zaim Üniversitesi'nin kurumsal kimliğini yansıtan kırmızı/bordo tema ile tasarlanmıştır.

## ✨ Özellikler

### 🎨 **Modern Tasarım**
- İstanbul Zaim Üniversitesi kurumsal kimliği
- Responsive ve kullanıcı dostu arayüz
- Animasyonlu geçişler ve etkileşimler
- Dark/Light mode desteği (gelecek güncellemede)

### 🔐 **Güvenli Giriş**
- Öğrenci numarası ve şifre ile giriş
- JWT token tabanlı kimlik doğrulama
- Otomatik oturum yönetimi
- Güvenli veri saklama

### 📚 **Akademik Modüller**
- **Ana Sayfa**: Hızlı erişim ve duyurular
- **Dersler**: Kayıtlı dersler ve detayları
- **Notlar**: Sınav sonuçları ve GPA takibi
- **Ders Programı**: Haftalık çizelge ve sınıf bilgileri
- **Profil**: Kişisel bilgiler ve ayarlar

### 🛠 **Teknik Özellikler**
- **TypeScript**: Tip güvenliği
- **Modüler Yapı**: Reusable bileşenler
- **Offline Support**: Veri önbellekleme
- **Real-time Updates**: Pull-to-refresh
- **Error Handling**: Kullanıcı dostu hata yönetimi

## 🚀 Kurulum

### Gereksinimler
- Node.js (18.x veya üzeri)
- npm veya yarn
- Expo CLI
- iOS Simulator veya Android Emulator

### 1. Projeyi İndirin
```bash
git clone <repository-url>
cd mobile
```

### 2. Bağımlılıkları Yükleyin
```bash
npm install
# veya
yarn install
```

### 3. Uygulamayı Başlatın
```bash
npm start
# veya
yarn start
```

### 4. Cihazda Çalıştırın
```bash
# iOS için
npm run ios

# Android için
npm run android

# Web için
npm run web
```

## 📋 Demo Giriş Bilgileri

Uygulamayı test etmek için aşağıdaki demo hesabını kullanabilirsiniz:

```
Öğrenci Numarası: 123456
Şifre: 123456
```

## 📁 Proje Yapısı

```
mobile/
├── app/                          # Expo Router sayfaları
│   ├── screens/                  # Ana ekranlar
│   │   ├── SplashScreen.tsx     # Açılış ekranı
│   │   └── LoginScreen.tsx      # Giriş ekranı
│   ├── (tabs)/                  # Tab navigation
│   │   ├── _layout.tsx          # Tab layout yapılandırması
│   │   ├── index.tsx            # Ana sayfa (Dashboard)
│   │   ├── courses.tsx          # Dersler
│   │   ├── grades.tsx           # Notlar
│   │   ├── schedule.tsx         # Ders Programı
│   │   └── profile.tsx          # Profil
│   ├── index.tsx                # Ana routing
│   └── login.tsx                # Login route
├── components/                   # React bileşenleri
│   └── ui/                      # Reusable UI bileşenleri
│       ├── Button.tsx           # Buton bileşeni
│       ├── Input.tsx            # Input bileşeni
│       ├── Card.tsx             # Kart bileşeni
│       ├── Logo.tsx             # Logo bileşeni
│       └── index.ts             # Bileşen export'ları
├── constants/                    # Sabitler ve design system
│   ├── Colors.ts                # Renk paleti
│   ├── Typography.ts            # Font sistemi
│   ├── Spacing.ts               # Boşluk sistemi
│   └── index.ts                 # Constant export'ları
├── types/                       # TypeScript tip tanımları
│   └── index.ts                 # Ana tip dosyası
├── utils/                       # Utility fonksiyonları
│   ├── api.ts                   # API client ve helper'lar
│   └── storage.ts               # Local storage yönetimi
├── assets/                      # Görseller ve fontlar
├── hooks/                       # Custom React hooks
└── services/                    # Servis katmanı
```

## 🎨 Design System

### Renk Paleti
```typescript
// Ana renkler
primary: '#DC143C',      // Zaim Üniversitesi kırmızısı
primaryDark: '#B91C3C',  // Koyu kırmızı varyantı
secondary: '#F8F9FA',    // Açık gri arka plan
success: '#22C55E',      // Başarı yeşili
warning: '#F59E0B',      // Uyarı turuncusu
error: '#EF4444',        // Hata kırmızısı
```

### Typography Sistemi
- **Başlıklar**: h1 (30px), h2 (24px), h3 (20px), h4 (18px)
- **Gövde Metni**: body (16px), bodySmall (14px), caption (12px)
- **Font Ağırlıkları**: normal, medium, semibold, bold

### Spacing Sistemi
- 4px grid sistemi tabanlı tutarlı boşluklar
- Component padding: xs (8px), sm (12px), md (16px), lg (20px)
- Ekran padding: horizontal (16px), vertical (20px)

## 🔌 API Entegrasyonu

### Endpoint'ler
```typescript
// Kimlik doğrulama
POST /auth/login
POST /auth/logout
POST /auth/refresh

// Kullanıcı
GET /user/me
PUT /user/profile
POST /user/change-password

// Dersler
GET /courses
GET /courses/:id

// Notlar
GET /grades
GET /grades/transcript

// Ders Programı
GET /schedule

// Duyurular
GET /announcements
POST /announcements/:id/read
```

### API Client Kullanımı
```typescript
import { apiClient } from './utils/api';

// Giriş yapma
const response = await apiClient.login({
  studentNumber: '123456',
  password: '123456'
});

// Dersler getirme
const courses = await apiClient.getCourses();
```

## 💾 Veri Yönetimi

### Local Storage
- **AsyncStorage** ile güvenli veri saklama
- Kimlik doğrulama token'ları
- Kullanıcı tercihleri ve ayarları
- Offline veri önbellekleme

### Cache Sistemi
```typescript
import { storage } from './utils/storage';

// Cache'e veri kaydetme
await storage.setCacheData('courses', coursesData, 3600000); // 1 saat

// Cache'den veri okuma
const cachedCourses = await storage.getCacheData('courses');
```

## 🧪 Test

```bash
# Unit testler
npm test

# E2E testler
npm run test:e2e

# Test coverage
npm run test:coverage
```

## 📦 Build

### Development Build
```bash
npm run build:dev
```

### Production Build
```bash
# iOS
npm run build:ios

# Android
npm run build:android
```

### EAS Build (Cloud)
```bash
npx eas build --platform all
```

## 🔧 Yapılandırma

### Environment Variables
`.env` dosyası oluşturun:
```env
API_BASE_URL=https://obs-api.izu.edu.tr/api/v1
API_TIMEOUT=10000
SENTRY_DSN=your_sentry_dsn_here
```

### App Config
`app.json` dosyasında uygulama ayarlarını yapılandırın:
```json
{
  "expo": {
    "name": "İZÜ OBS",
    "slug": "izu-obs",
    "version": "1.0.0",
    "orientation": "portrait",
    "platforms": ["ios", "android"]
  }
}
```

## 🚀 Deployment

### App Store (iOS)
1. Apple Developer hesabı gerekli
2. EAS Build ile IPA oluşturun
3. App Store Connect'e yükleyin

### Google Play Store (Android)
1. Google Play Console hesabı gerekli
2. EAS Build ile AAB oluşturun
3. Play Console'a yükleyin

## 🛠 Geliştirme

### Code Style
- **ESLint** ve **Prettier** kullanımı
- **TypeScript** strict mode
- **Conventional Commits** formatı

### Git Workflow
```bash
# Feature branch oluşturma
git checkout -b feature/new-feature

# Commit
git commit -m "feat: add new feature"

# Push ve Pull Request
git push origin feature/new-feature
```

## 📚 Kullanılan Kütüphaneler

### Temel
- **React Native**: 0.79.5
- **Expo**: ~53.0.20
- **TypeScript**: ~5.8.3

### Navigation
- **Expo Router**: ~5.1.4
- **React Navigation**: ^7.1.6

### UI ve Styling
- **Expo Vector Icons**: ^14.1.0
- **React Native Safe Area Context**: 5.4.0
- **React Native Reanimated**: ~3.17.4

### Storage ve Network
- **AsyncStorage**: Latest
- **Expo Constants**: ~17.1.7

## 🤝 Katkıda Bulunma

1. Repository'yi fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 👥 Geliştirici Ekibi

- **UI/UX Design**: Figma tasarım ekibi
- **Mobile Development**: React Native geliştirici ekibi
- **Backend API**: İZÜ BT departmanı

## 📞 İletişim

- **Destek**: support@izu.edu.tr
- **Teknik**: it@izu.edu.tr
- **Web**: https://www.izu.edu.tr

## 🔄 Güncelleme Geçmişi

### v1.0.0 (Mevcut)
- ✅ Temel OBS funktions
- ✅ Kullanıcı kimlik doğrulama
- ✅ Ders ve not yönetimi
- ✅ Ders programı görüntüleme
- ✅ Profil yönetimi

### v1.1.0 (Planlanan)
- 🔄 Push bildirimleri
- 🔄 Dark mode
- 🔄 Çoklu dil desteği
- 🔄 Gelişmiş önbellekleme

---

**© 2024 İstanbul Zaim Üniversitesi - Tüm hakları saklıdır.**
# ReactNativeStudentInformationSystem
