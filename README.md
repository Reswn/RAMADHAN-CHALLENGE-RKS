# 🌙 Ramadhan Space 2026

> **Alhazen Academy Ramadhan Coding Challenge**

### 📊 Challenge Progress Tracker

| Challenge       | Fitur Utama                      |    Status    | Deploy                                                          |
| :-------------- | :------------------------------- | :----------: | :-------------------------------------------------------------- |
| **Challenge 1** | Portal Doa (Sahur, Buka, Malam)  | ✅ Completed | [Live Review](https://ramadhan-challenge-rks.vercel.app/)       |
| **Challenge 2** | Hitung Zikir Interactive Counter | ✅ Completed | [Live Review](https://ramadhan-challenge2-rks-v19f.vercel.app/) |
| **Challenge 3** | _Coming Soon_                    |  ⏳ Pending  | -                                                               |
| **Challenge 4** | _Coming Soon_                    |  ⏳ Pending  | -                                                               |

---

<div align="center">

![Ramadhan 2026](https://img.shields.io/badge/Ramadhan-1447H-emerald?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap Icons](https://img.shields.io/badge/Bootstrap_Icons-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Dibuat oleh:** Reni Kartika Suwandi  
**Program:** Alhazen Academy Ramadhan Coding Challenge  
**Tahun:** 2026

</div>

---

## 📖 Tentang Proyek

**Ramadhan Space** adalah website portal ibadah modern yang dirancang khusus untuk membantu umat Muslim dalam menjalani ibadah Ramadhan dengan lebih khusyuk dan terorganisir. Website ini menyediakan kumpulan doa-doa Ramadhan lengkap dengan teks Arab, latin, artinya, serta fitur **Hitung Zikir Interactive** untuk membantu konsistensi dzikir harian.

Proyek ini merupakan kelanjutan dari **Challenge 1** dan dibuat untuk memenuhi **Challenge 2 Alhazen Academy Ramadhan Coding Challenge**, dengan menambahkan fitur counter zikir yang interaktif, dark mode, local storage, dan animasi yang lebih advanced menggunakan JavaScript.

---

## 🎯 Challenge 2 - Fitur Baru

### 📄 Halaman Hitung Zikir (`hitung-zikir.html`)

| Fitur                 | Deskripsi                                         | Status |
| :-------------------- | :------------------------------------------------ | :----: |
| **Counter Zikir**     | Menampilkan jumlah dzikir saat ini dengan animasi |   ✅   |
| **Tombol Tambah**     | Untuk menambah hitungan dzikir dengan efek scale  |   ✅   |
| **Tombol Reset**      | Untuk mengulang hitungan dari nol                 |   ✅   |
| **Target Dzikir**     | Menampilkan dan menyesuaikan target (33/100)      |   ✅   |
| **Badge/Notifikasi**  | Muncul saat target tercapai dengan confetti       |   ✅   |
| **Progress Bar**      | Visual progress menuju target                     |   ✅   |
| **Dark Mode**         | Toggle mode gelap/terang dengan save preference   |   ✅   |
| **Local Storage**     | Data tersimpan otomatis (count, streak, stats)    |   ✅   |
| **Stats Overview**    | Total Zikir, Hari Berturut, Target Selesai        |   ✅   |
| **12 Zikir Pilihan**  | Subhanallah, Alhamdulillah, dll dengan fadhilah   |   ✅   |
| **Keyboard Support**  | Space untuk tambah, R untuk reset                 |   ✅   |
| **Responsive Design** | Mobile, Tablet, Desktop friendly                  |   ✅   |

---

## 🚀 Fitur Lengkap

### 🏠 Halaman Beranda (`index.html`)

- **Hero Section:** Tampilan pembuka yang menarik dengan ilustrasi Ramadhan
- **Info Tanggal:** Display tanggal Masehi & Hijriah
- **Quick Access:** Akses cepat ke kategori doa & zikir
- **Doa Preview:** Pratinjau doa harian dengan tampilan kartu
- **Fitur Unggulan:** Penjelasan fitur portal (Doa & Zikir)
- **Dark Mode Toggle:** Switch mode gelap/terang

### 📿 Halaman Doa (`doa.html`)

Kumpulan doa lengkap dengan sistem **Expandable Card**:

- **🌙 Section Sahur**
  - Niat Puasa Ramadhan (Wajib)
  - Doa Sebelum Makan Sahur (Sunnah)
- **🌅 Section Buka Puasa**
  - Doa Sebelum Berbuka (Sunnah)
  - Doa Setelah Berbuka (Sunnah)
- **⭐ Section Malam Ramadhan**
  - Doa Lailatul Qadar (10 Malam Terakhir)
  - Doa Memohon Ampunan (Setiap Waktu)

### 📿 Halaman Hitung Zikir (`hitung-zikir.html`) **🆕**

Counter zikir interaktif dengan fitur lengkap:

- **Counter Display:** Angka besar dalam lingkaran gradient
- **Target Adjustment:** Tombol +/- untuk ubah target
- **Progress Bar:** Visual progress dengan warna dinamis
- **Notification:** Popup "Target Tercapai!" dengan confetti
- **Stats Cards:** Total Zikir, Streak Hari, Target Completed
- **12 Zikir Options:** Dengan lafal Arab, arti, dan fadhilah
- **Fadhilah Section:** Keutamaan masing-masing zikir dengan dalil
- **Benefits Grid:** 4 keutamaan umum berzikir

---

## 🛠️ Teknologi yang Digunakan

| Teknologi           | Versi  | Deskripsi                                          |
| :------------------ | :----- | :------------------------------------------------- |
| **HTML5**           | -      | Struktur halaman semantik                          |
| **CSS3**            | -      | Styling, Layout (Grid/Flexbox), Animasi, Variables |
| **JavaScript**      | ES6+   | Counter logic, Local Storage, Dark Mode, Events    |
| **Bootstrap Icons** | 1.11.3 | Library icon via CDN                               |
| **Google Fonts**    | -      | Font 'Poppins' (UI) dan 'Amiri' (Arab)             |
| **Vercel**          | -      | Deployment & Hosting                               |

---

## 📁 Struktur Folder

```bash
ramadhan-space/
│
├── index.html              # Halaman beranda utama
├── doa.html                # Halaman kumpulan doa interaktif
├── hitung-zikir.html       # 🆕 Halaman counter zikir (Challenge 2)
│
├── css/
│   └── style.css           # Combined stylesheet (Global + All Pages)
│
├── assets/
│   └── logo.png            # Logo Ramadhan Space
│
└── README.md               # Dokumentasi proyek ini
```

---

## 🎨 Color Palette

| Warna                | Kode      | Penggunaan                    |
| :------------------- | :-------- | :---------------------------- |
| **Primary Green**    | `#10b981` | Warna utama, tombol, gradient |
| **Primary Light**    | `#34d399` | Hover effects, accents        |
| **Primary Dark**     | `#059669` | Active states, shadows        |
| **Accent Gold**      | `#f59e0b` | Arabic text, highlights       |
| **Background Light** | `#f0fdfa` | Light mode background         |
| **Background Dark**  | `#0f172a` | Dark mode background          |
| **Text Main**        | `#1f2937` | Primary text (light)          |
| **Text Light**       | `#f1f5f9` | Primary text (dark)           |

---

## 🚀 Cara Menjalankan

### Metode 1: Langsung di Browser

1. Download/clone repository ini
2. Buka file `index.html` dengan browser (Chrome, Firefox, Edge)
3. Website siap digunakan!

### Metode 2: Menggunakan Live Server (VS Code)

1. Install extension **Live Server** di VS Code
2. Buka folder proyek di VS Code
3. Klik kanan pada `index.html`
4. Pilih **"Open with Live Server"**
5. Website akan terbuka di browser dengan auto-reload

### Metode 3: Deployment ke Vercel

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel

# Follow prompts dan project akan live
```

---

## 📱 Responsive Breakpoints

| Device      | Screen Width   | Layout                         |
| :---------- | :------------- | :----------------------------- |
| **Desktop** | > 1024px       | 3-4 columns grid, full navbar  |
| **Tablet**  | 768px - 1024px | 2-3 columns grid, sidebar menu |
| **Mobile**  | < 768px        | 1 column grid, hamburger menu  |

---

## 🎯 Fitur Challenge 2 - Detail Teknis

### Counter Logic

```javascript
// Add Count
function addCount() {
  count++;
  totalZikir++;
  updateDisplay();
  updateStatsDisplay();

  if (count >= target && !targetReached) {
    targetReached = true;
    targetCompleted++;
    showNotification(); // Confetti effect
  }

  saveToLocalStorage();
}
```

### Local Storage Data

```javascript
{
  count: 0,              // Counter saat ini
  target: 33,            // Target zikir
  currentZikir: '',      // Nama zikir yang dipilih
  currentZikirArabic: '', // Teks Arab
  currentFadhilah: '',   // Keutamaan zikir
  totalZikir: 0,         // Total kumulatif
  currentStreak: 0,      // Hari berturut-turut
  targetCompleted: 0,    // Jumlah target selesai
  lastVisitDate: ''      // Tanggal kunjungan terakhir
}
```

### Dark Mode Toggle

```javascript
function toggleDarkMode() {
  document.body.classList.toggle("dark-mode");
  const isDark = document.body.classList.contains("dark-mode");
  localStorage.setItem("darkMode", isDark);
  // Update icons (moon ↔ sun)
}
```

---

## 📊 Progress Challenge

### ✅ Challenge 1 - Completed

- [x] Halaman Beranda dengan Hero Section
- [x] Halaman Doa dengan Expandable Cards
- [x] Responsive Design (Mobile, Tablet, Desktop)
- [x] Dark Mode Support
- [x] Sidebar Navigation
- [x] Islamic Pattern Background
- [x] Bootstrap Icons Integration

### ✅ Challenge 2 - Completed

- [x] Counter Zikir Interactive
- [x] Tombol Tambah dengan Animasi
- [x] Tombol Reset
- [x] Target Display dengan Adjust (+/-)
- [x] Notification saat Target Tercapai
- [x] Confetti Effect
- [x] Progress Bar
- [x] Stats Overview (Total, Streak, Completed)
- [x] 12 Pilihan Zikir dengan Fadhilah
- [x] Local Storage (Data Persistence)
- [x] Dark Mode Toggle dengan Save
- [x] Keyboard Support (Space, R)
- [x] Vibration Feedback (Mobile)

### ⏳ Challenge 3 - Coming Soon

- [ ] _Features TBD_

### ⏳ Challenge 4 - Coming Soon

- [ ] _Features TBD_

---

## 🌐 Live Demo

| Challenge       | URL                                                                                         | Status  |
| :-------------- | :------------------------------------------------------------------------------------------ | :-----: |
| **Challenge 1** | [ramadhan-challenge-rks.vercel.app](https://ramadhan-challenge-rks.vercel.app/)             | ✅ Live |
| **Challenge 2** | [ramadhan-challenge2-rks-v19f.vercel.app](https://ramadhan-challenge2-rks-v19f.vercel.app/) | ✅ Live |

---

## 📸 Screenshots

### Challenge 1

- **Beranda:** Hero section dengan ilustrasi Ramadhan
- **Doa:** Expandable cards dengan lafal Arab, latin, arti

### Challenge 2

- **Hitung Zikir:** Counter dengan progress bar dan stats
- **Dark Mode:** Toggle mode gelap dengan save preference
- **Notification:** Popup confetti saat target tercapai

---

## 👤 Tentang Penulis

<div align="center">

### **Reni Kartika Suwandi**

**Participant - Alhazen Academy Ramadhan Coding Challenge 2026**

📧 Email: [your-email@example.com]  
💼 LinkedIn: [your-linkedin]  
🐙 GitHub: [your-github]

</div>

---

## 📄 Lisensi

Proyek ini dibuat untuk tujuan pembelajaran dalam rangka **Alhazen Academy Ramadhan Coding Challenge 2026**.

---

## 🙏 Ucapan Terima Kasih

Terima kasih kepada:

- **Alhazen Academy** - Atas kesempatan dan tantangan coding ini
- **Bootstrap Icons** - Untuk library icon yang lengkap
- **Google Fonts** - Untuk font Poppins dan Amiri
- **Vercel** - Untuk hosting dan deployment yang mudah

---

<div align="center">

### 🌟 **Semoga Ramadhan Kita Diterima Allah SWT** 🌟

**Marhaban Ya Ramadhan 1447 H**

---

Made with ❤️ by **Reni Kartika Suwandi**

</div>
