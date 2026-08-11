# Beta v1.Agustus.26

Aplikasi Android WARUNG BUMDes berbasis WebView dengan pencarian produk pintar.

## Build APK otomatis dengan GitHub Actions

1. Buat repository baru di GitHub.
2. Upload seluruh isi folder proyek ini ke repository.
3. Commit ke branch `main` atau `master`.
4. Buka tab **Actions**.
5. Pilih workflow **Build Beta v1.Agustus.26 APK**.
6. Jika perlu, tekan **Run workflow**.
7. Setelah selesai, buka hasil workflow → bagian **Artifacts**.
8. Download **Beta-v1.Agustus.26-APK** dan ambil `app-debug.apk`.
9. Pindahkan APK ke HP Android lalu install.

Workflow memakai JDK 17, Gradle 8.7, dan Android Gradle Plugin 8.5.2.

## Catatan

- APK yang dibuat workflow adalah debug APK dan cocok untuk instalasi/testing.
- Data aplikasi menggunakan penyimpanan lokal perangkat.
- Untuk APK release yang ditandatangani, diperlukan keystore/signing configuration.
