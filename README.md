# AkademiChat - Mobil Programlama Projesi

## 📱 Proje Hakkında
AkademiChat, üniversite öğrencileri için geliştirilmiş bir **mobil eğitim platformu** web uygulamasıdır.
React + TypeScript + Vite ile geliştirilmiş, Firebase altyapısı kullanılmıştır.

## 🚀 Kurulum ve Çalıştırma

### Gereksinimler
- **Node.js** (v18 veya üzeri) — https://nodejs.org

### Adımlar

1. Terminal açın ve proje klasörüne gidin:
```bash
cd akademi_chat_web
```

2. Bağımlılıkları yükleyin:
```bash
npm install
```

3. Uygulamayı başlatın:
```bash
npm run dev
```

4. Tarayıcıda açın:
```
http://localhost:5173
```

5. **Mobil görünüm** için tarayıcıda F12 tuşuna basın → sol üstteki telefon ikonuna tıklayın.

## 🔑 Giriş Bilgileri (Test Kullanıcıları)

| Email | Şifre | Bölüm |
|-------|-------|-------|
| seyma@edu.tr | 123456 | Hukuk Fakültesi |
| ahmet@edu.tr | 123456 | Bilgisayar Mühendisliği |
| elif@edu.tr | 123456 | Matematik |
| can@edu.tr | 123456 | İşletme |

## 📋 Özellikler

- ✅ Kullanıcı Girişi / Kayıt (Firebase Authentication)
- ✅ Bölüme Özel Ana Sayfa (Ders, Duyuru, Sınıf Arkadaşları)
- ✅ Sınıf Yönetimi (Dönemler, Dersler, GPA)
- ✅ Ders Detay Sayfası (Materyaller, Zaman Çizelgesi)
- ✅ Mesajlaşma Sistemi (Gerçek Zamanlı Chat)
- ✅ Ödev Takibi (İlerleme Durumu)
- ✅ Profil Sayfası (Rozetler, Başarılar)
- ✅ Mobil Uyumlu Tasarım (Responsive)

## 🛠 Teknolojiler

- **Frontend:** React 19, TypeScript, Vite
- **Stil:** Vanilla CSS (Glassmorphism Tasarım)
- **Backend:** Firebase (Auth, Firestore, Storage)
- **Paket Yönetimi:** npm
- **Mobil Dönüşüm:** Capacitor (Android desteği)

## 📁 Proje Yapısı

```
akademi_chat_web/
├── src/
│   ├── components/     # Layout bileşeni
│   ├── pages/          # Sayfa bileşenleri
│   │   ├── Home.tsx         # Ana Sayfa
│   │   ├── Login.tsx        # Giriş Sayfası
│   │   ├── Register.tsx     # Kayıt Sayfası
│   │   ├── Classes.tsx      # Sınıf Yönetimi
│   │   ├── ClassDetail.tsx  # Sınıf Detay
│   │   ├── CourseDetail.tsx # Ders Detay
│   │   ├── ChatRoom.tsx     # Sohbet Odası
│   │   ├── Messages.tsx     # Mesajlar
│   │   ├── Assignments.tsx  # Ödevler
│   │   └── Profile.tsx      # Profil
│   ├── services/       # Firebase ve veri servisleri
│   ├── types/          # TypeScript tip tanımları
│   ├── App.tsx         # Ana uygulama bileşeni
│   └── main.tsx        # Giriş noktası
├── public/             # Statik dosyalar
├── android/            # Android (Capacitor) projesi
├── package.json        # Bağımlılıklar
└── README.md           # Bu dosya
```

## 👨‍💻 Geliştirici
Mobil Programlama Dersi Projesi — 2025-2026 Bahar Dönemi
