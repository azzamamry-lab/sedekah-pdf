# Sedekah Subuh — Landing Page

Landing page Sedekah Subuh untuk Yayasan Nur Mirah. Desain ditiru dari referensi PDF
yang diberikan, dengan foto dari Wikimedia Commons (lisensi bebas komersial).

## 🌐 Link Live

**https://azzamamry-lab.github.io/sedekah-pdf/**

## Struktur Halaman

1. **Header** — transparan di atas hero, berubah putih saat digulir
2. **Hero** — foto sunrise, judul serif, 3 trust badge, kutipan
3. **Keutamaan** — hadis (HR. Bukhari-Muslim) + 4 poin
4. **Program** — 4 kartu dengan foto
5. **Cara Ikut** — 4 langkah dengan panah penghubung
6. **Dampak** — foto gelap masjid + 2 poin jaminan
7. **FAQ** — 6 pertanyaan, dua kolom
8. **CTA Akhir** — foto masjid saat matahari terbit
9. **Footer** — putih, 3 kolom

## Fitur

- Responsif penuh (desktop, tablet, mobile)
- Header transparan yang berubah saat digulir
- Menu mobile dengan tombol Escape (aksesibilitas keyboard)
- FAQ accordion
- Tanpa dependensi, tanpa build step. Cukup buka `index.html`.

## Palette

| Warna | Kode | Dipakai untuk |
|---|---|---|
| Hijau tua | `#1B4332` | Tombol, judul, aksen utama |
| Hijau medium | `#2D6A4F` | Hover state |
| Hijau muda | `#D8F3DC` | Latar ikon, aksen |
| Krem | `#F6F1E7` | Latar section |
| Abu muda | `#F2F2F0` | Kotak FAQ |
| Emas | `#D9A441` | Aksen, kutipan |

## Tipografi

- **Judul**: Fraunces (serif) — kesan elegan
- **Body**: Plus Jakarta Sans — mudah dibaca

## Foto

Semua foto dari **Wikimedia Commons**, lisensi bebas komersial.
Daftar lengkap ada di `img/SUMBER-DAN-LISENSI.txt`.

## Yang Masih Perlu Diisi

- Nomor rekening dan QRIS (belum ada di desain referensi)
- Kontak dan link sosial media asli
- Nama yayasan (masih "Yayasan Nur Mirah" dari referensi)

## Menjalankan Lokal

Buka langsung `index.html` di browser, atau:
```bash
python -m http.server 8090
```
lalu buka http://localhost:8090
