# Sisa

Aplikasi pencatat pengeluaran harian untuk anak kos. Catat dalam 30 detik sehari, tahu sisa uang sampai gajian.

**Live:** https://new-we.github.io/sisa/

## Masalah

Anak kos sering kehabisan uang sebelum gajian karena tidak tahu uangnya habis untuk apa.

## Solusi

- **Uang bulanan & tanggal gajian** — atur sekali, Sisa menghitung sisanya.
- **Sisa hari ini** — pengingat berapa yang boleh dipakai per hari sampai gajian berikutnya.
- **Kantong per kategori** — Makan, Transportasi, Belanja, Tagihan, Lainnya, masing-masing dengan anggaran.
- **Chart bulat** — pangsa pengeluaran sekilas.
- **Riwayat transaksi** — catat, lihat, hapus per item.

## Isi repo

| File | Isi |
|---|---|
| `index.html` | Landing page MVP + kalkulator "Uangmu habis tanggal berapa?" + form waitlist |
| `aplikasi.html` | Demo aplikasi (coba setelah isi waitlist) |
| `pitch-tahap-0.md` | Pitch Tahap 0: ide, target user, problem, solusi, hipotesis validasi |
| `PRD-Sisa.pdf` | Product Requirements Document v1.0 (16 halaman) |

## Cara coba

1. Buka https://new-we.github.io/sisa/
2. Isi form waitlist di bawah, tekan **Gabung Waitlist & Coba Aplikasi**.
3. Kamu langsung masuk ke demo aplikasinya dan bisa mencatat pengeluaran.

## Status

MVP tahap validasi (tugas kelas). Form waitlist untuk sekarang tersimpan di browser pengunjung (localStorage) — penyambungan ke Google Sheets menyusul. Target validasi: minimal 30% pengunjung landing page daftar waitlist, 50 pendaftar, 20% bersedia interview lanjut.
