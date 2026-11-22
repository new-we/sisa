# Pitch Tahap 0 — Aplikasi Pengeluaran Anak Kos

*1 halaman pitch untuk sesi approval mentor (sesuai Panduan Pengerjaan MVP Landing Page)*

## Opsi
**B — Produk baru.** Aplikasi pencatat pengeluaran khusus anak kos (bukan fitur tambahan di produk yang sudah ada).

## Target user (spesifik)
Anak kos usia 18–28 tahun — mahasiswa dan pekerja muda — yang menerima uang saku/gaji bulanan, belanja harian lewat HP, dan sering tidak sadar uangnya habis ke mana sebelum tanggal gajian.

## Problem (1 kalimat)
Anak kos sering kehabisan uang sebelum gajian karena tidak tahu uangnya habis untuk apa.

## Solusi (1 kalimat)
Aplikasi pencatat pengeluaran harian dengan kantong per kategori, riwayat transaksi, dan chart bulat — plus pengingat sisa uang sampai tanggal gajian.

## Fitur inti (MVP)
1. **Gaji / uang saku** — catat pemasukan bulanan dan tanggal gajian.
2. **Tracking history** — riwayat semua pemasukan dan pengeluaran.
3. **Kategori pengeluaran** — transportasi, belanja, tagihan, makan, dan lain-lain.
4. **Kantong** — anggaran per kategori dengan sisa saldo dan progress bar.
5. **Chart bulat** — diagram lingkaran pembagian pengeluaran per kategori.
6. **Sisa hari ini** — pengingat sisa uang harian sampai gajian berikutnya.

## Yang dikumpulkan lewat form
- Waitlist: nama + email/WA.
- Minat: bersedia mencoba versi beta atau tidak.
- 3 pertanyaan validasi:
  1. Kategori pengeluaran terbesarmu apa? (Makan / Transportasi / Belanja / Tagihan / Lainnya)
  2. Pernah kehabisan uang sebelum gajian? (Ya, sering / Pernah / Tidak pernah)
  3. Apa yang paling kamu butuhkan dari aplikasi pencatat uang? (jawaban singkat)

## Hipotesis yang divalidasi
Minimal 30% pengunjung landing page mau daftar waitlist.

## Referensi desain
Gaya **Minimalism** dari reel @ux.kia (screenshot: `workspace/user/files/1001309545_1_f2zz.jpg`) — latar putih bersih, aksen ungu, kartu saldo + kantong dengan progress bar, navigasi bawah Beranda / Kantong / Bayar / Riwayat.

## Referensi waitlist (file: `referensi-waitlist-sisa.html`)
Landing page "Sisa" — hero + kalkulator interaktif "Uangmu habis tanggal berapa?" (input gaji + pengeluaran harian → hasil + bar 30 hari), 3 masalah, 3 langkah cara kerja, form waitlist (nama, kontak, 2 pertanyaan validasi), FAQ. Gaya: latar #EEF2F7, aksen kuning #F2A900, judul Bricolage Grotesque, isi Instrument Sans. **Catatan: form referensi menyimpan ke penyimpanan Claude — versi kita wajib nyambung ke Google Sheets via Apps Script (sesuai panduan).** Alur baru (perintah ARIEF 20 Nov 19:03): tombol form **"Gabung Waitlist & Coba Aplikasi"** — saat diklik, data waitlist disimpan lalu langsung membuka **halaman aplikasi sendiri (`aplikasi.html`)**. Bagian preview "Coba aplikasi" di landing page DIHAPUS (dicoret ARIEF di screenshot).

## Nama aplikasi
**Sisa** — nama final (diganti kembali dari "Sangu" 22 Nov 2026 atas permintaan client Sabrina; "Sangu" sempat dipilih ARIEF 20 Nov 2026 19:41 dari ide-ide MUMU).
