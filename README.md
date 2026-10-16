# 🎂 Website Kartu Ucapan Ulang Tahun Aesthetic

Website kartu ucapan ulang tahun interaktif bertema langit malam (*aesthetic navy, dark, and glowing sky blue*), dilengkapi dengan amplop 3D yang bisa dibuka, surat ucapan yang menyentuh hati, pemutar musik, dan fitur kejutan kue interaktif dengan lilin yang bisa ditiup.

---

## 📁 Struktur File dalam Folder

```text
kartu-ucapan-ulang-tahun/
│
├── index.html        # Semua kode HTML, CSS, dan JavaScript berada di sini
├── lagu.mp3          # Musik instrumen piano Selamat Ulang Tahun
└── README.md         # Panduan penggunaan & kustomisasi
```

---

## 🚀 Cara Menjalankan di VS Code

### Cara 1: Menggunakan Live Server (Direkomendasikan)
1. Buka aplikasi **VS Code**.
2. Klik menu **File** > **Open Folder...** (atau tekan `Ctrl + K, Ctrl + O`).
3. Pilih folder:
   `F:\Kuliah Nafis\kartu-ucapan-ulang-tahun`
4. Pastikan ekstensi **Live Server** sudah terpasang di VS Code (jika belum, buka tab *Extensions* / `Ctrl + Shift + X`, cari *Live Server* oleh Ritwick Dey, lalu klik *Install*).
5. Klik kanan pada file `index.html` > pilih **"Open with Live Server"** (atau klik tombol *Go Live* di pojok kanan bawah VS Code).
6. Browser akan otomatis terbuka dan menampilkan kartu ucapan! 🎉

### Cara 2: Langsung Buka di Browser (Tanpa Ekstensi)
1. Buka folder `kartu-ucapan-ulang-tahun` di File Explorer Windows.
2. Klik dua kali (*double click*) pada file `index.html`.
3. Website akan langsung terbuka di Google Chrome / Edge / browser bawaan laptop Anda.

---

## 🎵 Fitur Musik
- Menggunakan lagu **"Happy Birthday Song" oleh CoComelon** sesuai tautan Spotify ([Spotify Track Link](https://open.spotify.com/track/2R5iTxkCln6NLTw6l0kjWw)).
- Tombol **Putar Musik** akan langsung memainkan lagu tersebut dengan animasi piringan hitam yang berputar dan fitur looping otomatis.
- File versi alunan piano sebelumnya tetap tersimpan aman sebagai `lagu_piano_lama.mp3`.
- Terdapat tautan langsung *Buka di Spotify* di widget musik untuk kemudahan akses.
- Jika suatu saat file `lagu.mp3` tidak ditemukan, sistem sudah memiliki **Smart Fallback** otomatis menggunakan *Web Audio API* yang menghasilkan melodi denting kotak musik kristal.

### Cara Mengganti Musik dengan Lagu Favorit Anda:
1. Siapkan file musik pilihan Anda yang berformat `.mp3`.
2. Ganti nama file tersebut menjadi `lagu.mp3`.
3. Pindahkan file tersebut ke dalam folder yang sama dengan `index.html` (timpa file lama).
4. Selesai! Lagu baru akan otomatis diputar saat tombol musik ditekan.

---

## ✏️ Cara Mengubah Isi Surat & Nama
Jika ingin mengubah ucapan untuk seseorang yang spesial:
1. Buka file `index.html` di VS Code.
2. Cari bagian `<article class="letter-body">` (sekitar baris 400).
3. Anda bisa langsung mengganti teks ucapan, nama penerima, maupun nama pengirim sesuai keinginan.
4. Simpan perubahan dengan menekan `Ctrl + S`.
