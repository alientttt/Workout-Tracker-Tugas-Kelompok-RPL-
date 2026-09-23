# Workout-Tracker-Tugas-Kelompok-RPL

Aplikasi pencatatan kebugaran (*Progressive Web App*) yang dirancang untuk membebaskan beban kognitif pengguna melalui pencatatan instan dan manajemen waktu istirahat otomatis yang dinamis. 

## Fitur Utama
* **One-Tap Logging:** Antarmuka tombol penyelesaian berukuran besar untuk menyimpan rekam jejak repetisi dan beban secara instan.
* **Auto-Rest Timer:** Logika asinkronus yang langsung menghitung mundur waktu istirahat dan memicu *haptic feedback* sesaat setelah set diselesaikan.
* **Exercise Swap:** Navigasi penukaran urutan gerakan secara dinamis dengan rekomendasi substitusi kelompok otot yang sama.
* **Dashboard Analytics:** Visualisasi metrik *Progressive Overload* dan riwayat *Personal Record* (PR) pengguna.

## Arsitektur & Teknologi
Sistem ini menggunakan arsitektur *Decoupled* (pemisahan Frontend dan Backend) yang dieksekusi secara efisien menggunakan ekosistem JavaScript:
* **Frontend:** React (Vite) dengan Tailwind CSS, mengimplementasikan antarmuka *mobile-first* yang dikalibrasi pada *8px grid system*.
* **Backend:** Node.js (Express) dieksekusi menggunakan **Bun** untuk optimasi memori yang ringan.
* **Storage:** Sinkronisasi *Cloud Database* eksternal dengan retensi *Web Storage API* (localStorage) untuk akses *offline*.

## Dokumentasi Rekayasa Perangkat Lunak
Seluruh rancangan sistem mengacu pada dokumen Spesifikasi Kebutuhan Perangkat Lunak (SRS) format Karl E. Wiegers.
* **SRS Workout Tracker R7U.pdf**

## Anggota Kelompok 1
* **Akmal Mahesa** - *202343501641*
* **Ifal Maulana** - *202343501627*
* **Zahra Aulia Salsabila** - *202343501626*
