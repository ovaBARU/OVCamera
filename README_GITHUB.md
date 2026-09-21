# OVAN Camera — GitHub Actions APK Build

## PENTING
Ini adalah proyek Android. **Jangan deploy ke Railway.**

### Upload ke GitHub
Upload seluruh isi folder proyek ke repository GitHub. Pastikan folder tersembunyi berikut ikut ter-upload:

`.github/workflows/ovan-camera-apk.yml`

Setelah upload:

1. Buka repository GitHub.
2. Klik **Actions**.
3. Di daftar workflow sebelah kiri harus muncul **Build OVAN Camera APK**.
4. Klik workflow tersebut.
5. Klik **Run workflow** → pilih branch `main` → **Run workflow**.
6. Tunggu sampai selesai.
7. Buka hasil workflow dan bagian **Artifacts**.
8. Download **OVAN-Camera-debug-apk**.
9. Ekstrak artifact dan install `app-debug.apk` di Android.

### Jika Actions masih tidak muncul
Buka **Settings → Actions → General** dan pastikan Actions diizinkan untuk repository tersebut.

Jangan upload ZIP sebagai isi aplikasi Railway. GitHub membutuhkan file proyek, termasuk folder `.github/workflows/`.
