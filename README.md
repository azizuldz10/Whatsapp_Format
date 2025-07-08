# WhatsApp Number Formatter Tool

Tool web sederhana untuk membersihkan dan memformat nomor WhatsApp Indonesia ke format standar.

## 🚀 Fitur

- **Auto Format**: Mengkonversi berbagai format nomor WA menjadi format standar Indonesia (081xxxxxxxxx)
- **Batch Processing**: Memproses banyak nomor sekaligus (satu per baris)
- **Validasi**: Memvalidasi nomor WhatsApp Indonesia yang valid
- **Statistik**: Menampilkan jumlah nomor valid dan invalid
- **Copy to Clipboard**: Fitur copy hasil dengan satu klik
- **Responsive Design**: Tampilan yang responsif untuk desktop dan mobile

## 📱 Format yang Didukung

Tool ini dapat mengkonversi berbagai format nomor WhatsApp menjadi format standar:

| Input | Output |
|-------|--------|
| `+62 813-1751-2977` | `081317512977` |
| `0813.1751.2977` | `081317512977` |
| `62 813 1751 2977` | `081317512977` |
| `+62-813-1751-2977` | `081317512977` |
| `62813-1751-2977` | `081317512977` |

## 🛠️ Cara Menggunakan

1. **Buka file `index.html`** di browser web Anda
2. **Masukkan nomor WhatsApp** di textarea input (satu nomor per baris)
3. **Klik tombol "Format Nomor"** untuk memproses
4. **Lihat hasil** di textarea output
5. **Copy hasil** dengan klik tombol "Copy Hasil"

## 📋 Contoh Penggunaan

### Input:
```
+62 813-1751-2977
0813.1751.2977
62 813 1751 2977
+62-821-1234-5678
0856 1234 5678
```

### Output:
```
081317512977
081317512977
081317512977
082112345678
085612345678
```

## ✅ Validasi Nomor

Tool ini memvalidasi nomor WhatsApp Indonesia dengan kriteria:
- Dimulai dengan `08`
- Digit kedua adalah `1-9` (operator seluler Indonesia)
- Panjang total 10-13 digit
- Hanya berisi angka setelah dibersihkan

## 🎨 Fitur UI

- **Design Modern**: Menggunakan tema WhatsApp (hijau)
- **Responsive**: Tampilan optimal di desktop dan mobile
- **User Friendly**: Interface yang intuitif dan mudah digunakan
- **Real-time Stats**: Menampilkan statistik hasil pemrosesan
- **Visual Feedback**: Animasi dan feedback untuk interaksi user

## 🔧 Teknologi

- **HTML5**: Struktur halaman
- **CSS3**: Styling dan responsive design
- **JavaScript**: Logic pemrosesan dan validasi nomor
- **No Dependencies**: Tidak memerlukan library eksternal

## 📁 Struktur File

```
NO WA/
├── index.html          # File utama aplikasi web
└── README.md          # Dokumentasi
```

## 🚀 Menjalankan Aplikasi

1. **Download/Clone** repository ini
2. **Buka `index.html`** di browser web favorit Anda
3. **Mulai gunakan** tool untuk memformat nomor WhatsApp

Tidak perlu instalasi server atau dependency tambahan!

## 📝 Catatan

- Tool ini khusus untuk nomor WhatsApp Indonesia
- Nomor yang tidak valid akan diabaikan dalam output
- Hasil dapat langsung di-copy untuk digunakan di aplikasi lain
- Tool bekerja offline setelah halaman dimuat

## 🤝 Kontribusi

Silakan buat issue atau pull request jika ada saran perbaikan atau fitur tambahan.

## 📄 Lisensi

Tool ini bebas digunakan untuk keperluan pribadi maupun komersial.
