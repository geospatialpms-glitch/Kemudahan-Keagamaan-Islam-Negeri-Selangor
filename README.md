# Dashboard Kemudahan Keagamaan (Islam) Negeri Selangor

Dashboard interaktif berdasarkan fail Shapefile Kemudahan Keagamaan (Islam) Negeri Selangor terkini yang diberikan. 1,587 tapak (476 Masjid dan 1,111 Surau), 9 daerah, 12 PBT, 592.59 hektar.

## GitHub Pages
1. Cipta repositori baharu di GitHub.
2. Muat naik kedua-dua fail `index.html` dan `data.json` pada akar repositori.
3. Pergi ke Settings → Pages → Build and deployment → Deploy from a branch; pilih `main` dan `/(root)`, kemudian Save.
4. Buka `https://NAMA-PENGGUNA.github.io/NAMA-REPO/` selepas penerbitan siap.

Peta satelit dan Leaflet memerlukan sambungan internet. Data tapak dimuatkan daripada `data.json`. Buka melalui GitHub Pages atau pelayan web tempatan (contohnya `python -m http.server 8000`), bukan dengan double-click fail HTML.

## Nota Data
- Data asal mengandungi **hanya** dua kategori: Masjid dan Surau. Kategori dikekalkan daripada data terkini yang diberikan. Rekod Surau Haji Abdullah Fakeh (Surau Kariah) telah dikategorikan sebagai Surau mengikut fail terbaru. Percanggahan nama/kategori lain memerlukan pengesahan sumber rasmi sebelum sebarang pembetulan.
- Keluasan dijumlahkan daripada medan `Luas_Hek`.
- Kedudukan penanda ialah titik wakil dalam poligon tapak. Klik penanda → "Lihat Sempadan Tapak" untuk melihat poligon sebenar.
- Tiada data status operasi/agama tambahan; medan tersebut tidak direka.
- Reka letak dashboard diinspirasikan daripada dashboard Tapak Perkuburan Negeri Selangor.
