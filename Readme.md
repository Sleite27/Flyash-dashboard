# CIRCA Dashboard (Dummy)
**CIRCA — Carbon Intensity Real-time Control Assistant**

Dashboard web statis (prototype) untuk menampilkan konsep sistem CIRCA: pemantauan **Carbon Intensity (kg CO₂/MWh)** dan **AI Recommendation Log** berbasis data (dummy).  
Dipakai untuk kebutuhan cover/proposal/Power Idea Contest, dan dapat dikembangkan menjadi dashboard real-time terintegrasi historian/DCS.

---

## Preview Fitur
- KPI utama:
  - Carbon Intensity (kg CO₂/MWh)
  - CO₂ Emissions Today (ton/hari)
  - Net Load (MW)
  - Aux Power (MW)
- Grafik tren 14 hari:
  - Carbon Intensity (kg CO₂/MWh)
  - CO₂ Rate (t/h)
- Input data manual (dummy) untuk update grafik
- Hapus data (per tanggal / undo terakhir)
- AI Recommendation Log:
  - Tambah rekomendasi + estimasi impact (kg CO₂/MWh)
  - Status: Recommended / Applied / Hold
- Penyimpanan lokal menggunakan `localStorage` (tanpa backend)

> Catatan: Semua data saat ini **dummy** dan hanya untuk demonstrasi UI/konsep.

---

## Struktur File

---

## Cara Menjalankan (Local)
### Opsi 1 — Langsung buka
- Klik dua kali `index.html` → akan terbuka di browser.

### Opsi 2 — Live Server (disarankan)
Jika pakai VS Code:
1. Install extension **Live Server**
2. Klik kanan `index.html` → **Open with Live Server**

---

## Deploy ke GitHub Pages
1. Buat repository baru (misal: `circa-dashboard`)
2. Upload `index.html` dan `README.md`
3. Masuk ke **Settings → Pages**
4. Source: **Deploy from a branch**
5. Branch: `main` dan folder: `/ (root)`
6. Save → link GitHub Pages akan muncul

---

## Kustomisasi Cepat
Di `index.html`, kamu bisa ubah:
- Nama unit / kapasitas (400 MW & 600 MW)
- Target Carbon Intensity (misal: 1020 kg CO₂/MWh)
- Data default grafik (array `ciData` dan `co2RateData`)
- Isi rekomendasi dummy (array `recoList`)

---

## Rencana Pengembangan (Roadmap)
- Integrasi data historian (CSV export / API / PI System connector)
- Parameter snapshot: O₂ stack, MS spray, RH spray, vacuum, aux load
- Forecast baseline vs optimized (prediksi CO₂ tahunan)
- Model rekomendasi berbasis machine learning (regression / tree-based model)
- User management + audit trail untuk kebutuhan MRV

---

## Lisensi
Prototype internal untuk kebutuhan riset/kompetisi.  
Silakan tambahkan lisensi sesuai kebijakan organisasi (MIT/Apache-2.0/internal).

---

## Kontak
Owner/Engineer: **Syarif (UBP Suralaya)**  
Project: **Power Idea Contest 2026 — CIRCA**
