# TEMAN GUSTY — Build APK dari HP

Paket ini sudah berisi source TEMAN GUSTY dan workflow GitHub Actions untuk membuat APK otomatis di cloud.

## Cara singkat
1. Buat repository GitHub baru, misalnya `teman-gusty`.
2. Upload semua isi folder ini ke repository tersebut (termasuk `.github/workflows/android.yml`).
3. Buka tab **Actions** → pilih **Build TEMAN GUSTY APK** → **Run workflow**.
4. Setelah selesai, buka hasil workflow → bagian **Artifacts** → download `TEMAN-GUSTY-APK`.
5. Ekstrak ZIP artifact dan install `app-debug.apk` di HP.

Tidak perlu memasukkan service_role key. Source memakai publishable key Supabase.

Catatan: APK debug cocok untuk uji/install langsung. Untuk Google Play, buat release build yang ditandatangani dengan kunci milik pengembang.
