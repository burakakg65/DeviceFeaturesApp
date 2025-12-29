# Device Features App

##  Mobil Programlama – Cihaz Özellikleri Uygulaması

Bu proje, Mobil Programlama dersi kapsamında React Native ve Expo kullanılarak geliştirilmiştir.  
Uygulamada mobil cihazların yerel donanım ve yazılım özelliklerine erişim sağlanmıştır.

---

##  Öğrenci Bilgileri
- **Ad Soyad:** Muhammed Burak Akgümüş
- ** Öğrenci No:** 220404059
- **Ders:** Mobil Programlama  
- **Lab:** Cihaz Özellikleri Uygulaması

---

##  Projenin Amacı
Bu uygulamanın amacı, Expo API’leri kullanılarak mobil cihazın temel özelliklerine güvenli ve doğru bir şekilde erişmeyi öğrenmektir.

Proje kapsamında aşağıdaki konular uygulanmıştır:
- İzin yönetimi
- Kamera ve galeri kullanımı
- GPS konum erişimi
- Yerel bildirimler
- Dokunsal geri bildirim (Haptics)
- Çok ekranlı navigasyon yapısı

---

##  Uygulama Özellikleri
-  Kamera ile fotoğraf çekme
-  Galeriden fotoğraf seçme
-  Mevcut GPS konumunu alma
-  Yerel bildirim gösterme
-  Başarılı işlemlerde titreşim (Haptics)

---

##  Ekran Yapısı
/screens
├── HomeScreen.js
├── CameraScreen.js
└── LocationScreen.js


- **HomeScreen:** Uygulamanın ana ekranı
- **CameraScreen:** Kamera ve galeri işlemleri
- **LocationScreen:** Konum ve bildirim işlemleri

---

##  Kurulum ve Çalıştırma

### 1️⃣ Gerekli Araçlar
- Node.js
- npm
- Expo Go (mobil cihazda)

### 2️⃣ Projeyi Klonla
```bash
git clone <GITHUB_REPO_LINK>
cd DeviceFeaturesApp

npm install
npx expo start  (Expo Go uygulaması ile QR kod okutularak proje çalıştırılabilir.)

