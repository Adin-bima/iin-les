# Les Privat Bunda Iin

Pamflet web interaktif untuk les privat ke rumah di Mataram dan sekitarnya.
Situs statis: satu `index.html`, tanpa build step.

## Deploy ke Vercel

1. Buat repo baru di GitHub, lalu push isi folder ini:
   ```bash
   git init
   git add .
   git commit -m "Pamflet les privat Bunda Iin"
   git branch -M main
   git remote add origin https://github.com/USERNAME/les-privat-bunda-iin.git
   git push -u origin main
   ```
2. Buka vercel.com → **Add New → Project** → pilih repo tersebut.
3. Framework Preset: **Other**. Build Command dan Output Directory dikosongkan.
4. Klik **Deploy**. Situs langsung aktif di `nama-proyek.vercel.app`.

## Mengubah isi

Semua teks ada di `index.html`:
- Kredensial dan deskripsi detail: array `creds` di bagian `<script>`.
- Nomor WhatsApp: cari `6282323033171` dan `+62 823-2303-3171`.
- Email: cari `iinmutmainah626@gmail.com`.
