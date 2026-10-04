# Workout-Tracker-Tugas-Kelompok-RPL

Aplikasi pencatatan kebugaran (*Progressive Web App*) yang dirancang untuk membebaskan beban kognitif pengguna melalui pencatatan instan dan manajemen waktu istirahat otomatis yang dinamis. 

## Dokumentasi Rekayasa Perangkat Lunak
Seluruh rancangan sistem mengacu pada dokumen Spesifikasi Kebutuhan Perangkat Lunak (SRS) format Karl E. Wiegers.
* **SRS Workout Tracker R7U.pdf**
* UML = **https://lucid.app/lucidchart/36b0e2e9-6d09-4c3f-abc8-83a9aaa4b1e1/edit?viewport_loc=-1048%2C-372%2C3242%2C1760%2C0_0&invitationId=inv_3842862e-9c57-4301-87b0-b7750c3b470f**

## Anggota Kelompok 1
* **Akmal Mahesa** - *202343501641*
* **Ifal Maulana** - *202343501627*
* **Zahra Aulia Salsabila** - *202343501626*

## Fitur Utama
* **One-Tap Logging:** Antarmuka tombol penyelesaian berukuran besar untuk menyimpan rekam jejak repetisi dan beban secara instan.
* **Auto-Rest Timer:** Logika asinkronus yang langsung menghitung mundur waktu istirahat dan memicu *haptic feedback* sesaat setelah set diselesaikan.
* **Exercise Swap:** Navigasi penukaran urutan gerakan secara dinamis dengan rekomendasi substitusi kelompok otot yang sama.
* **Dashboard Analytics:** Visualisasi metrik *Progressive Overload* dan riwayat *Personal Record* (PR) pengguna.

## Arsitektur & Teknologi
Sistem ini menggunakan arsitektur *Decoupled* (pemisahan Frontend dan Backend) yang dieksekusi secara efisien menggunakan ekosistem JavaScript:
* **Frontend:** React (Vite) dengan Tailwind CSS*.
* **Backend:** Node.js (Express) dieksekusi menggunakan **Bun**.
* **Storage:** Sinkronisasi *Cloud Database* eksternal dengan retensi *Web Storage API* (localStorage) untuk akses *offline*.

