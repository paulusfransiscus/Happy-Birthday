# Website Ulang Tahun untuk Bibi 💗 (versi ringkas — 2 file)

## Isi folder
- `index.html` — halaman pembuka animasi scan QR (CSS & JS sudah menyatu di dalamnya)
- `ucapan.html` — halaman ucapan + galeri 4 foto (CSS & JS sudah menyatu di dalamnya)

Cuma 2 file ini yang perlu diupload. Nggak ada file CSS/JS terpisah lagi.

## Cara nambahin foto
1. Siapkan 4 foto, ganti namanya jadi persis: `foto1.jpg`, `foto2.jpg`, `foto3.jpg`, `foto4.jpg`
   (kalau formatnya .png, ganti juga bagian `src="foto1.jpg"` dst di dalam `ucapan.html` jadi `.png`)
2. Taruh keempat foto itu di folder yang SAMA dengan `index.html` dan `ucapan.html`.
3. Selesai — foto otomatis muncul di galeri gaya polaroid pada halaman ucapan.
   Kalau salah satu foto belum ada, tempatnya akan tampil placeholder ikon 🖼️ (nggak rusak tampilannya).

## Cara custom isi ucapan
Buka `ucapan.html` pakai text editor (Notepad, VS Code, dll), lalu ganti:
- `Bibi Kuu` → panggilan asli bibinya
- Paragraf ucapan → tulis versi kamu sendiri
- `[Nama kamu]` → nama kamu

## Cara upload ke GitHub Pages (gratis)
1. Buat repository baru di GitHub, misalnya `ucapan-ultah-bibi`.
2. Upload `index.html`, `ucapan.html`, dan keempat foto (`foto1.jpg`–`foto4.jpg`) ke repo itu.
3. Masuk ke **Settings → Pages**.
4. Di bagian **Branch**, pilih `main` dan folder `/root`, lalu **Save**.
5. Tunggu 1–2 menit, link akan muncul: `https://namakamu.github.io/ucapan-ultah-bibi/`
6. Kirim link itu ke Bibi. Dia tinggal ketuk tombol scan → otomatis pindah ke halaman ucapan + foto.

Catatan: efek "scan" dibuat pakai animasi HTML/CSS/JavaScript (bukan Python beneran),
karena GitHub Pages cuma bisa menjalankan website statis. Visualnya tetap terasa
seperti scan sungguhan kok. 🎉
