# OVAN Camera — GitHub Build

## Jangan deploy ke Railway
Ini adalah proyek Android. Railway bukan tempat menjalankan source APK ini.

## Upload ke GitHub
Upload seluruh isi folder proyek ini ke repository GitHub.

## Build APK otomatis
Setelah push ke GitHub:
1. Buka tab **Actions**.
2. Pilih **Build OVAN Camera APK**.
3. Tunggu sampai selesai.
4. Buka hasil workflow dan download artifact **OVAN-Camera-debug-apk**.
5. Ekstrak artifact untuk mendapatkan `app-debug.apk`.

Anda juga bisa menjalankan workflow manual dari **Actions → Build OVAN Camera APK → Run workflow**.
