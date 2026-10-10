# Panduan Penggunaan Konverter Python ke MP4 (Portable)

Folder ini berisi sistem konversi portabel untuk menjalankan script Python (`.py`) dan merender atau mengubahnya menjadi format video MP4 menggunakan Python portable.

## 📁 Struktur Folder
Pastikan struktur folder Anda sesuai dengan susunan berikut agar file `conversi.bat` dapat berjalan dengan lancar:

```text
python portabel/
│
├── py/             <-- Tempat menaruh file script python (.py) yang akan dikonversi
├── python/         <-- Folder mesin Python portable beserta pustaka (library) pendukung
├── video/          <-- Tempat hasil output video (.mp4) tersimpan
└── conversi.bat    <-- File batch utama untuk menjalankan proses konversi
```

---

## 🚀 Cara Penggunaan

1. **Masukkan Script Python (.py):**
   * Letakkan file script Python yang ingin Anda ubah menjadi video ke dalam folder `py`.
   * Pastikan script Anda sudah dirancang untuk menghasilkan output video (misalnya menggunakan pustaka seperti `manim`, `opencv-python`, atau `pygame` dengan perekam frame).

2. **Jalankan File Batch:**
   * Klik dua kali pada file `conversi.bat`.
   * Sistem akan otomatis menggunakan mesin Python dari folder `python` untuk memproses script yang ada di folder `py`.

3. **Ambil Hasil Video:**
   * Setelah proses selesai, buka folder `video` untuk melihat hasil file video dengan format `.mp4`.

---

## 🛠️ Catatan Penting
* Pastikan pustaka yang dibutuhkan oleh script Python Anda (seperti `opencv-python`, `moviepy`, dll.) sudah terinstal di dalam lingkungan Python portable pada folder `python`.
* Jika terjadi error, pastikan nama file dan path folder tidak mengandung karakter khusus yang bermasalah di Command Prompt Windows.