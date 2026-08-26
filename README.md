# Club Royal Lounge — Undangan Grand Opening (Roblox)

Website undangan single-page bertema **Royal Gold / Club Kerajaan**, lengkap dengan:
- Logo asli **Royal Lounge** kamu dipakai langsung di halaman gerbang & hero
- Banner "Club Royal" jadi showcase image di tengah halaman
- Efek **gerbang tirai beludru (curtain reveal)** — tirai kiri-kanan terbuka saat tombol "Buka Undangan" ditekan
- Lampu sorot klub berputar (rotating spotlight rays) di background
- Partikel emas melayang + cincin cahaya berdenyut di sekitar logo
- Teks berjalan (marquee) "CLUB ROYAL LOUNGE · GRAND OPENING · FAMS & CLAN WELCOME"
- **Musik dari YouTube** (video yang kamu kasih) otomatis diputar begitu tirai dibuka
- Tombol **"Gabung ke Club Royal Lounge"** yang langsung membuka link Roblox kamu
- Semua kata-kata sudah diubah jadi gaya mengundang ke **club malam Roblox**, dresscode dihapus

## Struktur file (WAJIB upload semua, jangan cuma index.html)
```
index.html
assets/
  royal-logo.png
  royal-banner.jpg
  royal-poster.jpg
```
Gambar-gambar ini dipakai langsung oleh index.html, jadi kalau tidak diupload, logo & banner tidak akan muncul.

## Cara upload ke GitHub Pages
1. Buat repository baru di GitHub (public), contoh: `club-royal-lounge`.
2. Klik **Add file > Upload files**, lalu drag semua file di atas **sekaligus dengan struktur foldernya** (folder `assets` ikut ter-upload, atau upload manual: buat folder `assets` di GitHub lalu upload 3 gambar ke situ).
3. Buka **Settings > Pages**.
4. Di bagian **Source**, pilih branch `main` dan folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit, link undangan kamu aktif di:
   `https://<username-github-kamu>.github.io/club-royal-lounge/`

## Catatan
- Musik akan otomatis mulai begitu tamu menekan tombol **"Buka Undangan"** di tirai pembuka (browser mengharuskan ada klik dulu sebelum audio bisa nyala, jadi ini normal & aman).
- Tombol musik kecil di pojok kanan bawah bisa dipakai untuk jeda/lanjut musik kapan saja.
- Link tombol join sudah diarahkan ke map Roblox kamu.
