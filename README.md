# Display TV - PMB UIN Sunan Ampel Surabaya

Display informasi digital untuk layar TV/monitor.

## Cara Deploy ke Vercel

1. Push repo ini ke GitHub
2. Buka [vercel.com](https://vercel.com) → Import Git Repository
3. Pilih repo ini → Deploy (tanpa konfigurasi tambahan)

## Penggunaan

- Klik ikon ⚙️ (kanan atas) untuk membuka panel pengaturan
- Atau tekan tombol **S** di keyboard

### Panel Pengaturan:
| Fitur | Cara |
|---|---|
| Background | Upload gambar dari perangkat |
| YouTube | Paste URL → Tambah Video (bisa banyak) |
| Timeline | Paste link Google Sheet publik → Muat |
| Poster | Paste link share Google Drive → Tambah |

### Format Google Sheet:
| A | B | C |
|---|---|---|
| Nama Kegiatan | Tanggal (YYYY-MM-DD) | Keterangan |

Sheet harus di-share: **Anyone with the link → Viewer**

### Shortcut Keyboard:
- `S` — buka/tutup pengaturan
- `→` — video berikutnya
- `←` — video sebelumnya
- `Esc` — tutup pengaturan

## Catatan
- Google Sheet harus publik (Anyone with the link - Viewer)
- Gambar Google Drive harus di-share publik (Anyone with the link)
- Timeline auto-refresh setiap 5 menit
