# BelHitung - Game Edukasi Matematika untuk Anak

Game interaktif berbasis web untuk membantu anak-anak belajar berhitung dengan cara yang menyenangkan. Menggunakan emoji sebagai alat bantu visual agar lebih mudah dipahami.

## Fitur

- 3 level permainan dengan tingkat kesulitan bertahap
- Tampilan visual menggunakan emoji (buah, hewan, bintang, dll)
- Efek suara untuk jawaban benar dan salah
- Sistem penilaian dengan grade (A+, A, B, C, D)
- Animasi confetti untuk skor sempurna
- Responsif, bisa dimainkan di HP maupun komputer

## Level Permainan

| Level | Nama | Deskripsi |
|-------|------|-----------|
| 1 | 🔢 Menghitung Benda | Menghitung jumlah emoji yang ditampilkan (1-15) |
| 2 | ➕ Penjumlahan | Menjumlahkan dua kelompok benda |
| 3 | ➖ Pengurangan | Mengurangi satu kelompok benda dari kelompok lainnya |

Setiap level terdiri dari **10 soal** dengan 4 pilihan jawaban.

## Cara Menjalankan

Tidak perlu instalasi apapun. Cukup buka file `index.html` di browser.

```bash
# Atau gunakan local server (opsional)
python -m http.server 8000
# Lalu buka http://localhost:8000
```

## Teknologi

- HTML5
- CSS3
- JavaScript (Vanilla, tanpa framework)
- Web Audio API (efek suara)
- Canvas API (animasi confetti)
