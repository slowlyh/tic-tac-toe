# Tic-Tac-Toe — vs. the System

Tic-tac-toe melawan komputer. Single file: HTML + CSS + JS dalam satu dokumen, tanpa dependency — cukup buka di browser.

## Fitur

- **3 tingkat kesulitan**
  - Easy — langkah acak
  - Medium — menang/blok saat bisa, tapi kadang lengah
  - Hard — algoritma minimax, *tidak mungkin dikalahkan* (terburuk: seri)
- **Ledger** — papan skor You / Draws / System lintas ronde
- **Tweaks panel** — tema Paper (terang) / Ink (gelap), toggle animasi; tersimpan di `localStorage`
- Animasi goresan X/O digambar via SVG, garis kemenangan ditarik otomatis
- Responsif, state focus/hover, mendukung `prefers-reduced-motion`

## Menjalankan

Buka langsung:

```
Tic-Tac-Toe.html
```

atau serve lokal:

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000/Tic-Tac-Toe.html
```

## Cara main

Kamu **X**, sistem **O**. Klik kotak kosong untuk bermain. Tiga simbol sejajar menang.

> Tips: lawan Hard selalu main optimal — cotek tengah dulu kalau jalan duluan.
