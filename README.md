<h1 align="center">📱 IP-LAUNCHER</h1>

<p align="center">
  Launcher Android bergaya iOS dengan ikon kustom<br>
  Kotlin + Jetpack Compose
</p>

<p align="center">
  <a href="GANTI_DENGAN_LINK_RILIS">
    <img src="https://img.shields.io/badge/⬇️_DOWNLOAD-IP--LAUNCHER--V1.apk-6C3CE9?style=for-the-badge&logo=android&logoColor=white" alt="Download APK">
  </a>
</p>

---

## ✨ Fitur

- 🏠 **Beranda** grid 4 kolom, dock kaca, dan titik halaman
- 📚 **App Library** dengan pencarian aplikasi
- 🎭 **Ikon kustom**: nama dan gambar ikon terpisah dari aplikasi tujuan
  (contoh: ikon "App Store" membuka Play Store, ikon "Safari" membuka browser bawaan)
- ✏️ **Atur ikon**: tekan lama ikon untuk mengubah nama, gambar, dan aplikasi yang dibuka
- 🔒 **Layar kunci gaya iOS**: jam besar, senter, kamera, geser ke atas untuk membuka

Semua ikon dan tampilan memakai desain orisinal.

## 📋 Syarat

- Android 8.0 (API 26) atau lebih baru

## 📥 Cara pasang

1. Unduh `IP-LAUNCHER-V1.apk` dari halaman rilis
2. Pasang, lalu buka **IP-LAUNCHER Setup**
3. Tekan **Jadikan beranda bawaan**
4. *(Opsional)* Aktifkan layar kunci:
   - Beri izin **tampil di atas aplikasi lain**
   - Izinkan **notifikasi**
   - Nyalakan saklar **Aktifkan layar kunci**

## 🎭 Cara mengubah ikon

1. Tekan lama ikon di beranda
2. Ubah **nama**, pilih **aplikasi tujuan**, atau pilih **gambar ikon** dari galeri
3. Tekan **Simpan**. Tombol **Reset ikon** mengembalikan gambar awal

## ⚠️ Batasan

- Android tidak mengizinkan aplikasi mengganti layar kunci sistem. Layar kunci gaya iOS tampil lebih dulu, lalu layar kunci asli HP (PIN/sidik jari) muncul setelah geser ke atas.
- Aplikasi tujuan ikon berbeda antar HP. Jika tidak ditemukan, tekan lama ikon untuk memilihnya.
- Layanan layar kunci perlu dinyalakan lagi setelah HP restart, dan bisa dimatikan oleh penghemat baterai.
- Ini build debug dan belum tersedia di Play Store.

## 🛠️ Build sendiri

Proyek ini dibangun otomatis oleh GitHub Actions.

1. Upload proyek ke repo GitHub
2. Buka tab **Actions** dan jalankan workflow **Build IP-LAUNCHER APK**
3. Unduh artifact **IP-LAUNCHER-V1**, isinya `IP-LAUNCHER-V1.apk`

Atau buka folder proyek di Android Studio, lalu **Build → Build APK**.

## 🧰 Teknologi

Kotlin · Jetpack Compose · Material 3 · Foreground Service · GitHub Actions

## 📄 Catatan

IP-LAUNCHER adalah proyek independen dan tidak berafiliasi dengan Apple Inc.
iOS dan iPhone adalah merek dagang milik Apple Inc.
