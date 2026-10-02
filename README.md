# 🏛 Sistem Informasi Manajemen Desa Pabuaran

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

Sistem Informasi Manajemen Desa Pabuaran adalah aplikasi berbasis web yang dirancang untuk memfasilitasi transparansi informasi publik dan mempermudah administrasi pelayanan bagi warga. Sistem ini terbagi menjadi dua antarmuka utama: portal publik (Frontend) untuk masyarakat dan panel kendali terintegrasi (Backend) untuk aparatur desa.

---

## ✨ Fitur Utama

### 👥 Portal Publik (Frontend)
Portal interaktif yang dapat diakses oleh masyarakat umum untuk mendapatkan informasi terkini:
*   **Beranda & Profil Desa:** Menampilkan informasi umum, Sambutan Kepala Desa, Sejarah, serta Visi & Misi Desa Pabuaran.
*   **Struktur Pemerintahan:** Visualisasi bagan kepengurusan desa dan susunan keanggotaan Badan Permusyawaratan Desa (BPD).
*   **Katalog Potensi Desa:** Etalase digital sektor unggulan desa (BUMDes, UMKM, Pertanian, Perikanan, Peternakan, dan Koperasi).
*   **Pusat Informasi & Berita:** Modul artikel dinamis untuk publikasi kegiatan dan pengumuman desa.
*   **Pusat Layanan Warga:** Fasilitas unduh *template* surat pengantar resmi (Domisili, dll) dan panduan alur pengajuan proposal.
*   **Statistik Demografi:** Dasbor visual angka statistik penduduk, kepala keluarga, dusun, posyandu, dan fasilitas umum lainnya.

### ⚙️ Panel Admin (Backend)
Sistem manajemen basis data (CMS) khusus untuk perangkat desa mengelola seluruh konten:
*   **Keamanan:** Autentikasi halaman Login khusus Admin Desa.
*   **Dashboard Terpusat:** Akses cepat ke berbagai modul manajemen utama.
*   **Manajemen Struktural:** Fitur CRUD (Create, Read, Update, Delete) untuk mengelola data kepegawaian dan kepengurusan BPD.
*   **Manajemen Berita & Publikasi:** Editor artikel untuk menulis dan mempublikasikan berita kegiatan desa.
*   **Manajemen Layanan:** Pengelolaan berkas *template* surat warga dan pemantauan pengajuan proposal.
*   **Manajemen Statistik & Slide:** Pembaruan data numerik demografi desa dan gambar *banner/slide* secara *real-time*.

---

## 💻 Tech Stack

*   **Framework:** Laravel (PHP 8.x)
*   **Database:** MySQL
*   **Frontend:** Bootstrap 5, HTML5, CSS3
*   **Icons:** Bootstrap Icons
*   **Database Tools:** TablePlus

---

## 📸 Dokumentasi Antarmuka

### 🖥️ Portal Publik (Frontend)

| Halaman | Tampilan |
| :--- | :--- |
| **Beranda** | <img src="docs/Home%20Page.png" width="400"> |
| **Visi & Misi** | <img src="docs/Visi%20%26%20Misi.png" width="400"> |
| **Sejarah Desa** | <img src="docs/Sejarah%20Desa.png" width="400"> |
| **Sambutan Kades** | <img src="docs/Sambutan%20Kepala%20Desa.png" width="400"> |
| **Kepengurusan** | <img src="docs/Halaman%20Struktural.png" width="400"> |
| **Potensi Desa** | <img src="docs/Potensi%20Desa.png" width="400"> |
| **Berita Desa** | <img src="docs/Halaman%20Berita.png" width="400"> |
| **Statistik** | <img src="docs/Statistik%20Penduduk.png" width="400"> |
| **Template Surat** | <img src="docs/Tamplate%20Surat.png" width="400"> |
| **Pengajuan Proposal**| <img src="docs/Tamplate%20Proposal.png" width="400"> |

### 🛠️ Panel Admin (Backend)

| Modul | Tampilan |
| :--- | :--- |
| **Login Admin** | <img src="docs/Backend%20-%20Halaman%20Login%20Admin.png" width="400"> |
| **Dashboard** | <img src="docs/Backend-%20Home%20Page.png" width="400"> |
| **Manajemen Struktural** | <img src="docs/Backend%20-%20Data%20Struktural.png" width="400"> |
| **Manajemen Berita** | <img src="docs/Backend%20-%20Halaman%20Managemen%20Berita.png" width="400"> |
| **Manajemen Potensi** | <img src="docs/Backend%20-%20Halaman%20Pontensi%20Desa.png" width="400"> |
| **Manajemen Statistik** | <img src="docs/Backend%20-%20Halaman%20Statistik.png" width="400"> |
| **Template Surat** | <img src="docs/Backend%20-%20Halaman%20Surat.png" width="400"> |
| **Pengajuan Proposal** | <img src="docs/Backend%20-%20Pengajuan%20Proposal.png" width="400"> |
| **Manajemen Slide** | <img src="docs/Backend%20-%20Halaman%20Slide.png" width="400"> |

---

## 🚀 Panduan Instalasi Lokal

Ikuti instruksi berikut untuk menjalankan proyek ini di lingkungan pengembangan lokal:

1. **Kloning Repositori:**
   ```bash
   git clone [https://github.com/username-anda/web_desa.git](https://github.com/username-anda/web_desa.git)
   cd web_desa