# 🎬 AnimeVerse

Aplikasi mobile Flutter yang komprehensif untuk menemukan, menilai, dan mengelola daftar anime favorit Anda dengan integrasi Firebase real-time dan autentikasi yang aman.

## 👤 Identitas Mahasiswa

**Nama** : Desi Maria Elita Silalahi
**NIM** : 231401044
**Lab** : Pemrograman Mobile 3

## 📱 Deskripsi Proyek

AnimeVerse adalah aplikasi mobile yang dirancang khusus untuk para penggemar anime di seluruh dunia. Aplikasi ini memberikan pengalaman yang mulus dan intuitif untuk menemukan, menjelajahi, dan mengelola koleksi anime favorit Anda.
Dibangun dengan **Flutter** dan terintegrasi dengan layanan **Firebase**, AnimeVerse menyediakan berbagai fitur modern termasuk:
- Autentikasi aman dengan Email/Password dan Google OAuth
- Database real-time untuk sinkronisasi instan
- Cloud Storage untuk manajemen media
- UI/UX responsif dengan design language modern
- Pencarian dan filtering yang powerful
- Sistem favorit yang dapat dipersonalisasi

## ✨ Fitur Utama

### 🔐 Sistem Autentikasi
- **Sign Up dengan Email & Password** - Registrasi akun baru dengan validasi lengkap
- **Sign In dengan Email & Password** - Login aman dengan autentikasi Firebase
- **Google OAuth Integration** - Sign in dengan satu klik menggunakan akun Google
- **Password Recovery** - Reset password melalui email
- **Session Management** - Sesi login persisten
- **Secure Authentication** - Implementasi keamanan Firebase yang robust

### 🏠 Halaman Beranda (Home Screen)
- **Daftar Anime Terpopuler** - Menampilkan anime trending dan paling populer
- **Search Real-time** - Pencarian instan sambil mengetik
- **Genre Filtering** - Filter anime berdasarkan genre (Action, Adventure, Comedy, Drama, dll)
- **Infinite Scroll** - Loading otomatis saat scroll ke bawah
- **Pull-to-Refresh** - Refresh data dengan gesture tarik ke bawah
- **Loading States** - Feedback visual yang jelas saat loading data
- **Error Handling** - Tampilan error yang informatif dengan tombol retry
- **Genre Filter Info** - Informasi jumlah anime yang ditampilkan

### ❤️ Manajemen Favorit
- **Add/Remove Favorites** - Toggle favorit dengan mudah dari halaman detail
- **Daftar Favorit Lengkap** - Screen khusus untuk melihat semua anime favorit
- **Search Favorites** - Pencarian dalam daftar favorit
- **Persistent Storage** - Favorit disimpan di Firebase Realtime Database
- **Empty State** - Pesan panduan ketika belum ada favorit
- **Real-time Sync** - Sinkronisasi instant antar device

### 📄 Halaman Detail Anime (Detail Screen)
- **Informasi Lengkap** - Judul, rating, genre, sinopsis, dan metadata lainnya
- **Large Image Display** - Poster anime dengan resolusi tinggi
- **Rating & Episode Info** - Informasi rating dan jumlah episode
- **Favorite Toggle Button** - Tombol untuk menambah/menghapus favorit
- **CustomScrollView** - Scroll yang smooth dengan SliverAppBar
- **Error Handling** - Penanganan error saat loading gambar
- **Back Button** - Navigasi mudah kembali ke halaman sebelumnya
- **Responsive Layout** - Adaptif di semua ukuran layar

### 👤 Halaman Profil (Profile Screen)
- **Informasi Akun** - Nama, email, tanggal pembuatan akun
- **Member Badge** - Badge yang menunjukkan kapan menjadi member
- **Change Password** - Dialog untuk mengubah password dengan re-authentication
- **Account Settings** - Pengelolaan preferensi akun
- **App Information** - Informasi tentang aplikasi (versi, dll)
- **Logout Button** - Logout dengan konfirmasi
- **Real-time Sync** - Semua perubahan tersinkronisasi instant
- **Google Account Support** - Deteksi otomatis untuk pengguna Google

### 🔑 Layar Autentikasi

#### Sign In Screen
- Field email dan password dengan validasi
- Show/hide password toggle
- "Forgot Password" button untuk reset password
- Google sign-in button
- Link ke halaman sign up
- Loading state dengan spinner
- Error message yang informatif

#### Sign Up Screen
- Field email dan password dengan validasi
- Password strength indicator
- Show/hide password toggle
- Google sign-up button
- Link ke halaman sign in
- Validasi input real-time
- Loading state

### 🎨 Desain UI/UX
- **Dark Theme** - Tema gelap yang nyaman untuk mata
- **Modern Design** - Design language yang contemporary
- **Responsive Layout** - Sempurna di phone, tablet, dan layar besar
- **Smooth Animations** - Transisi yang halus dan natural
- **Custom Widgets** - Widget reusable yang well-structured
- **Color Scheme** - Palet warna yang konsisten dan menarik
- **Typography** - Font sizing yang terukur dengan MediaQuery
- **Accessibility** - Kontras tinggi, font readable, touch-friendly

## 📸 Screenshot Aplikasi

### 1. Splash Screen
<img width="208" height="462" alt="Screenshot_20251205_200125" src="https://github.com/user-attachments/assets/8dd5a119-5321-41f9-82a8-7c7d31383be6" />

### 2. Halaman Sign In
<img width="208" height="462" alt="Screenshot_20251205_201352" src="https://github.com/user-attachments/assets/446fc9fc-c031-4021-b484-91160c33b5a1" />

**Fitur**: Email/password validation, forgot password, social login, error handling

### 3. Halaman Sign Up
<img width="208" height="462" alt="Screenshot_20251205_201402" src="https://github.com/user-attachments/assets/4c972949-d355-4ad3-8a6c-88ba946af5cf" />

**Fitur**: Input validation, password strength, social registration

### 4. Halaman Beranda (Home Screen)
<img width="208" height="462" alt="Screenshot_20251205_201537" src="https://github.com/user-attachments/assets/b231b0cc-44d6-43e7-9317-140950e870be" />

**Fitur**: Search, genre filter, infinite scroll, pull-to-refresh, pagination

### 5. Halaman Detail Anime (Detail Screen)
<img width="208" height="462" alt="Screenshot_20251205_224640" src="https://github.com/user-attachments/assets/2b79118a-4f26-4886-b470-2bd0134f2ef2" />

**Fitur**: Informasi lengkap, poster berkualitas tinggi, favorite toggle, responsive

### 6. Halaman Favorit (Favorite Screen)
<img width="208" height="462" alt="Screenshot_20251205_201558" src="https://github.com/user-attachments/assets/60a3a772-89b5-46b2-a204-b3a16dc29336" />

**Fitur**: Search favorit, list interaktif, remove button, empty state

### 7. Halaman Profil (Profile Screen)
<img width="208" height="462" alt="Screenshot_20251205_201634" src="https://github.com/user-attachments/assets/e96ce676-e373-4605-9d8f-a67c423c14eb" />

**Fitur**: User info, avatar, password change, logout, app info

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: Flutter 
- **Language**: Dart 
- **State Management**: Provider Pattern
- **Routing**: GoRouter untuk navigasi type-safe
- **HTTP Client**: Dio untuk API calls

### Backend & Cloud Services
- **Authentication**: Firebase Authentication
- **Real-time Database**: Firebase Realtime Database
- **Cloud Storage**: Firebase Cloud Storage
- **API Source**: Jikan API (MyAnimeList Unofficial API)

### Development & Tools
- **IDE**: Android Studio / VS Code dengan Flutter extension
- **Version Control**: Git & GitHub
- **Testing Framework**: Flutter Test
- **Build System**: Gradle (Android), Xcode (iOS)

### Key Technologies
 **UI Framework** Flutter 
 **Language** Dart 
 **State Management** Provider 
 **Navigation** GoRouter  
 **HTTP Client** Dio  
 **Authentication** Firebase Auth  
 **Database** Firebase Realtime DB  
 **Storage** Firebase Cloud Storage  
 **Image Caching** cached_network_image 
 **SVG Support** flutter_svg 
 **Image Picker** image_picker 

## 💻 Instalasi & Setup
### Prasyarat
- **Flutter SDK**: Versi 3.0 atau lebih tinggi
- **Dart SDK**: Versi 3.0 atau lebih tinggi (included dengan Flutter)
- **IDE**: Android Studio, VS Code, atau IntelliJ IDEA
- **Git**: Untuk version control
- **Firebase Account**: Untuk setup backend

### Langkah-Langkah Instalasi

#### 1. Clone Repository
```bash
git clone https://github.com/rielyta/Anime-Verse.git
cd Anime-Verse
```

#### 2. Install Dependencies
```bash
# Install semua dependencies flutter
flutter pub get

# Update dependencies ke versi terbaru (opsional)
flutter pub upgrade
```

#### 3. Setup Firebase

##### A. Create Firebase Project
1. Buka [Firebase Console](https://console.firebase.google.com)
2. Klik "Create a new project"
3. Masukkan nama project (misal: AnimeVerse)
4. Follow setup wizard

##### B. Android Setup
1. Di Firebase Console, tambahkan Android app
2. Masukkan Package Name: `com.example.anime_verse`
3. Download `google-services.json`
4. Letakkan di `android/app/`

##### C. iOS Setup (jika diperlukan)
1. Tambahkan iOS app di Firebase Console
2. Download `GoogleService-Info.plist`
3. Letakkan di `ios/Runner/`
4. Jangan lupa add ke Xcode project

##### D. Konfigurasi Layanan Firebase

**Enable Authentication:**
- Buka Firebase Console → Authentication
- Enable Email/Password provider
- Enable Google Sign-In
- Configure OAuth consent screen di Google Cloud Console

**Setup Realtime Database:**
- Buka Firebase Console → Realtime Database
- Create Database
- Set rules dengan security rules di bawah:
```json
{
  "rules": {
    "users": {
      "$uid": {
        ".read": "$uid === auth.uid",
        ".write": "$uid === auth.uid"
      }
    },
    "favorites": {
      "$uid": {
        ".read": "$uid === auth.uid",
        ".write": "$uid === auth.uid"
      }
    }
  }
}
```

**Setup Cloud Storage:**
- Buka Firebase Console → Cloud Storage
- Create bucket
- Set rules untuk image storage

#### 4. Konfigurasi Environment
```bash
# Pastikan menggunakan Flutter channel stable
flutter channel stable

# Update Flutter
flutter upgrade

# Check dependencies
flutter doctor
```

#### 5. Run Project

```bash
# List connected devices
flutter devices

# Run di Android Emulator
flutter run -d emulator-5554

# Run di iOS Simulator
flutter run -d ios

# Run di Device Fisik
flutter run

# Run dengan verbose output (debugging)
flutter run -v
```

#### 6. Build Release

```bash
# Android APK
flutter build apk --release

# Android App Bundle (untuk Play Store)
flutter build appbundle --release

# iOS App
flutter build ios --release
```

---

## 🏗️ Arsitektur Proyek

### Pola MVVM + Provider

Aplikasi menggunakan arsitektur **Model-View-ViewModel (MVVM)** yang dikombinasikan dengan **Provider Pattern** untuk state management:

```
UI Layer (Screens)
    ↓
ViewModel Layer (Providers)
    ↓
Services Layer
    ↓
Data Layer (Models)
```

### State Management Flow

- **User Interaction** → **Provider Method** → **Service Processing** → **Data Update** → **UI Rebuild**

### Keuntungan Arsitektur Ini
- Separation of Concerns
- Reusability widgets
- Testability yang mudah
- Maintainability kode
- Scalability fitur baru

---

## 📁 Struktur Folder

```
anime_verse/
├── android/                      # Android config
├── ios/                          # iOS config
├── lib/
│   ├── main.dart                # Entry point
│   ├── config/
│   │   ├── routes.dart
│   │   ├── theme.dart
│   │   └── constants.dart
│   ├── models/
│   │   ├── anime.dart
│   │   ├── user.dart
│   │   └── favorite.dart
│   ├── provider/
│   │   ├── auth_provider.dart
│   │   ├── app_state_provider.dart
│   │   └── user_provider.dart
│   ├── screens/
│   │   ├── signin_screen.dart
│   │   ├── signup_screen.dart
│   │   ├── home_screen.dart
│   │   ├── detail_screen.dart
│   │   ├── favorite_screen.dart
│   │   └── profile_screen.dart
│   ├── widgets/
│   │   ├── app_scaffold.dart
│   │   ├── anime_card.dart
│   │   ├── favorite_anime_card.dart
│   │   └── genre_list.dart
│   ├── services/
│   │   ├── firebase_service.dart
│   │   ├── auth_service.dart
│   │   ├── anime_service.dart
│   │   └── storage_service.dart
│   └── utils/
│       ├── validators.dart
│       ├── snackbar_helper.dart
│       └── constants.dart
├── pubspec.yaml
└── README.md
```

---

## 📦 Dependency & Package

### Core Dependencies
```yaml
provider: ^6.0.0              # State management
go_router: ^10.0.0            # Navigation
firebase_core: ^2.x           # Firebase
firebase_auth: ^4.x           # Auth
firebase_database: ^10.x      # Database
firebase_storage: ^11.x       # Storage
dio: ^5.x                     # HTTP
cached_network_image: ^3.x    # Image caching
flutter_svg: ^2.x             # SVG support
image_picker: ^1.x            # Image picker
```

---

## 🚀 Link Demo & Repository

### Repository
**GitHub**: [github.com/rielyta/Anime-Verse](https://github.com/rielyta/AnimeVerse)

### Link Demo
**Video**: https://drive.google.com/file/d/14hZeAzXEIFi6LD7lng7QalQGlrJkCmFf/view?usp=drivesdk

