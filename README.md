# HUMAN + AI — Bandung Innovation Week 2026

Presentasi interaktif berbasis HTML: **HUMAN + AI — The Future of Digital Product Development**.

Membangun produk digital melalui kolaborasi manusia dan AI.

**Presenter:** Julianto Ahmad Nugraha
**Event:** Bandung Innovation Week 2026
**Durasi:** 25 menit · 12 slide · kanvas 1920 × 1080 (16:9)

---

## Menjalankan secara lokal

Tidak perlu build, dependency, atau server. Cukup buka `index.html` di browser:

```bash
open index.html          # macOS
# atau drag file ke browser
```

## Kontrol saat presentasi

| Tombol | Fungsi |
|---|---|
| `→` `Space` `Enter` `PageDown` | Slide berikutnya |
| `←` `PageUp` | Slide sebelumnya |
| `Home` / `End` | Slide pertama / terakhir |
| `F` | Mode fullscreen |
| `N` | Panel catatan pembicara |
| `Esc` | Tutup panel catatan |

Tersedia juga: klik area kiri/kanan layar, swipe di perangkat sentuh, progress bar di atas,
indikator ACT dan nomor slide, dan URL hash (`#7`) untuk menuju slide tertentu.

## Struktur

```
index.html      — presentasi (self-contained: CSS + JS inline)
assets/         — 12 aset foto editorial grayscale
```

## Sistem visual

**Dynamic Editorial — Modern Brutalist, Human-Centered Storytelling**

| Token | Hex | Penggunaan |
|---|---|---|
| Dark Charcoal | `#101310` | Latar utama |
| Lime Green | `#A6F542` | Aksen & highlight |
| Off White | `#F2F4EF` | Teks utama & bidang terang |
| Muted Gray | `#747D73` | Teks sekunder |

Tipografi: Archivo / Archivo Black (display), IBM Plex Mono (metadata).
Seluruh aset fotografi dibiarkan grayscale; lime green hanya dipakai sebagai aksen grafis.

## Aksesibilitas

- Mendukung `prefers-reduced-motion` — seluruh animasi dimatikan, konten tetap utuh
- Semua informasi terbaca tanpa bergantung pada animasi
- Kontras teks memenuhi WCAG AA

## Catatan

- Slide 09: *illustrative case study* — bukan hasil riset pasien aktual
- Slide 10: *conceptual redesign* — belum divalidasi, bukan hasil teruji
- Speaker notes belum ditulis; panel [N] menampilkan arahan produksi per slide
