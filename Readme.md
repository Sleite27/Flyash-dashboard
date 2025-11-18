# Fly Ash Management Dashboard

Prototype **web-based dashboard** untuk manajemen pengelolaan dan pengolahan fly ash di PLTU.

Dashboard ini fokus pada:
- Ringkasan produksi fly ash per hari
- Tingkat pemanfaatan fly ash
- Stok di silo dan landfill
- Pendapatan dari pemanfaatan fly ash
- Ringkasan mutu / kualitas batch fly ash untuk pengambilan keputusan pemanfaatan (silika, semen, dll)

> Status: **Prototype UI v0.1** – data masih dummy / statis.

---

## 🔧 Cara Menjalankan Secara Lokal

1. Clone atau download repo ini.
2. Buka file `index.html` dengan browser (Chrome, Edge, dsb):
   - Klik dua kali `index.html`, atau
   - Drag & drop `index.html` ke jendela browser.

Tidak diperlukan backend atau instalasi apa pun.

---

## 🌐 Deploy dengan GitHub Pages

1. Buka repo ini di GitHub.
2. Masuk ke tab **Settings** → **Pages**.
3. Pada bagian *Source*, pilih:
   - `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
4. Klik **Save**.
5. Setelah beberapa detik, GitHub akan memberikan URL seperti:

   `https://username.github.io/flyash-dashboard`

---

## 📂 Struktur Folder

```text
flyash-dashboard/
├── index.html      # Halaman utama dashboard
├── README.md       # Dokumentasi proyek
├── .gitignore      # File yang diabaikan oleh Git
├── LICENSE         # Lisensi MIT
└── assets/
    ├── img/        # (opsional) untuk logo/gambar
    ├── css/        # (opsional) untuk file CSS terpisah
    └── js/         # (opsional) untuk file JavaScript