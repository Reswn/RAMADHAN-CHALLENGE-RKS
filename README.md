# 🌙 Ramadhan Portal 2026

> **Challenge 1 - Alhazen Academy Ramadhan Coding Challenge**

<div align="center">

![Ramadhan 2026](https://img.shields.io/badge/Ramadhan-1447H-emerald?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap Icons](https://img.shields.io/badge/Bootstrap_Icons-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Dibuat oleh:** Reni Kartika Suwandi  
**Program:** Alhazen Academy Ramadhan Coding Challenge  
**Tahun:** 2026

</div>

---

## Tentang Proyek

**Ramadhan Portal** adalah website portal ibadah modern yang dirancang khusus untuk membantu umat Muslim dalam menjalani ibadah Ramadhan dengan lebih khusyuk dan terorganisir. Website ini menyediakan kumpulan doa-doa Ramadhan lengkap dengan teks Arab, latin, dan artinya dalam antarmuka yang elegan dan responsif.

Proyek ini dibuat sebagai solusi untuk **Challenge 1 Alhazen Academy Ramadhan Coding Challenge**, mengimplementasikan prinsip desain web modern menggunakan HTML5 semantik dan CSS3 murni tanpa ketergantungan framework berat.

---

##  Fitur Utama

### Halaman Beranda (`index.html`)
- **Hero Section:** Tampilan pembuka yang menarik dengan ilustrasi Ramadhan.
- **Info Tanggal:** Display tanggal Masehi & Hijriah (statik).
- **Quick Access:** Akses cepat ke kategori doa (Sahur, Buka, Malam).
- **Doa Preview:** Pratinjau doa harian dengan tampilan kartu yang indah.
- **Fitur Unggulan:** Penjelasan singkat tentang fitur portal.

###  Halaman Doa (`doa.html`)
Kumpulan doa lengkap dengan sistem **Expandable Card** (klik untuk buka/tutup):
- **🌙 Secton Sahur**
  - Niat Puasa Ramadhan (Wajib)
  - Doa Sebelum Makan Sahur (Sunnah)
- **🌅 Section Buka Puasa**
  - Doa Sebelum Berbuka (Sunnah)
  - Doa Setelah Berbuka (Sunnah)
- **⭐ Section Malam Ramadhan**
  - Doa Lailatul Qadar (10 Malam Terakhir)
  - Doa Memohon Ampunan (Setiap Waktu)

### Desain & UX
- ✅ **Fully Responsive:** Tampilan optimal di Mobile, Tablet, dan Desktop.
- ✅ **Sidebar Navigation:** Menu hamburger dengan sidebar slide-in pada layar kecil.
- ✅ **Islamic Aesthetic:** Pattern geometris Islami dan palet warna hijau emerald.
- ✅ **Smooth Animations:** Transisi halus pada hover, buka card, dan navigasi.
- ✅ **No JavaScript Logic:** Murni HTML & CSS (interaktivitas menggunakan `<details>` & CSS target).
- ✅ **Bootstrap Icons:** Integrasi icon library yang konsisten.

---

## Teknologi yang Digunakan

| Teknologi | Deskripsi |
| :--- | :--- |
| **HTML5** | Struktur halaman semantik |
| **CSS3** | Styling, Layout (Grid/Flexbox), Animasi, Variables |
| **Bootstrap Icons** | Library icon via CDN |
| **Google Fonts** | Font 'Poppins' (UI) dan 'Amiri' (Arab) |

---

##  Struktur Folder

```bash
ramadhan-portal/
│
├── index.html              # Halaman beranda utama
├── doa.html                # Halaman kumpulan doa interaktif
│
├── css/
│   └── style.css           # Combined stylesheet (Global + Page Specific)
│
└── README.md               # Dokumentasi proyek ini
