# 📏 D-Estima

**Aplikasi Prediksi Tinggi Badan**
---

## 📘 Deskripsi

**D-Estima** adalah aplikasi mobile yang digunakan untuk memperkirakan tinggi badan seseorang dengan memasukkan dua data antropometri:

* **Panjang Lengan**
* **Lingkar Lengan Atas**

Aplikasi ini dilengkapi dengan fitur pendukung seperti **riwayat prediksi**, **ekspor ke Excel**, **pengaturan tema**, dan **pengaturan bahasa**, sehingga lebih fleksibel dan informatif untuk berbagai kebutuhan, baik penelitian maupun penggunaan pribadi.

---

## ✨ Fitur Utama

### 🔢 1. Prediksi Tinggi Badan

* Pengguna memasukkan panjang lengan atas serta panjang bahu.
* Aplikasi menghitung dan menampilkan hasil estimasi tinggi badan secara otomatis.

### 🕘 2. History (Riwayat Prediksi)

* Menyimpan seluruh hasil prediksi sebelumnya.
* Memudahkan pengguna untuk melihat perkembangan atau hasil prediksi yang pernah dilakukan.

### 📤 3. Export to Excel

* Riwayat prediksi dapat diekspor menjadi file **Excel (.xlsx)**.
* Cocok untuk kebutuhan penelitian, laporan, atau dokumentasi.

### 🎨 4. Tema (Light & Dark Mode)

* Tersedia fitur **ganti tema** sesuai preferensi pengguna.

### 🌐 5. Ganti Bahasa

* Mendukung **multi-language** (misalnya Bahasa Indonesia & English).
* Pengguna dapat mengganti bahasa langsung dari pengaturan aplikasi.

---

## 🛠️ Teknologi yang Digunakan

* **Dart** – bahasa pemrograman utama
* **Flutter** – framework UI cross-platform
* **Provider / GetX / Bloc** (sesuai implementasi kamu)
* **Package Excel** (untuk ekspor data)
* **SharedPreferences / Hive** (untuk menyimpan history & tema)

---

## 📱 Cara Menjalankan Aplikasi (Flutter)

### 1️⃣ Instal Flutter Terlebih Dahulu

Cek instalasi:

```bash
flutter --version
```

Jika belum ada, instal sesuai panduan resmi:
[https://docs.flutter.dev/get-started/install](https://docs.flutter.dev/get-started/install)

---

### 2️⃣ Clone Repository

```bash
git clone https://github.com/username/d-estima.git
cd d-estima
```

---

### 3️⃣ Install Dependency

```bash
flutter pub get
```

---

### 4️⃣ Jalankan Aplikasi

```bash
flutter run
```

---

### 5️⃣ Build APK

```bash
flutter build apk
```

Hasil APK dapat ditemukan di:

```
build/app/outputs/flutter-apk/app-release.apk
```

---

## 📥 Cara Install APK di Android

1. Kirim file APK ke HP
2. Buka file tersebut
3. Izinkan instalasi dari "Unknown Sources" jika diminta
4. Aplikasi siap digunakan

---

## 📂 Struktur Folder (Opsional, jika ingin dicantumkan)

```
lib/
 ├── main.dart
 ├── screens/
 ├── widgets/
 ├── models/
 ├── services/
 ├── controllers/
 ├── utils/
assets/
pubspec.yaml
README.md
```

---

## 🎯 Tujuan Pengembangan

D-Estima dirancang untuk:

* Mendukung penelitian antropometri
* Membantu tenaga kesehatan atau pendidikan
* Menyediakan alat praktis bagi pengguna umum untuk memprediksi tinggi badan
* Mempermudah dokumentasi data melalui fitur riwayat dan ekspor Excel

---

## 👨‍💻 Developer

Dibuat oleh: **Natha Widya Putra Nugraha**


