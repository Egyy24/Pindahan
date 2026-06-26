# Pindahan – Asisten Pindahan Rumah

**Pindahan** adalah aplikasi web *all-in-one* untuk membantu Anda merencanakan dan menjalankan proses pindahan rumah secara terstruktur. Mulai dari daftar barang, timeline tugas, anggaran, estimasi volume, tata letak ruangan, hingga doa dan adab Islami, semua tersedia dalam satu halaman.

> Dibangun dengan **React + Tailwind CSS**, data disimpan **sepenuhnya di browser (localStorage)** tanpa server.

---

## Tampilan

- Dashboard progres packing dan anggaran
- Checklist barang dengan kategori dan prioritas
- Timeline tugas dengan deadline
- Budget planner + grafik pengeluaran
- Estimasi volume dan rekomendasi kendaraan
- Room planner (grid 10×10) dengan penanda arah kiblat
- Move Day checklist (sebelum, saat, setelah)
- Laporan akhir yang bisa dicetak (print) atau diekspor JSON
- Doa dan dzikir hijrah (6 doa pilihan)
- Adab bertetangga (checklist sunnah)

---

## Fitur Utama

| Fitur | Deskripsi |
|-------|-----------|
| **Checklist Barang** | Tambah, edit, hapus, tandai sudah dipacking. Filter kategori, cari, urutkan prioritas. |
| **Timeline** | Buat tugas dengan deadline dan status (Belum/Sedang/Selesai). Kalender mini menampilkan tugas per tanggal. |
| **Budget Planner** | Atur total budget, catat pengeluaran per kategori, lihat grafik pie & bar. |
| **Prioritas Packing** | Kelompokkan barang berdasarkan prioritas (Sangat Penting sampai Tidak Mendesak). |
| **Estimasi Volume** | Hitung total volume barang dan dapatkan rekomendasi kendaraan (motor, mobil, truk). |
| **Room Planner** | Tata furniture di grid 10×10. Simpan denah dan tandai arah kiblat. |
| **Move Day Checklist** | Checklist khusus hari-H (sebelum berangkat, saat pindahan, setelah sampai). |
| **Laporan Akhir** | Ringkasan lengkap + grafik + jurnal refleksi hijrah. Bisa **print** atau **export JSON**. |
| **Doa dan Dzikir** | 6 doa pilihan untuk keluar rumah, perjalanan, masuk rumah baru, istikharah, dan syukur. Tandai sudah dibaca. |
| **Adab Bertetangga** | Daftar adab Islami + checklist pelaksanaan, bisa tambah sendiri. |
| **Mode Gelap** | Nyaman digunakan malam hari. |

---

## Teknologi

- **React 18** (tanpa build tool, menggunakan CDN)
- **Tailwind CSS** (via CDN)
- **Recharts** untuk grafik
- **Babel Standalone** untuk JSX
- **localStorage** untuk penyimpanan data

---

## Instalasi & Penggunaan

Karena ini adalah **single HTML file**, tidak perlu instalasi atau server khusus.

### Cara menjalankan:
1. Unduh file `pindahan.html`.
2. Buka dengan browser modern (Chrome, Firefox, Edge, Safari).
3. Mulai isi data dari menu **Panduan** atau langsung ke **Budget Planner** untuk atur tanggal & anggaran.

> **Catatan:** Semua data disimpan di browser Anda. Tidak ada sinkronisasi antar perangkat. Backup data melalui tombol **Export JSON** di halaman Laporan Akhir.

### Mode Pengembangan (jika ingin mengedit):
- Buka file di editor teks.
- Ubah kode JSX di dalam `<script type="text/jsx-source">`.
- Simpan dan refresh browser.

---

## Panduan Singkat

1. **Atur Budget dan Tanggal** → Menu Budget Planner, klik "Set Budget".
2. **Daftarkan Barang** → Checklist Barang, tambahkan semua barang.
3. **Tentukan Prioritas** → Menu Prioritas Packing.
4. **Susun Timeline** → Tambahkan tugas & deadline.
5. **Catat Pengeluaran** → Budget Planner.
6. **Estimasi Volume** → Isi jumlah kardus/furnitur.
7. **Rencanakan Ruang** → Room Planner.
8. **Hari-H** → Move Day Checklist.
9. **Laporan** → Cetak atau export.

---

## Cetak Laporan

- Buka halaman **Laporan Akhir**.
- Klik tombol **Print**.
- Hasil cetak sudah diatur untuk ukuran A4 dengan margin rapi.

---

## FAQ

**Apakah data aman?**  
Ya. Data hanya disimpan di localStorage perangkat Anda, tidak dikirim ke internet.

**Apakah data hilang jika browser ditutup?**  
Tidak. Data tetap ada selama Anda menggunakan browser yang sama.

**Bagaimana cara backup?**  
Buka Laporan Akhir, Export JSON, simpan file. Untuk restore, impor melalui developer tools (localStorage).

**Bisa digunakan di HP?**  
Ya, responsif untuk semua ukuran layar.

---

## 🤝 Kontribusi

Karena ini adalah file tunggal, Anda bebas memodifikasi sesuai kebutuhan. Jika menemukan bug atau punya saran, silakan buka issue di repositori.

---
